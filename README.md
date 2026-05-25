# Paychex (paychex-developer)

Paychex, Inc. (NASDAQ: PAYX) is a Rochester, New York-based provider of integrated payroll, human resources, retirement, insurance, and benefits outsourcing services for small- and medium-sized businesses, with developer APIs exposed through the Paychex Flex platform.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/paychex-developer/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Benefits, HCM, HR, Paychex Flex, Payroll, Time and Attendance, Workforce

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Paychex Payroll Companies API
The Paychex Payroll Companies API exposes the list of payroll-bearing companies that a registered Paychex application has been granted access to, along with each company's configuration. Companies are the root tenant resource for all other Paychex REST APIs — workers and time are nested underneath a company.

**Human URL:** [https://developer.paychex.com/](https://developer.paychex.com/)

**Base URL:** `https://api.paychex.com`

#### Tags

 - Companies, Employer, HCM, Paychex Flex, Payroll

#### Properties

- [Documentation](https://developer.paychex.com/documentation)
- [GettingStarted](https://developer.paychex.com/getting-started/overview)
- [Authentication](https://developer.paychex.com/getting-started/overview)
- [OpenAPI](openapi/paychex-payroll-companies-openapi.yml)
- [JSONSchema](json-schema/paychex-companies-company-schema.json)
- [JSONLD](json-ld/paychex-companies-context.jsonld)
- [NaftikoCapability](capabilities/paychex-companies.yaml)

### Paychex Workers API
The Paychex Workers API provides access to employees and contractors inside a Paychex Flex company. Workers are nested under the company resource and expose personal data, employment status, pay rates, and work assignments.

**Human URL:** [https://developer.paychex.com/](https://developer.paychex.com/)

**Base URL:** `https://api.paychex.com`

#### Tags

 - Employees, HCM, HR, Paychex Flex, Workers, Workforce

#### Properties

- [Documentation](https://developer.paychex.com/documentation)
- [GettingStarted](https://developer.paychex.com/getting-started/overview)
- [Authentication](https://developer.paychex.com/getting-started/overview)
- [OpenAPI](openapi/paychex-workers-openapi.yml)
- [JSONSchema](json-schema/paychex-workers-worker-schema.json)
- [JSONLD](json-ld/paychex-workers-context.jsonld)
- [NaftikoCapability](capabilities/paychex-workers.yaml)

### Paychex Time API
The Paychex Time API enables third-party time and attendance vendors to submit time entries, punches, and time-worked totals for workers inside a Paychex Flex company so they flow into Paychex Payroll processing.

**Human URL:** [https://developer.paychex.com/](https://developer.paychex.com/)

**Base URL:** `https://api.paychex.com`

#### Tags

 - Attendance, Paychex Flex, Payroll, Time, Time and Attendance, Workforce Management

#### Properties

- [Documentation](https://developer.paychex.com/documentation)
- [GettingStarted](https://developer.paychex.com/getting-started/overview)
- [Authentication](https://developer.paychex.com/getting-started/overview)
- [OpenAPI](openapi/paychex-time-openapi.yml)
- [NaftikoCapability](capabilities/paychex-time.yaml)

## Common Properties

- [Portal](https://developer.paychex.com/)
- [Documentation](https://developer.paychex.com/documentation)
- [GettingStarted](https://developer.paychex.com/getting-started/overview)
- [Authentication](https://developer.paychex.com/getting-started/overview)
- [GitHubOrganization](https://github.com/paychex)
- [LinkedIn](https://www.linkedin.com/company/paychex)
- [X](https://x.com/Paychex)
- [Facebook](https://www.facebook.com/Paychex)
- [YouTube](https://www.youtube.com/user/PaychexInc)
- [Blog](https://www.paychex.com/articles)
- [Newsroom](https://www.paychex.com/newsroom)
- [InvestorRelations](https://investor.paychex.com/)
- [SupportContact](https://developer.paychex.com/support)

## Features

| Name | Description |
|------|-------------|
| Company-Scoped Access | Every API call is scoped to a company resource that the registered application has been granted explicit access to, enforcing tenant isolation across Paychex Flex clients. |
| Worker Lifecycle Management | List, retrieve, and update worker records — including personal information, work assignments, and pay rates — for hire-to-retire HR workflows. |
| Time Data Ingest | Submit time entries, punches, and time-worked records from third-party time and attendance systems so they flow into Paychex Payroll processing. |
| OAuth 2.0 Client Credentials | All APIs are protected by an OAuth 2.0 client_credentials flow tied to a registered Paychex partner or client application; there is no end-user OAuth dance. |
| Partner-Approved Integrations | Production access is gated behind partner registration and Paychex approval; sandbox credentials are issued during integration review rather than via self-serve signup. |
| Paychex Flex Native | APIs read and write against the same Paychex Flex platform used by ~800,000 payroll clients, so changes flow through the same payroll, HR, and benefits engines. |

## Use Cases

| Name | Description |
|------|-------------|
| HRIS and Payroll Sync | Keep an external HRIS or workforce-management system in sync with Paychex Flex by listing companies, mirroring workers, and reconciling pay and assignment changes. |
| Time and Attendance Integration | Push punches, time entries, and time-worked totals from third-party time tracking tools into Paychex Payroll so labor data drives paychecks automatically. |
| Onboarding Automation | Trigger downstream onboarding workflows — provisioning, benefits, equipment — when a new worker is created or activated in Paychex Flex. |
| Embedded Payroll for Partners | ISVs and vertical SaaS platforms surface Paychex payroll inside their own product, using the developer APIs to read companies and workers and feed payroll inputs. |
| Analytics and Workforce Reporting | Pull worker, company, and time data into BI and people-analytics stacks for headcount, labor cost, and compliance reporting. |

## Integrations

| Name | Description |
|------|-------------|
| Paychex Flex | Native integration with Paychex Flex — the cloud HR, payroll, time, and benefits platform that the developer APIs sit on top of. |
| Paychex Time | Native time and attendance product whose data model is exposed (and writable) via the Paychex Time API. |
| Paychex HR PEO | Professional Employer Organization (PEO) co-employment services that share the same underlying worker and company records exposed via the developer APIs. |
| Paychex Marketplace | Partner marketplace where vetted ISVs publish integrations built on the Paychex developer APIs. |
| Paycor (Acquired 2025) | Paychex completed its $4.1B acquisition of Paycor in 2025, expanding the HCM surface area covered by the broader Paychex platform. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Paychex Payroll Companies API](openapi/paychex-payroll-companies-openapi.yml)
- [Paychex Workers API](openapi/paychex-workers-openapi.yml)
- [Paychex Time API](openapi/paychex-time-openapi.yml)

### JSON Schema

- [Paychex Company](json-schema/paychex-companies-company-schema.json)
- [Paychex Worker](json-schema/paychex-workers-worker-schema.json)
- [Paychex Time Entry](json-schema/paychex-time-timeentry-schema.json)

### JSON Structure

- [Paychex Company Structure](json-structure/paychex-companies-company-structure.json)
- [Paychex Worker Structure](json-structure/paychex-workers-worker-structure.json)

### JSON-LD

- [Paychex Context](json-ld/paychex-developer-context.jsonld)
- [Paychex Companies Context](json-ld/paychex-companies-context.jsonld)
- [Paychex Workers Context](json-ld/paychex-workers-context.jsonld)

### Naftiko Capabilities

- [Paychex Companies Capability](capabilities/paychex-companies.yaml)
- [Paychex Workers Capability](capabilities/paychex-workers.yaml)
- [Paychex Time Capability](capabilities/paychex-time.yaml)

### Examples

- [List Companies](examples/paychex-companies-listcompanies-example.json)
- [Get Company](examples/paychex-companies-getcompany-example.json)
- [List Company Workers](examples/paychex-workers-listcompanyworkers-example.json)
- [Get Company Worker](examples/paychex-workers-getcompanyworker-example.json)
- [Submit Time Entries (Request)](examples/paychex-time-createtimeentries-request-example.json)
- [Submit Time Entries (Response)](examples/paychex-time-createtimeentries-response-example.json)

### Plans and Commercial

- [Plans and Pricing](plans/paychex-developer-plans-pricing.yml)
- [Rate Limits](rate-limits/paychex-developer-rate-limits.yml)
- [FinOps Profile](finops/paychex-developer-finops.yml)

### Vocabulary and Rules

- [Vocabulary](vocabulary/paychex-developer-vocabulary.yml)
- [Spectral Rules](rules/paychex-developer-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
