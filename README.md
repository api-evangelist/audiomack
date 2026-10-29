# Audiomack

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

Audiomack is an on-demand music streaming and audio discovery platform that lets artists and creators upload unlimited music and podcasts and reach listeners through its iOS, Android, and web apps. The service is widely associated with hip-hop, rap, R&B, Afrobeats, dancehall, reggae, electronic, and Latin genres, and is a launchpad for independent and emerging artists worldwide, with particularly strong adoption across Africa, the Caribbean, and the U.S. Audiomack publishes a public Data API at https://api.audiomack.com/v1 that exposes the catalog (songs, albums, playlists), artist profiles and follower graph, search and autosuggest, charts by genre and timeframe, streaming URL issuance, favorites and reposts, ad and view/play stats reporting, and authenticated user resources. Authentication is OAuth 1.0a (three-legged), with an optional unauthenticated `key` parameter for read-only access on some endpoints. Audiomack also publishes a Creators portal, an Artist Guide, Audiomack Studios, and the AMP monetization program for artist payouts.

**Areas:** Music · Music Streaming · Audio · Podcasts · Hip-Hop · Rap · Afrobeats · Reggae · Dancehall · R&B · Electronic · Charts

## Audiomack on APIs.io

Everything profiled for Audiomack is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/audiomack/](https://apis.io/providers/audiomack/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Audiomack Artist API](https://apis.io/apis/audiomack/audiomack-artist-api/) — Artist profiles, uploads, favorites, followers, and pinned items.
- [Audiomack Chart API](https://apis.io/apis/audiomack/audiomack-chart-api/) — Aggregate song, album, and playlist charts across timeframes and genres.
- [Audiomack Music API](https://apis.io/apis/audiomack/audiomack-music-api/) — Songs, albums, streaming, favorites, reposts, and metrics.
- [Audiomack Playlist API](https://apis.io/apis/audiomack/audiomack-playlist-api/) — Playlist creation, editing, favoriting, and discovery.
- [Audiomack Search API](https://apis.io/apis/audiomack/audiomack-search-api/) — Free-text search and autosuggest across music, albums, and artists.
- [Audiomack Stats API](https://apis.io/apis/audiomack/audiomack-stats-api/) — Tokenised view and play event reporting.
- [Audiomack User API](https://apis.io/apis/audiomack/audiomack-user-api/) — Authenticated user profile, feed, uploads, playlists, and notifications.
- [Audiomack O Auth API](https://apis.io/apis/audiomack/audiomack-oauth-api/) — OAuth 1.0a request-token and access-token exchanges.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Audiomack Agentic Access](https://apis.io/agentic-access/audiomack/audiomack-agentic-access/)

#### Collections (9)

Postman and Open Collection request collections.

- [Audiomack Data Artist API](https://apis.io/collections/audiomack/open-audiomack-artist-api/)
- [Audiomack Data Artist Chart API](https://apis.io/collections/audiomack/open-audiomack-chart-api/)
- [Audiomack Data API](https://apis.io/collections/audiomack/open-audiomack-data-api/)
- [Audiomack Data Artist Music API](https://apis.io/collections/audiomack/open-audiomack-music-api/)
- [Audiomack Data Artist OAuth API](https://apis.io/collections/audiomack/open-audiomack-oauth-api/)
- [Audiomack Data Artist Playlist API](https://apis.io/collections/audiomack/open-audiomack-playlist-api/)
- [Audiomack Data Artist Search API](https://apis.io/collections/audiomack/open-audiomack-search-api/)
- [Audiomack Data Artist Stats API](https://apis.io/collections/audiomack/open-audiomack-stats-api/)
- [Audiomack Data Artist User API](https://apis.io/collections/audiomack/open-audiomack-user-api/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Audiomack Authentication](https://apis.io/security/audiomack/audiomack-authentication/)
- [Audiomack Domain Security](https://apis.io/security/audiomack/audiomack-domain-security/)
- [Audiomack Vulnerability Disclosure](https://apis.io/security/audiomack/audiomack-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://audiomack.com)
- [Documentation](https://www.audiomack.com/data-api/docs)
- [Getting started](https://www.audiomack.com/data-api/docs)
- [Support](https://audiomack.zendesk.com/)
- [Blog](https://audiomack.com/blog)
- [Terms of service](https://audiomack.com/about/terms-of-service)
- [Privacy policy](https://audiomack.com/about/privacy-policy)
- [GitHub](https://github.com/audiomack)

## API Evangelist rating

**Kin Score 31.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 50.5 |
| Contract governance | 0.0 |
| Operational transparency | 2.6 |
| Developer ergonomics | 50.0 |
| Access clarity | 13.2 |

**Agent readiness 18.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 17.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/audiomack/](https://apis.io/providers/audiomack/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Audiomack: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/audiomack/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
