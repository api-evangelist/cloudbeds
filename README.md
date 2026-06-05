# Cloudbeds (cloudbeds)

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
