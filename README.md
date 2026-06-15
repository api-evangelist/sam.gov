# SAM.gov (sam.gov)

SAM.gov (System for Award Management) is the official US government system for vendor registration and federal procurement. Operated by the General Services Administration (GSA), SAM.gov consolidates multiple legacy acquisition systems and provides APIs for contract opportunities, entity management, federal hierarchy, and location validation services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sam.gov/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sam.gov/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** Public

## Tags

- Federal Government
- Procurement
- Contracts
- Entity Management
- Location Services
- GSA

## Timestamps

- **Created:** 2024-03-29
- **Modified:** 2026-05-19

## APIs

### SAM.gov Public Location Services API

The Public Location Services API provides Location Services data (Country, State, City, and ZIP) for validating location data submitted to SAM.gov. Location Services State API supports both United States and Foreign Countries. Requires a valid SAM.gov System Account API key.

- **Human URL:** [https://open.gsa.gov/api/location-public-api/](https://open.gsa.gov/api/location-public-api/)

#### Tags

- Location Services
- Validation
- Government
- GSA

#### Properties

- [Documentation](https://open.gsa.gov/api/location-public-api/)
- [OpenAPI](openapi/sam-gov-location-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sam-gov-location-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sam-gov-location-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAM.gov Get Opportunities Public API

The Get Opportunities Public API provides all published contract opportunity details based on request parameters. Returns solicitation notices, awards, and pre-solicitations from SAM.gov. Rate limited to 1000 requests/day. Requires a SAM.gov API key.

- **Human URL:** [https://open.gsa.gov/api/get-opportunities-public-api/](https://open.gsa.gov/api/get-opportunities-public-api/)

#### Tags

- Contract Opportunities
- Procurement
- Federal Contracts
- Government

#### Properties

- [Documentation](https://open.gsa.gov/api/get-opportunities-public-api/)
- [Base U R L](https://api.sam.gov/prod/opportunities/v2/search)
- [Postman Collection](collections/sam-gov-location-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sam-gov-location-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAM.gov Opportunity Management API

The Opportunity Management API allows authorized users to programmatically submit, update, and manage contract opportunity notices in SAM.gov. Requires federal government or contractor system account authorization.

- **Human URL:** [https://open.gsa.gov/api/opportunities-api/](https://open.gsa.gov/api/opportunities-api/)

#### Tags

- Contract Management
- Procurement
- Federal Contracts
- Government

#### Properties

- [Documentation](https://open.gsa.gov/api/opportunities-api/)
- [Postman Collection](collections/sam-gov-location-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sam-gov-location-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAM.gov Entity Management API

The Entity Management API provides detailed entity (vendor/contractor) information from SAM.gov including registration status, hierarchy, security levels, points of contact, and certifications. Used to verify vendors eligible for federal contracts.

- **Human URL:** [https://open.gsa.gov/api/entity-api/](https://open.gsa.gov/api/entity-api/)

#### Tags

- Entity Management
- Vendor Registration
- Federal Procurement
- Government

#### Properties

- [Documentation](https://open.gsa.gov/api/entity-api/)
- [Postman Collection](collections/sam-gov-location-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sam-gov-location-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAM.gov Federal Hierarchy Public API

The Federal Hierarchy Public API allows non-federal users to retrieve Federal Organization details down to the office level. Used to look up agency and organizational hierarchy for federal procurement purposes.

- **Human URL:** [https://open.gsa.gov/api/fh-public-api/](https://open.gsa.gov/api/fh-public-api/)

#### Tags

- Federal Hierarchy
- Government Organization
- Government

#### Properties

- [Documentation](https://open.gsa.gov/api/fh-public-api/)
- [Postman Collection](collections/sam-gov-location-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sam-gov-location-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAM.gov Contract Awards API

The Contract Awards API provides access to federal contract award information from SAM.gov, including award details, vendor information, award amounts, and performance period data.

- **Human URL:** [https://open.gsa.gov/api/contract-awards/](https://open.gsa.gov/api/contract-awards/)

#### Tags

- Contract Awards
- Federal Spending
- Procurement
- Government

#### Properties

- [Documentation](https://open.gsa.gov/api/contract-awards/)
- [Postman Collection](collections/sam-gov-location-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sam-gov-location-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://sam.gov)
- [Portal](https://open.gsa.gov/api/)
- [Documentation](https://open.gsa.gov/api/)
- [A P I Key](https://open.gsa.gov/api/get-opportunities-public-api/#getting-started)
- [Git Hub](https://github.com/GSA)
- [Data Catalog](https://catalog.data.gov)
- [Status Page](https://sam.gov/status)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
