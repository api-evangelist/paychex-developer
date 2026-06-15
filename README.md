# Paychex (paychex-developer)

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
