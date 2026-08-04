# SAM.gov (sam.gov)

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
