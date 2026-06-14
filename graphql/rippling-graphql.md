# Rippling GraphQL Schema

## Overview

This document describes a conceptual GraphQL schema for the Rippling unified workforce platform. Rippling provides REST APIs across HR, IT, and Finance domains. The GraphQL schema presented here models the same underlying resources — employees, payroll, benefits, devices, apps, identity, and spend — as a unified graph that traverses organizational structure, compensation, and access management in a single query surface.

Rippling does not currently publish an official GraphQL API. This schema is a conceptual representation derived from the published REST API reference at https://developer.rippling.com/docs/rippling-api and the platform documentation at https://developer.rippling.com/.

## Domain Coverage

The schema spans eight product domains:

**HRIS Core** — Employee profiles, departments, teams, work locations, legal entities, org nodes, manager hierarchy, custom fields, and onboarding/offboarding workflows.

**Payroll** — Pay schedules, pay periods, payroll runs, paychecks, earning types, deductions, taxes, direct deposit, and bank accounts.

**Benefits** — Benefit plans, benefit enrollments, employee benefit records, and dependent coverage.

**Time Off** — Time-off types, leave policies, time-off requests, and balance tracking.

**IT and Device Management** — Managed devices, device applications, app access, app subscriptions, company apps, SSO providers, and identity providers.

**Identity and Access** — Roles, permissions, OAuth tokens, SCIM/WorkOS connections, and HRIS profile linking.

**Spend** — Expense reports, individual expenses, credit cards, and spend categories.

**Platform** — Webhooks, workflow events, integrations, org chart, and report definitions.

## Root Types

The schema exposes three root operation types:

- `Query` — read access across all domains
- `Mutation` — create, update, and delete operations
- `Subscription` — real-time events via webhook-backed subscriptions

## Key Design Decisions

**Employee as central node** — The `Employee` type is the hub of the graph. Payroll, benefits, time off, devices, and app access all relate back to an employee identifier.

**Org hierarchy via OrgNode** — The `OrgNode` type allows recursive traversal of the company's organizational tree independent of department or team groupings.

**Separation of plan vs enrollment** — `BenefitPlan` describes a plan offered by the company; `BenefitEnrollment` records an employee's election into a plan; `BenefitEmployee` joins an employee to a specific coverage tier and effective date.

**Device lifecycle** — `ManagedDevice` tracks hardware assignment, MDM enrollment status, and OS. `DeviceApplication` represents software installed on a managed device.

**Identity layering** — `SSOProvider`, `IdentityProvider`, and `WorkosConnection` represent the three layers of Rippling's identity stack: SSO configuration, upstream IdP federation, and the WorkOS-powered directory connection.

**Spend separation** — `ExpenseReport` groups one or more `Expense` items; `CreditCard` records corporate card assignment independent of the expense workflow.

## Usage Notes

- All IDs are opaque strings matching Rippling's internal identifiers.
- Timestamps follow ISO 8601 format and are represented as the `DateTime` scalar.
- Monetary amounts use the `Money` scalar (a string-encoded decimal with currency code).
- Pagination uses cursor-based connections following the Relay specification.
- Enum values mirror the string constants used in the Rippling REST API.

## References

- Developer Portal: https://developer.rippling.com/
- API Reference: https://developer.rippling.com/docs/rippling-api
- Webhooks Guide: https://developer.rippling.com/documentation/developer-portal/v2-guides/webhooks
- GitHub Organization: https://github.com/Rippling
- LLMs.txt: https://developer.rippling.com/llms.txt
