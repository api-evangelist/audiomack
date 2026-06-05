# Audiomack (audiomack)

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
