# Crystal Reports (crystal-reports)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

SAP Crystal Reports is a business intelligence application for designing and generating formatted reports from various data sources including SQL databases, spreadsheets, and XML.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/crystal-reports/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Business Intelligence, Data Visualization, Reporting, SAP

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-17

## APIs

3 APIs: Crystal Reports REST API, Crystal Reports SDK, Crystal Reports Server REST API.

## Features

| Name | Description |
|------|-------------|
| Report Generation | Generate formatted reports from databases, spreadsheets, and XML. |
| Report Viewing | Embed report viewers in web and desktop applications. |
| Report Scheduling | Schedule automated report generation and delivery. |
| Parameter Prompts | Pass dynamic parameters to filter report content. |
| Export Formats | Export to PDF, Excel, Word, CSV, XML, and other formats. |
| Sub-Reports | Embed linked sub-reports for drill-down capabilities. |
| Cross-Tab Reports | Generate pivot-table style cross-tabulation reports. |
| Charting | Create charts and graphs within reports. |
| Data Source Connectivity | Connect to SQL Server, Oracle, SAP HANA, ODBC, JDBC. |
| Report Server Management | Manage server instances, folders, users, and security. |

## Use Cases

| Name | Description |
|------|-------------|
| Financial Reporting | Financial statements, balance sheets, and P&L reports. |
| Operational Dashboards | Operational reports for manufacturing and logistics. |
| Compliance Reports | Regulatory compliance reports for auditing. |
| Customer Invoicing | Formatted invoices and statements from billing data. |
| HR Analytics | Employee reports, headcount, and compensation summaries. |
| Embedded Reporting | Embed Crystal Reports viewer in custom applications. |

## Solutions

| Name | Description |
|------|-------------|
| SAP Crystal Reports | Desktop report designer for creating templates. |
| SAP Crystal Reports Server | Server platform for scheduling and distributing reports. |
| SAP BusinessObjects BI | Enterprise BI platform with Crystal Reports integration. |

## Artifacts

### OpenAPI

- [Crystal Reports REST API](openapi/crystal-reports-rest-api.yaml) — 24 operations, 25 schemas (generated from official SAP PDF documentation)

### JSON Schema

23 standalone JSON Schema files in [json-schema/](json-schema/).

### JSON Structure

23 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [Crystal Reports Context](json-ld/crystal-reports-context.jsonld) — 23 types, 54 properties

### Examples

23 example JSON files in [examples/](examples/).

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Reporting Services](capabilities/shared/reporting.yaml) — 12 operations covering authentication, repository, reports, metadata, instances, export, and OData

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Report Management](capabilities/report-management.yaml) | All reporting services | 11 | Report Developer / BI Analyst |

## Vocabulary

- [Crystal Reports Vocabulary](vocabulary/crystal-reports-vocabulary.yaml) — 7 resources, 3 APIs, 3 domains, 4 personas

## Rules

- [Crystal Reports Spectral Rules](rules/crystal-reports-spectral-rules.yml) — 16 rules

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
