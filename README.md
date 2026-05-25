# Cloudbeds (cloudbeds)

Cloudbeds is a San Diego-based hospitality management platform for small and mid-size independent hotels, hostels, and groups, offering PMS, channel manager, booking engine, payments, and a marketplace of integrations. Cloudbeds publishes a public REST API (v1.2 and v1.3), a GraphQL API, blueprints, and webhooks for reservations, guests, rooms, rates, payments, and events.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cloudbeds/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- Hospitality, Hotels, PMS, Property Management, Channel Manager, Booking Engine, Payments

## APIs
- **Cloudbeds REST API v1.3** — current REST API at `https://hotels.cloudbeds.com/api/v1.3`. Reservations, guests, rooms, rate plans, payments, webhooks, dashboard. Docs: https://developers.cloudbeds.com/reference
- **Cloudbeds REST API v1.2** — legacy version still supported for backwards compatibility.
- **Cloudbeds GraphQL API** — typed query interface alongside REST.
- **Cloudbeds Webhooks** — reservation, guest, room, and payment events.

## Artifacts
- **OpenAPI** — [openapi/cloudbeds-openapi.yml](openapi/cloudbeds-openapi.yml) — v1.3 surface generated from the developer documentation.
- **Naftiko Capabilities** — [capabilities/](capabilities/) — reservations, guests, rooms and rates, payments, webhooks.
- **JSON Schemas** — [json-schema/](json-schema/) — Reservation, Guest, Rate Plan.
- **JSON Structure** — [json-structure/](json-structure/) — Reservation, Guest.
- **JSON-LD Context** — [json-ld/cloudbeds-context.jsonld](json-ld/cloudbeds-context.jsonld) — schema.org/LodgingReservation alignment.
- **Examples** — [examples/](examples/) — reservation, guest, rate plan.
- **Spectral Rules** — [rules/cloudbeds-rules.yml](rules/cloudbeds-rules.yml) — auth, rate limits, destructive-action confirmation, PCI handling.
- **Vocabulary** — [vocabulary/cloudbeds-vocabulary.yml](vocabulary/cloudbeds-vocabulary.yml) — hospitality, distribution, reservations, payments, integration terms.

## Commercial Surface
- **Plans** — [plans/cloudbeds-plans-pricing.yml](plans/cloudbeds-plans-pricing.yml) — tiered property SaaS (Foundation/Essentials/Plus/Premier) plus payment processing; free Marketplace developer registration.
- **RateLimits** — [rate-limits/cloudbeds-rate-limits.yml](rate-limits/cloudbeds-rate-limits.yml) — 429 responses; specific thresholds not publicly documented.
- **FinOps** — [finops/cloudbeds-finops.yml](finops/cloudbeds-finops.yml) — FOCUS-aligned hybrid (SaaS plus payments volume).

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-24

## Common Properties
- [Website](https://www.cloudbeds.com/)
- [Developer Portal](https://developers.cloudbeds.com/)
- [GitHub Organization](https://github.com/cloudbeds)
- [LinkedIn](https://www.linkedin.com/company/cloudbeds)
- [Integrations](https://www.cloudbeds.com/integrations/)
- [llms.txt](https://developers.cloudbeds.com/llms.txt)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
