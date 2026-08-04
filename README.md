# Cloudbeds (cloudbeds)

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

Cloudbeds is a San Diego-based hospitality management platform for small and mid-size independent hotels, hostels, and groups, offering PMS, channel manager, booking engine, payments, and a marketplace of integrations. Cloudbeds publishes a public REST API (v1.2 and v1.3), a GraphQL API, blueprints, and webhooks for reservations, guests, rooms, rates, payments, and events.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cloudbeds/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cloudbeds/refs/heads/main/apis.yml)

## Tags

- Hospitality
- Hotels
- PMS
- Property Management
- Channel Manager
- Booking Engine
- Payments

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-24

## APIs

### Cloudbeds REST API v1.3

REST API exposing reservations, guests, rooms, rate plans, payments, webhooks, dashboard, and reporting for properties using Cloudbeds. v1.3 is the latest documented version.

- **Human URL:** [https://developers.cloudbeds.com/reference](https://developers.cloudbeds.com/reference)
- **Base URL:** `https://hotels.cloudbeds.com/api/v1.3`

#### Tags

- REST
- PMS
- v1.3

#### Properties

- [Documentation](https://developers.cloudbeds.com/reference)
- [OpenAPI](openapi/cloudbeds-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloudbeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudbeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/cloudbeds-rules.yml)
- [JSON Schema](json-schema/cloudbeds-reservation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloudbeds-guest-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cloudbeds-rate-plan-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/cloudbeds-reservation-structure.json)
- [JSON Structure](json-structure/cloudbeds-guest-structure.json)
- [JSON-LD](json-ld/cloudbeds-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/cloudbeds-reservation-example.json)
- [Example](examples/cloudbeds-guest-example.json)
- [Example](examples/cloudbeds-rate-plan-example.json)
- [Vocabulary](vocabulary/cloudbeds-vocabulary.yml)

### Cloudbeds REST API v1.2 (Legacy)

Earlier supported version of the Cloudbeds REST API. New integrations should target v1.3.

- **Human URL:** [https://developers.cloudbeds.com/reference](https://developers.cloudbeds.com/reference)
- **Base URL:** `https://hotels.cloudbeds.com/api/v1.2`

#### Tags

- REST
- PMS
- Legacy

#### Properties

- [Documentation](https://developers.cloudbeds.com/reference)
- [Postman Collection](collections/cloudbeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudbeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudbeds GraphQL API

GraphQL API offering a typed query interface for reservations, properties, and inventory alongside the REST API.

- **Human URL:** [https://developers.cloudbeds.com/reference](https://developers.cloudbeds.com/reference)

#### Tags

- GraphQL

#### Properties

- [Documentation](https://developers.cloudbeds.com/reference)
- [Postman Collection](collections/cloudbeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudbeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudbeds Webhooks

Event-driven webhooks for reservation, guest, room, and payment state changes. Use webhooks instead of polling list endpoints.

- **Human URL:** [https://developers.cloudbeds.com/reference](https://developers.cloudbeds.com/reference)

#### Tags

- Webhooks
- Events

#### Properties

- [Documentation](https://developers.cloudbeds.com/reference)
- [Postman Collection](collections/cloudbeds.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudbeds.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/cloudbeds)
- [LinkedIn](https://www.linkedin.com/company/cloudbeds)
- [Website](https://www.cloudbeds.com/)
- [Developer](https://developers.cloudbeds.com/)
- [Plans](plans/cloudbeds-plans-pricing.yml)
- [Rate Limits](rate-limits/cloudbeds-rate-limits.yml)
- [Fin Ops](finops/cloudbeds-finops.yml)
- [Integrations](https://www.cloudbeds.com/integrations/)
- [L L Ms Txt](https://developers.cloudbeds.com/llms.txt)
- [Spectral Rules](rules/cloudbeds-rules.yml)
- [Vocabulary](vocabulary/cloudbeds-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
