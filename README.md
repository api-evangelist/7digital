# 7digital (7digital)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
