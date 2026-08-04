# Paychex (paychex-developer)

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

Paychex, Inc. (NASDAQ: PAYX) is a Rochester, New York-based provider of integrated payroll, human resources, retirement, insurance, and benefits outsourcing services for small- and medium-sized businesses, with developer APIs exposed through the Paychex Flex platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/paychex-developer/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/paychex-developer/refs/heads/main/apis.yml)

## Scope

- **Access:** 3rd-Party

## Tags

- Benefits
- HCM
- HR
- Paychex Flex
- Payroll
- Time and Attendance
- Workforce

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Paychex Payroll Companies API

The Paychex Payroll Companies API exposes the list of payroll-bearing companies that a registered Paychex application has been granted access to, along with each company's configuration, pay components, deductions, earnings, and worksite data. It is the entry point to every other Paychex REST API — workers and time are scoped underneath a company resource.

- **Human URL:** [https://developer.paychex.com/](https://developer.paychex.com/)
- **Base URL:** `https://api.paychex.com`

#### Tags

- Companies
- Employer
- HCM
- Paychex Flex
- Payroll

#### Properties

- [Documentation](https://developer.paychex.com/documentation)
- [Getting Started](https://developer.paychex.com/getting-started/overview)
- [Authentication](https://developer.paychex.com/getting-started/overview)
- [OpenAPI](openapi/paychex-payroll-companies-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paychex-payroll-companies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paychex-payroll-companies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/paychex-companies-company-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/paychex-companies-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Paychex Workers API

The Paychex Workers API provides access to employee and contractor records inside a Paychex Flex company — including personal details, employment status, pay rates, work assignments, and lifecycle events such as hire and termination. Workers are addressed as a sub-resource of a company (`/companies/{companyId}/workers`).

- **Human URL:** [https://developer.paychex.com/](https://developer.paychex.com/)
- **Base URL:** `https://api.paychex.com`

#### Tags

- Employees
- HCM
- HR
- Paychex Flex
- Workers
- Workforce

#### Properties

- [Documentation](https://developer.paychex.com/documentation)
- [Getting Started](https://developer.paychex.com/getting-started/overview)
- [Authentication](https://developer.paychex.com/getting-started/overview)
- [OpenAPI](openapi/paychex-workers-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paychex-workers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paychex-workers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/paychex-workers-worker-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/paychex-workers-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Paychex Time API

The Paychex Time API enables third-party time and attendance systems to submit time entry, punch, and time-worked data for workers inside a Paychex Flex company so it can be consumed by Paychex Payroll. Operations are versioned under `/time/v1/` and are typically scoped per company and worker.

- **Human URL:** [https://developer.paychex.com/](https://developer.paychex.com/)
- **Base URL:** `https://api.paychex.com`

#### Tags

- Attendance
- Paychex Flex
- Payroll
- Time
- Time and Attendance
- Workforce Management

#### Properties

- [Documentation](https://developer.paychex.com/documentation)
- [Getting Started](https://developer.paychex.com/getting-started/overview)
- [Authentication](https://developer.paychex.com/getting-started/overview)
- [OpenAPI](openapi/paychex-time-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paychex-time.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paychex-time.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.paychex.com/)
- [Documentation](https://developer.paychex.com/documentation)
- [Getting Started](https://developer.paychex.com/getting-started/overview)
- [Authentication](https://developer.paychex.com/getting-started/overview)
- [GitHub Organization](https://github.com/paychex)
- [LinkedIn](https://www.linkedin.com/company/paychex)
- [X (Twitter)](https://x.com/Paychex)
- [Facebook](https://www.facebook.com/Paychex)
- [YouTube](https://www.youtube.com/user/PaychexInc)
- [Blog](https://www.paychex.com/articles)
- [Newsroom](https://www.paychex.com/newsroom)
- [Investor Relations](https://investor.paychex.com/)
- [Support Contact](https://developer.paychex.com/support)
- [OpenAPI](openapi/paychex-payroll-companies-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/paychex-workers-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/paychex-time-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/paychex-companies-company-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/paychex-workers-worker-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/paychex-developer-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Plans](plans/paychex-developer-plans-pricing.yml)
- [Rate Limits](rate-limits/paychex-developer-rate-limits.yml)
- [Fin Ops](finops/paychex-developer-finops.yml)
- [Vocabulary](vocabulary/paychex-developer-vocabulary.yml)
- [Spectral Rules](rules/paychex-developer-rules.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**Email:** kin@apievangelist.com
