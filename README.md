# 7digital / MassiveMusic (7digital)

7digital (now operating as MassiveMusic following a corporate pivot toward Songtradr-affiliated business music services) is a B2B music platform that licenses a 100M+ track music catalogue and provides the streaming, download-delivery, royalty-reporting, and content-ingestion infrastructure that powers music services for fitness apps, social-media platforms, background-music providers, interactive-radio products, music stores, and subscription streaming services. The API surface is split into a classic REST API (v1.2) and a modern MassiveMusic Streaming Platform API, both signed with OAuth 1.0 and gated behind a commercial agreement.

**URL:** [Visit APIs.json URL](https://docs.massivemusic.com/reference)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Music, Streaming, Licensing, Catalogue, B2B, Royalty Reporting, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-28

## APIs

### 7digital API

Classic 7digital REST API (v1.2). Covers catalogue browse / search / charts, artist / release / track lookup and recommendations, baskets, vouchers, purchase delivery, lockers, payment cards, editorial, translations, IP-to-country lookup, and user signup / authentication. OAuth 1.0 signed; partner consumer key required.

**Human URL:** [https://docs.massivemusic.com/reference](https://docs.massivemusic.com/reference)

**Base URL:** `https://api.7digital.com/1.2`

#### Tags

 - Catalogue, Search, Commerce, Payments, Accounts

#### Properties

- [Documentation](https://docs.massivemusic.com/reference)
- [APIReference](https://docs.massivemusic.com/reference/about-this-api)
- [Authentication](https://docs.massivemusic.com/reference/authentication)
- [OpenAPI](openapi/7digital-api-openapi.yml)
- [NaftikoCapability — Releases](capabilities/api-releases.yaml)
- [NaftikoCapability — Artists](capabilities/api-artists.yaml)
- [NaftikoCapability — Tracks](capabilities/api-tracks.yaml)
- [NaftikoCapability — Tags](capabilities/api-tags.yaml)
- [NaftikoCapability — Basket](capabilities/api-basket.yaml)
- [NaftikoCapability — User](capabilities/api-user.yaml)
- [NaftikoCapability — Users](capabilities/api-users.yaml)
- [NaftikoCapability — Territories](capabilities/api-territories.yaml)
- [NaftikoCapability — Translations](capabilities/api-translations.yaml)
- [NaftikoCapability — IP Lookup](capabilities/api-iplookup.yaml)
- [NaftikoCapability — Editorial](capabilities/api-editorial.yaml)
- [NaftikoCapability — Catalogue](capabilities/api-catalogue.yaml)
- [NaftikoCapability — Payment](capabilities/api-payment.yaml)
- [JSONSchema](json-schema/)
- [JSONStructure](json-structure/)
- [JSON-LD](json-ld/7digital-api-context.jsonld)
- [Example](examples/)
- [SDK — Node.js](https://github.com/7digital/7digital-api)
- [SDK — Python](https://github.com/7digital/python-7digital-api)
- [SDK — .NET (C#) Wrapper](https://github.com/7digital/SevenDigital.Api.Wrapper)
- [SDK — .NET (C#) Schema](https://github.com/7digital/SevenDigital.Api.Schema)
- [SDK — Java Client (Scala)](https://github.com/7digital/SevenDigital.Api.Client)
- [SDK — iOS (archived)](https://github.com/7digital/7digital-iOS-SDK)
- [SDK — Android (archived)](https://github.com/7digital/7digital-Android-SDK)
- [CodeExamples — API Walkthroughs](https://github.com/7digital/7digital-API-walkthroughs)
- [CodeExamples — Catalogue Feed Fetcher (Ruby)](https://github.com/7digital/7digital-feed-fetcher-example)
- [CodeExamples — Ruby API Examples (archived)](https://github.com/7digital/7digital_api_examples)

### MassiveMusic Streaming Platform API

Modern MassiveMusic Streaming Platform API. Covers catalogue with batch lookup, Interactive Radio (DMCA / GVL ruleset listening sessions), Logging (catalogue / preview / subscriber stream reporting required for licensor royalty), HLS and HTTP Progressive streaming (preview, catalogue, locker, subscriber, offline), Offline Device authorisation, Download Purchases (single + ZIP), Playlists, Sales (credit / refund / locker), Subscriptions, User Management, and Content Delivery / bulk media transfer. OAuth 1.0 signed; partner consumer key required.

**Human URL:** [https://docs.massivemusic.com/reference](https://docs.massivemusic.com/reference)

**Base URL:** `https://api.7digital.com`

#### Tags

 - Streaming, Interactive Radio, Royalty Reporting, Content Delivery, Playlists, Subscriptions

#### Properties

- [Documentation](https://docs.massivemusic.com/reference)
- [APIReference](https://docs.massivemusic.com/reference/introduction)
- [Authentication](https://docs.massivemusic.com/reference/authentication)
- [RateLimits](https://docs.massivemusic.com/reference/usage-limits)
- [OpenAPI](openapi/7digital-streaming-platform-openapi.yml)
- [NaftikoCapability — Catalogue](capabilities/streaming-platform-catalogue.yaml)
- [NaftikoCapability — Interactive Radio](capabilities/streaming-platform-interactive-radio.yaml)
- [NaftikoCapability — Logging](capabilities/streaming-platform-logging.yaml)
- [NaftikoCapability — Streaming](capabilities/streaming-platform-streaming.yaml)
- [NaftikoCapability — Offline Devices](capabilities/streaming-platform-offline-devices.yaml)
- [NaftikoCapability — Download Purchases](capabilities/streaming-platform-download-purchases.yaml)
- [NaftikoCapability — Playlists](capabilities/streaming-platform-playlists.yaml)
- [NaftikoCapability — Sales](capabilities/streaming-platform-sales.yaml)
- [NaftikoCapability — Subscriptions](capabilities/streaming-platform-subscriptions.yaml)
- [NaftikoCapability — User Management](capabilities/streaming-platform-user-management.yaml)
- [NaftikoCapability — Content Delivery](capabilities/streaming-platform-content-delivery.yaml)
- [JSONSchema](json-schema/)
- [JSONStructure](json-structure/)
- [JSON-LD](json-ld/7digital-streaming-platform-context.jsonld)
- [Example](examples/)
- [PostmanCollection](https://docs.massivemusic.com/docs/postman-sample-requests)

## Common Properties

- [Website](https://uk.7digital.com)
- [Documentation](https://docs.massivemusic.com)
- [GettingStarted](https://docs.massivemusic.com/docs/guides-introduction)
- [APIReference](https://docs.massivemusic.com/reference)
- [ChangeLog](https://docs.massivemusic.com/changelog)
- [FAQ](https://docs.massivemusic.com/docs/faq)
- [Support](https://docs.massivemusic.com/docs/support)
- [StatusPage](https://docs.massivemusic.com/docs/health-dashboards)
- [TermsOfService](https://docs.massivemusic.com/docs/sla)
- [GitHubOrganization](https://github.com/7digital)
- [PostmanCollection](https://www.postman.com/speeding-water-232919/7digital-client-test-suite/overview)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [SpectralRules](rules/7digital-rules.yml)
- [Vocabulary](vocabulary/7digital-vocabulary.yml)
- [Plans](plans/7digital-plans-pricing.yml)
- [RateLimits](rate-limits/7digital-rate-limits.yml)
- [FinOps](finops/7digital-finops.yml)

## Features

| Name | Description |
|------|-------------|
| 100M+ Track Licensed Catalogue | Direct licences with major and independent labels. Standard + Enhanced metadata. Pre-cleared Songtradr catalogue for synced uses. |
| Catalogue Search + Browse | Free-text search across artists, releases, and tracks; popularity-weighted ranking; alphabetical browse; batch lookup of releases / tracks in a single request. |
| HLS and HTTP Progressive Streaming | Preview clips, catalogue streaming, locker streaming, subscription streaming (online + offline), in HLS or HTTP Progressive variants. |
| Interactive Radio | DMCA and GVL-compliant lean-back radio sessions. Skip-budget and ruleset enforcement on every Get-Next-Track call. Playback events influence subsequent track selection. |
| Subscription Streaming with Device Concurrency | Subscriber playback gated on a valid subscription record; clientId parameter enforces single-device concurrency. |
| Offline Mode for Subscriptions | Per-device offline authorisation, encrypted on-device caching, deferred play-event reporting when connectivity is restored. |
| Royalty + Usage Reporting | Three logging endpoints (catalogue / preview / subscriber) plus S3-bucket bulk loggers feed Client Usage Reports and Label Reports. |
| Sales Credit + Refund Tracking | Log sales in the originating currency, attach purchased content to the user locker, and remove refunds from the sales report. |
| Content Delivery (DDEX + SFTP + Media Transfer) | DDEX ERN message ingestion via SFTP and bulk media transfer for downloading an entire licensed catalogue at 50 req/sec. |
| Playlist Management API | Partner-scoped playlists with optional user association, public / private visibility, descriptions, and per-track source / audioUrl metadata. |
| User Account + Authentication | OAuth 1.0 user accounts with signup, authenticate, and details endpoints. 2-legged (partner) and 3-legged (user-context) flows. |
| Multi-Territory + Multi-Currency | ISO 3166-1 alpha-2 territory codes, IP-to-country resolution for geo-restriction, per-territory pricing in local currency. |
| Compliance Testing | Pre-launch Compliance Testing with Client Success validates that stream logs are correctly attributed to the right usage type before royalty reporting goes live. |

## Use Cases

| Name | Description |
|------|-------------|
| Music Streaming Service | Build a full subscription streaming service on top of licensed catalogue + HLS streaming + subscriber logging. |
| Fitness App with Curated Music | Stream catalogue tracks to workout sessions, report plays for licensor royalty. |
| Social Media Music | Either MassiveMusic-managed content delivery or self-managed delivery for short-form video music. |
| Background Music Service | Lean-back music for retail, hospitality, or workplace using catalogue + ruleset-compliant playback. |
| Interactive Radio Product | Launch a DMCA / GVL-compliant lean-back radio station with skip budgets and playback-event-driven track selection. |
| Digital Music Storefront | Sell tracks and releases via basket + payment-card + PayPal flows; deliver downloads from the user locker. |
| White-Label Subscription Service | Operate a fully white-labelled subscription music service with offline mode and per-territory licensing. |
| Content Delivery / Aggregator | Ingest catalogue via DDEX + SFTP and bulk-download licensed media for upstream distribution. |

## Integrations

| Name | Description |
|------|-------------|
| Warner Music Group | Documented integration steps for Warner Music Group catalogue + reporting. |
| Universal Music Group | Security due diligence + integration steps for Universal Music Group. |
| DDEX | ERN 3.8 message components for catalogue ingestion via SFTP. |
| PayPal | PayPal Express Checkout integration for basket purchase completion. |
| AWS S3 | S3-bucket bulk loggers for stream / preview / subscription logs and bulk batch submission. |
| Songtradr | Access to the Songtradr pre-cleared catalogue (the represented catalogue) via the same API surface. |
| Postman | Public Postman workspace with example requests covering authentication and core operations. |

## Solutions

| Name | Description |
|------|-------------|
| Background Music Service | End-to-end recipe for a lean-back retail / hospitality music product. |
| Content Delivery Service | End-to-end recipe for a catalogue ingestion + delivery pipeline. |
| Download Service | End-to-end recipe for a track / release download storefront. |
| Fitness Service | End-to-end recipe for a fitness app with curated music streams. |
| Interactive Radio Streaming Service | End-to-end recipe for a DMCA / GVL-compliant radio station. |
| Social Media Service (Managed) | End-to-end recipe for short-form music with MassiveMusic-managed content delivery. |
| Social Media Service (Self-Managed) | End-to-end recipe for short-form music with partner-managed content delivery. |
| Streaming Service | End-to-end recipe for a non-subscription catalogue streaming service. |
| Subscription Streaming Service | End-to-end recipe for a subscription-based streaming service with offline mode. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [7digital API (v1.2) — openapi/7digital-api-openapi.yml](openapi/7digital-api-openapi.yml) — 61 operations across 13 tags
- [MassiveMusic Streaming Platform API — openapi/7digital-streaming-platform-openapi.yml](openapi/7digital-streaming-platform-openapi.yml) — 46 operations across 11 tags

### JSON Schema

64 standalone JSON Schema (draft 2020-12) files in [`json-schema/`](json-schema/) — one per OpenAPI `components/schemas` entry across both specs.

### JSON Structure

64 JSON Structure (json-structure.org) files in [`json-structure/`](json-structure/) — converted 1:1 from the JSON Schema set.

### JSON-LD

- [json-ld/7digital-api-context.jsonld](json-ld/7digital-api-context.jsonld) — JSON-LD 1.1 context for the classic API entities, with schema.org alignments for name, description, url, image, releaseDate, duration, etc.
- [json-ld/7digital-streaming-platform-context.jsonld](json-ld/7digital-streaming-platform-context.jsonld) — JSON-LD 1.1 context for the Streaming Platform entities.

### Examples

64 realistic JSON example payloads in [`examples/`](examples/) — deterministically generated, one per JSON Schema.

## Capabilities

Naftiko capabilities are organised one file per OpenAPI tag, each self-contained with an HTTP `consumes` block, a REST exposer, and an MCP exposer.

### 7digital API (v1.2) capabilities

| Capability | Operations |
|---|---|
| [Releases](capabilities/api-releases.yaml) | 11 |
| [Artists](capabilities/api-artists.yaml) | 10 |
| [Tracks](capabilities/api-tracks.yaml) | 4 |
| [Tags](capabilities/api-tags.yaml) | 1 |
| [Basket](capabilities/api-basket.yaml) | 8 |
| [User](capabilities/api-user.yaml) | 18 |
| [Users](capabilities/api-users.yaml) | 2 |
| [Territories](capabilities/api-territories.yaml) | 1 |
| [Translations](capabilities/api-translations.yaml) | 1 |
| [IP Lookup](capabilities/api-iplookup.yaml) | 1 |
| [Editorial](capabilities/api-editorial.yaml) | 1 |
| [Catalogue](capabilities/api-catalogue.yaml) | 2 |
| [Payment](capabilities/api-payment.yaml) | 2 |

### MassiveMusic Streaming Platform API capabilities

| Capability | Operations |
|---|---|
| [Catalogue](capabilities/streaming-platform-catalogue.yaml) | 13 |
| [Interactive Radio](capabilities/streaming-platform-interactive-radio.yaml) | 4 |
| [Logging](capabilities/streaming-platform-logging.yaml) | 3 |
| [Streaming](capabilities/streaming-platform-streaming.yaml) | 9 |
| [Offline Devices](capabilities/streaming-platform-offline-devices.yaml) | 3 |
| [Download Purchases](capabilities/streaming-platform-download-purchases.yaml) | 3 |
| [Playlists](capabilities/streaming-platform-playlists.yaml) | 4 |
| [Sales](capabilities/streaming-platform-sales.yaml) | 4 |
| [Subscriptions](capabilities/streaming-platform-subscriptions.yaml) | 1 |
| [User Management](capabilities/streaming-platform-user-management.yaml) | 1 |
| [Content Delivery](capabilities/streaming-platform-content-delivery.yaml) | 1 |

## Vocabulary

- [7digital Vocabulary](vocabulary/7digital-vocabulary.yml) — Unified taxonomy mapping 22 resources, 15 actions, 7 workflows, and 9 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [7digital Spectral Ruleset](rules/7digital-rules.yml) — 36 rules across 13 sections (info, openapi version, servers, paths, operations, tags, parameters, request bodies, responses, schemas, security, HTTP method conventions, general quality) enforcing 7digital / MassiveMusic API conventions including the "7digital " summary prefix, camelCase paths + parameters + operationIds, OAuth 1.0 security, and Microcks mock-server compatibility.

## Plans + Rate Limits + FinOps

- [Plans](plans/7digital-plans-pricing.yml) — Single enterprise / contact-sales plan covering all product lines (catalogue, streaming, downloads, content delivery) with metered entries for royalty pass-through.
- [Rate Limits](rate-limits/7digital-rate-limits.yml) — Non-live keys throttled at ~4,000 req/day; endpoint-specific acceptable-usage budgets (preview-log 5 req/sec, media-transfer 50 req/sec); subscription-streaming clientId concurrency control.
- [FinOps](finops/7digital-finops.yml) — FOCUS 1.3-aligned billing surface; 8 meters covering streams, downloads, transfers, API requests, and the platform integration fee; four FinOps principles tailored to royalty-pass-through music platforms.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
