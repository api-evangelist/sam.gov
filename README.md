# SAM.gov

SAM.gov (System for Award Management) is the official US government system for vendor registration and federal procurement, operated by the General Services Administration (GSA). SAM.gov consolidates multiple legacy acquisition systems and provides APIs for contract opportunities, entity management, federal hierarchy, and location validation services.

## APIs

| API | Description |
|---|---|
| [Location Services API](https://open.gsa.gov/api/location-public-api/) | Validate city, state, and ZIP code data for SAM.gov submissions |
| [Get Opportunities Public API](https://open.gsa.gov/api/get-opportunities-public-api/) | Retrieve published federal contract opportunities |
| [Opportunity Management API](https://open.gsa.gov/api/opportunities-api/) | Submit and manage contract opportunity notices |
| [Entity Management API](https://open.gsa.gov/api/entity-api/) | Query vendor/contractor registration data |
| [Federal Hierarchy Public API](https://open.gsa.gov/api/fh-public-api/) | Retrieve federal organizational hierarchy |
| [Contract Awards API](https://open.gsa.gov/api/contract-awards/) | Access federal contract award data |

## Resources

- **SAM.gov Portal**: [sam.gov](https://sam.gov)
- **GSA Open Technology**: [open.gsa.gov/api](https://open.gsa.gov/api/)
- **API Key Registration**: [GSA Developer Portal](https://open.gsa.gov/api/get-opportunities-public-api/#getting-started)
- **GitHub (GSA)**: [github.com/GSA](https://github.com/GSA)
- **Data Catalog**: [catalog.data.gov](https://catalog.data.gov)

## Artifacts

### OpenAPI Specs
- [sam-gov-location-services-openapi.yml](openapi/sam-gov-location-services-openapi.yml) — Location Services API (cities, states, ZIP validation)

### Spectral Rules
- [sam-gov-rules.yml](rules/sam-gov-rules.yml) — API style and compliance rules

### Capabilities
- [federal-procurement.yaml](capabilities/federal-procurement.yaml) — Location validation for vendor registration
- [shared/sam-gov-location-services.yaml](capabilities/shared/sam-gov-location-services.yaml) — Location Services API consumed definition

### JSON Schema
- [sam-gov-city-schema.json](json-schema/sam-gov-city-schema.json) — City entity schema
- [sam-gov-opportunity-schema.json](json-schema/sam-gov-opportunity-schema.json) — Federal contract opportunity schema

### JSON Structure
- [sam-gov-city-structure.json](json-structure/sam-gov-city-structure.json) — City structure documentation
- [sam-gov-opportunity-structure.json](json-structure/sam-gov-opportunity-structure.json) — Opportunity structure documentation

### JSON-LD
- [sam-gov-context.jsonld](json-ld/sam-gov-context.jsonld) — Linked data context for federal procurement entities

### Examples
- [sam-gov-get-cities-example.json](examples/sam-gov-get-cities-example.json) — Get cities request/response
- [sam-gov-validate-zip-example.json](examples/sam-gov-validate-zip-example.json) — Validate ZIP code request/response

### Vocabulary
- [sam-gov-vocabulary.yml](vocabulary/sam-gov-vocabulary.yml) — Federal procurement terminology

## Maintained By

[Kin Lane](mailto:kin@apievangelist.com) — [API Evangelist](https://apievangelist.com)
