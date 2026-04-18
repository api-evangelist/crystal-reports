# Crystal Reports (crystal-reports)
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
