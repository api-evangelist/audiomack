# Audiomack

Audiomack is an on-demand music streaming and audio discovery platform that lets artists and creators upload unlimited music and podcasts and reach listeners through its iOS, Android, and web apps. The service is widely associated with hip-hop, rap, R&B, Afrobeats, dancehall, reggae, electronic, and Latin music, with particularly strong adoption across Africa, the Caribbean, and the United States.

This repository is part of the [API Evangelist](https://apievangelist.com) network and profiles Audiomack's public APIs, developer surface, and supporting resources using the [APIs.json](https://apisjson.org) format.

## APIs

### Audiomack Data API

The [Audiomack Data API](https://www.audiomack.com/data-api/docs) is a public REST API at `https://api.audiomack.com/v1` that exposes Audiomack's catalog and social graph:

- Songs, albums, artists, and playlists
- Charts by genre and timeframe (daily, weekly, monthly, yearly, total)
- Full-text search and autosuggest across music, albums, and artists
- Short-lived streaming URL issuance (~10 second TTL) via `/music/{id}/play`
- Favorites, reposts, follows, and pinned items
- View and play stats reporting via tokenised stats events
- Authenticated user resources: profile, feed, uploads, playlists, favorites, notifications

Authentication uses the three-legged OAuth 1.0a flow:

1. `POST /v1/request_token` with an `oauth_callback`
2. Redirect the user to `https://audiomack.com/oauth/authenticate?oauth_token={token}`
3. `POST /v1/access_token` to exchange the authorised request token for a one-year access token

Some read endpoints accept an unauthenticated `key` query parameter.

OpenAPI: [`openapi/audiomack-data-api-openapi.yml`](openapi/audiomack-data-api-openapi.yml).

## Developer resources

- Data API docs: <https://www.audiomack.com/data-api/docs>
- API code examples (PHP): <https://github.com/audiomack/audiomack-api-examples>
- GitHub organization: <https://github.com/audiomack>
- Audiomack for Creators portal: <https://creators.audiomack.com>
- Artist Guide: <https://guide.audiomack.com>
- Style Guide: <https://styleguide.audiomack.com>
- Help Center: <https://audiomack.zendesk.com>
- Responsible disclosure: <https://creators.audiomack.com/responsible-disclosure>

## Apps and products

- iOS app: <https://apps.apple.com/us/app/audiomack-music-downloader/id669528610>
- Android app: <https://play.google.com/store/apps/details?id=com.audiomack>
- Audiomack Studios: <https://audiomack.studio>
- AMP (Audiomack Monetization Program): rolling out for eligible artists

## Files in this repository

- [`apis.yml`](apis.yml) — APIs.json profile for Audiomack
- [`openapi/audiomack-data-api-openapi.yml`](openapi/audiomack-data-api-openapi.yml) — OpenAPI 3.0 description of the Audiomack Data API
- [`README.md`](README.md) — This file
