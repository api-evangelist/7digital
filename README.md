# 7digital (7digital)

7digital (now operating as MassiveMusic following a corporate pivot toward Songtradr-affiliated business music services) is a B2B music platform that licenses a 100M+ track music catalogue and provides the streaming, download-delivery, royalty-reporting, and content-ingestion infrastructure that powers music services for fitness apps, social-media platforms, background-music providers, interactive-radio products, music stores, and subscription streaming services. The API surface is split into a classic REST API (v1.2) and a modern MassiveMusic Streaming Platform API, both signed with OAuth 1.0 and gated behind a commercial agreement.

**APIs.json:** [https://docs.massivemusic.com/reference](https://docs.massivemusic.com/reference)

## Tags

- Music
- Streaming
- Licensing
- Catalogue
- B2B
- Royalty Reporting
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-28

## APIs

### 7digital API

Classic 7digital REST API (v1.2). Covers catalogue browse / search / charts, artist / release / track lookup and recommendations, baskets, vouchers, purchase delivery, lockers, payment cards, editorial, translations, IP-to-country lookup, and user signup / authentication. OAuth 1.0 signed; partner consumer key required.

- **Human URL:** [https://docs.massivemusic.com/reference](https://docs.massivemusic.com/reference)
- **Base URL:** `https://api.7digital.com/1.2`

#### Tags

- Catalogue
- Search
- Commerce
- Payments
- Accounts

#### Properties

- [Documentation](https://docs.massivemusic.com/reference)
- [API Reference](https://docs.massivemusic.com/reference/about-this-api)
- [Authentication](https://docs.massivemusic.com/reference/authentication)
- [OpenAPI](openapi/7digital-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/7digital-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/7digital-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/)
- [J S O N- L D](json-ld/7digital-api-context.jsonld)
- [Example](examples/)
- [SDK](https://github.com/7digital/7digital-api)
- [SDK](https://github.com/7digital/python-7digital-api)
- [SDK](https://github.com/7digital/SevenDigital.Api.Wrapper)
- [SDK](https://github.com/7digital/SevenDigital.Api.Schema)
- [SDK](https://github.com/7digital/SevenDigital.Api.Client)
- [SDK](https://github.com/7digital/7digital-iOS-SDK)
- [SDK](https://github.com/7digital/7digital-Android-SDK)
- [Code Examples](https://github.com/7digital/7digital-API-walkthroughs)
- [Code Examples](https://github.com/7digital/7digital-feed-fetcher-example)
- [Code Examples](https://github.com/7digital/7digital_api_examples)

### MassiveMusic Streaming Platform API

Modern MassiveMusic Streaming Platform API. Covers catalogue with batch lookup, Interactive Radio (DMCA / GVL ruleset listening sessions), Logging (catalogue / preview / subscriber stream reporting required for licensor royalty), HLS and HTTP Progressive streaming (preview, catalogue, locker, subscriber, offline), Offline Device authorisation, Download Purchases (single + ZIP), Playlists, Sales (credit / refund / locker), Subscriptions, User Management, and Content Delivery / bulk media transfer. OAuth 1.0 signed; partner consumer key required.

- **Human URL:** [https://docs.massivemusic.com/reference](https://docs.massivemusic.com/reference)
- **Base URL:** `https://api.7digital.com`

#### Tags

- Streaming
- Interactive Radio
- Royalty Reporting
- Content Delivery
- Playlists
- Subscriptions

#### Properties

- [Documentation](https://docs.massivemusic.com/reference)
- [API Reference](https://docs.massivemusic.com/reference/introduction)
- [Authentication](https://docs.massivemusic.com/reference/authentication)
- [Rate Limits](https://docs.massivemusic.com/reference/usage-limits)
- [OpenAPI](openapi/7digital-streaming-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/7digital-streaming-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/7digital-streaming-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/)
- [J S O N- L D](json-ld/7digital-streaming-platform-context.jsonld)
- [Example](examples/)
- [Postman Collection](https://docs.massivemusic.com/docs/postman-sample-requests) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

## Common Properties

- [Website](https://uk.7digital.com)
- [Documentation](https://docs.massivemusic.com)
- [Getting Started](https://docs.massivemusic.com/docs/guides-introduction)
- [API Reference](https://docs.massivemusic.com/reference)
- [Changelog](https://docs.massivemusic.com/changelog)
- [F A Q](https://docs.massivemusic.com/docs/faq)
- [Support](https://docs.massivemusic.com/docs/support)
- [Status Page](https://docs.massivemusic.com/docs/health-dashboards)
- [Terms of Service](https://docs.massivemusic.com/docs/sla)
- [GitHub Organization](https://github.com/7digital)
- [GitHub Repository](https://github.com/7digital/7digital-api)
- [GitHub Repository](https://github.com/7digital/python-7digital-api)
- [GitHub Repository](https://github.com/7digital/SevenDigital.Api.Wrapper)
- [Postman Collection](https://www.postman.com/speeding-water-232919/7digital-client-test-suite/overview) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Spectral Rules](rules/7digital-rules.yml)
- [Vocabulary](vocabulary/7digital-vocabulary.yml)
- [Plans](plans/7digital-plans-pricing.yml)
- [Rate Limits](rate-limits/7digital-rate-limits.yml)
- [Fin Ops](finops/7digital-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
