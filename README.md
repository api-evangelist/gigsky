# GigSky (gigsky)

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

GigSky is a global eSIM and mobile-data roaming platform offering travel and enterprise/IoT cellular connectivity across 190+ destinations. For business, enterprise, and IoT customers it provides the GigSky Enterprise Manager (GEM) and IoT SIM Management portal with RESTful APIs for eSIM provisioning, plan/catalog and connectivity management, orders, and usage controls. The partner/reseller and enterprise API surface is account-gated rather than publicly documented.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gigsky/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gigsky/refs/heads/main/apis.yml)

## Tags

- eSIM
- Mobile Data
- Roaming
- Connectivity
- IoT
- Telecom

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## API Availability

GigSky's enterprise and IoT product pages confirm a "fully featured SIM Management portal, with RESTful APIs," but GigSky does **not** publish a public developer/API reference. No base URL, endpoint paths, request/response schemas, or authentication scheme are publicly documented as of the review date. API access is partner/enterprise-gated through the GigSky Enterprise Manager (gem.gigsky.com), the IoT SIM Deployment portal (iot.gigsky.com), and sales-led onboarding (business.gigsky.com). The artifacts in this repository document the API surface honestly based on public materials; endpoint, schema, and auth details are marked unverified and must be reconciled against partner documentation obtained directly from GigSky.

## APIs

### GigSky Plans & Catalog API

Programmatic access to GigSky's catalog of regional and global eSIM data plans by destination and price zone, used by partners and enterprises to browse and select connectivity. Endpoints, base URL, and authentication are partner/enterprise-gated and not publicly documented as of the review date; the base URL shown is illustrative and unverified.

- **Human URL:** [https://www.gigsky.com/enterprise-solutions](https://www.gigsky.com/enterprise-solutions)
- **Base URL:** `https://api.gigsky.com`

#### Tags

- Plans
- Catalog
- Data Plans
- Pricing

#### Properties

- [Documentation](https://www.gigsky.com/enterprise-solutions)
- [OpenAPI](openapi/gigsky-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gigsky.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gigsky.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GigSky eSIM Provisioning API

RESTful eSIM/SIM provisioning and lifecycle management through the GigSky Enterprise Manager (GEM) and IoT SIM Management portal - assigning and activating eSIM profiles, country-by-country connectivity control, per-SIM and per-user-group limits, sub-accounts, and Over-the-Air (OTA) network provisioning. The API is account-gated; endpoint and auth details are not publicly published.

- **Human URL:** [https://www.gigsky.com/iot-solutions](https://www.gigsky.com/iot-solutions)
- **Base URL:** `https://api.gigsky.com`

#### Tags

- eSIM
- Provisioning
- SIM Management
- OTA

#### Properties

- [Documentation](https://www.gigsky.com/iot-solutions)
- [OpenAPI](openapi/gigsky-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gigsky.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gigsky.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GigSky Orders API

Order placement and fulfillment for eSIM plans and SIM deployments by partners and enterprises, tied to GigSky's pay-as-you-go and pooled-data billing models. Order endpoints, base URL, and authentication are partner/enterprise-gated and not publicly documented.

- **Human URL:** [https://www.gigsky.com/enterprise-solutions](https://www.gigsky.com/enterprise-solutions)
- **Base URL:** `https://api.gigsky.com`

#### Tags

- Orders
- Activation
- Fulfillment

#### Properties

- [Documentation](https://www.gigsky.com/enterprise-solutions)
- [OpenAPI](openapi/gigsky-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gigsky.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gigsky.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GigSky Usage API

Reporting on data consumption and connectivity usage per SIM, user group, sub-account, or pooled plan, supporting GigSky's monthly statement and pay-as-you-go billing. Usage endpoints and authentication are account-gated and not publicly documented as of the review date.

- **Human URL:** [https://www.gigsky.com/enterprise-solutions](https://www.gigsky.com/enterprise-solutions)
- **Base URL:** `https://api.gigsky.com`

#### Tags

- Usage
- Reporting
- Data Consumption

#### Properties

- [Documentation](https://www.gigsky.com/enterprise-solutions)
- [OpenAPI](openapi/gigsky-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gigsky.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gigsky.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/gigsky)
- [Website](https://www.gigsky.com/)
- [Documentation](https://www.gigsky.com/enterprise-solutions)
- [Plans](plans/gigsky-plans-pricing.yml)
- [Rate Limits](rate-limits/gigsky-rate-limits.yml)
- [Fin Ops](finops/gigsky-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
