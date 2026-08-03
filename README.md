# Audiomack (audiomack)

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

Audiomack is an on-demand music streaming and audio discovery platform that lets artists and creators upload unlimited music and podcasts and reach listeners through its iOS, Android, and web apps. The service is widely associated with hip-hop, rap, R&B, Afrobeats, dancehall, reggae, electronic, and Latin genres, and is a launchpad for independent and emerging artists worldwide, with particularly strong adoption across Africa, the Caribbean, and the U.S. Audiomack publishes a public Data API at https://api.audiomack.com/v1 that exposes the catalog (songs, albums, playlists), artist profiles and follower graph, search and autosuggest, charts by genre and timeframe, streaming URL issuance, favorites and reposts, ad and view/play stats reporting, and authenticated user resources. Authentication is OAuth 1.0a (three-legged), with an optional unauthenticated `key` parameter for read-only access on some endpoints. Audiomack also publishes a Creators portal, an Artist Guide, Audiomack Studios, and the AMP monetization program for artist payouts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/audiomack/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/audiomack/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Music
- Music Streaming
- Audio
- Podcasts
- Hip-Hop
- Rap
- Afrobeats
- Reggae
- Dancehall
- R&B
- Electronic
- Charts
- Playlists
- Discovery
- Creator Economy
- Independent Artists

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Audiomack Data API

The Audiomack Data API provides programmatic access to Audiomack's music catalog and social graph: songs, albums, artists, playlists, charts by genre and timeframe (daily/weekly/monthly/yearly/total), full-text search and autosuggest, streaming URL issuance (short-lived, ~10 second TTL), favorites, reposts, follows, ad and view/play stats reporting, and the authenticated user's feed, uploads, playlists, favorites, and notifications. Requests are signed with OAuth 1.0a; access tokens are valid for one year. List endpoints support page-based pagination, the `fields` parameter for sparse fieldsets, and a configurable `limit`.

- **Human URL:** [https://www.audiomack.com/data-api/docs](https://www.audiomack.com/data-api/docs)
- **Base URL:** `https://api.audiomack.com/v1`

#### Tags

- Music
- Streaming
- Catalog
- Artists
- Playlists
- Charts
- Search
- OAuth 1.0a

#### Properties

- [Documentation](https://www.audiomack.com/data-api/docs)
- [OpenAPI](openapi/audiomack-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/audiomack-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/audiomack-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Code Examples](https://github.com/audiomack/audiomack-api-examples)
- [Authentication](https://www.audiomack.com/data-api/docs)

## Common Properties

- [Website](https://audiomack.com)
- [Portal](https://creators.audiomack.com)
- [Documentation](https://www.audiomack.com/data-api/docs)
- [Getting Started](https://www.audiomack.com/data-api/docs)
- [Code Examples](https://github.com/audiomack/audiomack-api-examples)
- [GitHub Organization](https://github.com/audiomack)
- [Support](https://audiomack.zendesk.com/)
- [Contact](https://creators.audiomack.com/contact-us)
- [Documentation](https://creators.audiomack.com/about/legal)
- [Terms of Service](https://audiomack.com/about/terms-of-service)
- [Privacy Policy](https://audiomack.com/about/privacy-policy)
- [Responsible Disclosure](https://creators.audiomack.com/responsible-disclosure)
- [Documentation](https://guide.audiomack.com)
- [Documentation](https://styleguide.audiomack.com)
- [Product](https://audiomack.studio)
- [Sign Up](https://audiomack.com/login)
- [Twitter](https://twitter.com/audiomack)
- [LinkedIn](https://www.linkedin.com/company/audiomack)
- [Facebook](https://www.facebook.com/audiomack)
- [Instagram](https://www.instagram.com/audiomack)
- [YouTube](https://www.youtube.com/audiomack)
- [Tik Tok](https://www.tiktok.com/@audiomack)
- [Twitch](https://www.twitch.tv/audiomack)
- [Apps](https://apps.apple.com/us/app/audiomack-music-downloader/id669528610)
- [Apps](https://play.google.com/store/apps/details?id=com.audiomack)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
