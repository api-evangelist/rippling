# Rippling (rippling)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Rippling is a unified workforce platform spanning HR, IT, and Finance with programmable APIs for employees, payroll, devices, apps, time tracking, benefits, expenses, and SCIM identity provisioning.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rippling/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rippling/refs/heads/main/apis.yml)

## Tags

- HR
- HCM
- Payroll
- IT
- Identity
- SCIM
- Devices
- Spend Management

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-30

## APIs

### Rippling Platform API

The Rippling Platform API exposes core HRIS resources — companies, employees, departments, work locations, custom fields, employment types, and compensation history — for partners building HR-data integrations.

#### Tags

- Platform
- HRIS
- Workforce

#### Properties

- [Documentation](https://developer.rippling.com/)
- [API Reference](https://developer.rippling.com/docs/rippling-api)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Employees API

Read and write employee records — personal information, employment details, manager hierarchy, work email, work location, and custom employee fields — for active and terminated workers.

#### Tags

- Employees
- Workers
- Profiles

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Companies API

Retrieve company-level metadata, legal entities, business addresses, and account-wide configuration scoped to the authenticated tenant.

#### Tags

- Companies
- Tenants

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Departments API

List and manage departments and the hierarchical org structure used to group employees and route approvals.

#### Tags

- Departments
- Org Structure

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Teams API

Manage cross-functional teams that group employees independently of the department hierarchy.

#### Tags

- Teams
- Org Structure

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Work Locations API

Read and manage company work locations including office addresses and remote-work designations referenced by employee records.

#### Tags

- Locations
- Offices

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Payroll API

Push earnings, deductions, and reimbursements into Rippling Payroll for off-cycle and on-cycle pay runs, and read pay-history events.

#### Tags

- Payroll
- Earnings
- Deductions

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Time Off API

Submit and manage time-off requests, leave balances, and policies for vacation, sick leave, and other absence categories.

#### Tags

- Time Off
- Leave
- PTO

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Time Tracking API

Capture clock-in / clock-out events, hourly timesheets, breaks, and shift schedules for hourly and shift-based workers.

#### Tags

- Time Tracking
- Timesheets
- Shifts

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Benefits API

Retrieve employee benefits enrollments, dependents, and plan details across health, dental, vision, and other insurance lines.

#### Tags

- Benefits
- Insurance

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Expenses API

Submit and approve employee expense reports, attach receipts, and reimburse approved expenses through Rippling Spend.

#### Tags

- Expenses
- Reimbursements
- Spend

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Corporate Cards API

Issue, manage, and reconcile corporate cards, spend limits, and transactions for Rippling Spend customers.

#### Tags

- Cards
- Spend
- Bill Pay

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Bill Pay API

Manage vendor invoices, approvals, and payments through Rippling Bill Pay for accounts-payable workflows.

#### Tags

- Bill Pay
- AP
- Invoices

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Recruiting API

Sync candidates, applications, and offers between external ATS platforms and Rippling's recruiting and onboarding flows.

#### Tags

- Recruiting
- ATS
- Candidates

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Onboarding API

Trigger new-hire onboarding, capture personal details, distribute offer letters and policy documents, and provision day-one access.

#### Tags

- Onboarding
- Hires

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Devices API

Manage company-owned devices, MDM enrollment, ownership assignment, and lifecycle status across macOS, Windows, iOS, and Android.

#### Tags

- Devices
- MDM
- IT

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Apps API

Manage SaaS app provisioning, role assignment, and de-provisioning across the Rippling Apps catalog for IT teams.

#### Tags

- Apps
- SaaS Management
- Provisioning

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling SCIM API

SCIM 2.0 endpoints for inbound user, group, and role provisioning from identity providers (Okta, Azure AD, Google) and outbound to partner SaaS applications.

#### Tags

- SCIM
- Identity
- Provisioning

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling SSO API

Configure SAML/OIDC single sign-on between Rippling as an IdP and external service providers, plus SP integrations into Rippling.

#### Tags

- SSO
- Identity
- SAML

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Custom Fields API

Define and read custom fields attached to employees, departments, and other Rippling resources for tenant-specific metadata.

#### Tags

- Custom Fields
- Metadata

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rippling Webhooks API

Subscribe to Rippling events (employee created/updated/terminated, time-off approved, payroll finalized, device assigned) for near real-time downstream integration.

#### Tags

- Webhooks
- Events

#### Properties

- [Documentation](https://developer.rippling.com/)
- [Webhooks](https://developer.rippling.com/documentation/developer-portal/v2-guides/webhooks)
- [Webhooks](https://developer.rippling.com/documentation/rippling-platform/developer/webhooks)
- [AsyncAPI](asyncapi/rippling-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/rippling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rippling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rippling)
- [Website](https://www.rippling.com/)
- [Documentation](https://developer.rippling.com/)
- [API Reference](https://developer.rippling.com/docs/rippling-api)
- [Pricing](https://www.rippling.com/pricing)
- [Login](https://app.rippling.com/login)
- [Status Page](https://status.rippling.com/)
- [Blog](https://www.rippling.com/blog)
- [Support](https://support.rippling.com/)
- [GitHub Organization](https://github.com/Rippling)
- [Privacy Policy](https://www.rippling.com/privacy)
- [Terms of Service](https://www.rippling.com/terms)
- [Plans](plans/rippling-plans-pricing.yml)
- [Rate Limits](rate-limits/rippling-rate-limits.yml)
- [Fin Ops](finops/rippling-finops.yml)
- [Features](undefined)
- [Integrations](https://www.rippling.com/platform/integrations)
- [L L Ms Txt](https://developer.rippling.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
