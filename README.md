# InstantDB (instantdb)

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

InstantDB (Instant) is a realtime client-side database and Firebase alternative that gives apps a sync engine with multiplayer, offline mode, and optimistic updates by default. It exposes an HTTP Admin API (api.instantdb.com) for server-side InstaQL queries and InstaML transactions, plus auth, storage, presence, and a realtime WebSocket sync layer.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/instantdb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/instantdb/refs/heads/main/apis.yml)

## Tags

- Database
- Realtime
- Sync
- Backend
- Local First

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### InstantDB Admin HTTP API

Server-side HTTP Admin API at api.instantdb.com, authenticated with a Bearer admin token and an App-Id header, that bypasses permissions to run InstaQL queries, InstaML transactions, auth, storage, and presence operations.

- **Human URL:** [https://www.instantdb.com/docs/http-api](https://www.instantdb.com/docs/http-api)
- **Base URL:** `https://api.instantdb.com`

#### Tags

- Admin
- HTTP
- Backend

#### Properties

- [Documentation](https://www.instantdb.com/docs/http-api)
- [API Reference](https://www.instantdb.com/docs/http-api)
- [OpenAPI](openapi/instantdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/instantdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instantdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### InstantDB Query (InstaQL) API

Reads data with InstaQL, Instant's relational GraphQL-like query language, via POST /admin/query — returning nested entities in a single round trip with optional rule parameters.

- **Human URL:** [https://www.instantdb.com/docs/instaql](https://www.instantdb.com/docs/instaql)
- **Base URL:** `https://api.instantdb.com`

#### Tags

- Query
- InstaQL
- Read

#### Properties

- [Documentation](https://www.instantdb.com/docs/instaql)
- [API Reference](https://www.instantdb.com/docs/http-api)
- [OpenAPI](openapi/instantdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/instantdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instantdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### InstantDB Transactions (InstaML) API

Writes, updates, links, and deletes data with InstaML transaction steps via POST /admin/transact, applied atomically as an admin that bypasses permission rules.

- **Human URL:** [https://www.instantdb.com/docs/instaml](https://www.instantdb.com/docs/instaml)
- **Base URL:** `https://api.instantdb.com`

#### Tags

- Transactions
- InstaML
- Write

#### Properties

- [Documentation](https://www.instantdb.com/docs/instaml)
- [API Reference](https://www.instantdb.com/docs/http-api)
- [OpenAPI](openapi/instantdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/instantdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instantdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### InstantDB Auth API

Server-side auth — mint refresh tokens, create/send/verify magic codes, look up and delete users, and sign users out — over /admin/refresh_tokens, /admin/magic_code, /admin/users, and related endpoints.

- **Human URL:** [https://www.instantdb.com/docs/auth](https://www.instantdb.com/docs/auth)
- **Base URL:** `https://api.instantdb.com`

#### Tags

- Auth
- Tokens
- Magic Code

#### Properties

- [Documentation](https://www.instantdb.com/docs/auth)
- [API Reference](https://www.instantdb.com/docs/http-api)
- [OpenAPI](openapi/instantdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/instantdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instantdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### InstantDB Storage API

Uploads, lists, and deletes files in Instant's object storage via PUT /admin/storage/upload, the $files query namespace, and the storage delete endpoints, with files surfaced as first-class entities.

- **Human URL:** [https://www.instantdb.com/docs/storage](https://www.instantdb.com/docs/storage)
- **Base URL:** `https://api.instantdb.com`

#### Tags

- Storage
- Files
- Uploads

#### Properties

- [Documentation](https://www.instantdb.com/docs/storage)
- [API Reference](https://www.instantdb.com/docs/http-api)
- [OpenAPI](openapi/instantdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/instantdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instantdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### InstantDB Realtime Sync API

The realtime sync transport — a persistent WebSocket at wss://api.instantdb.com/runtime/session over which the client Reactor sends init, add-query, transact, and presence ops and the server streams query novelty (refresh-ok), presence, and broadcasts back to subscribers.

- **Human URL:** [https://www.instantdb.com/essays/architecture](https://www.instantdb.com/essays/architecture)
- **Base URL:** `wss://api.instantdb.com/runtime/session`

#### Tags

- Realtime
- WebSocket
- Sync
- Presence

#### Properties

- [Documentation](https://www.instantdb.com/essays/architecture)
- [API Reference](https://www.instantdb.com/docs/presence-and-topics)
- [AsyncAPI](asyncapi/instantdb-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [GitHub Organization](https://github.com/instantdb)
- [LinkedIn](https://www.linkedin.com/company/instantdb)
- [Website](https://www.instantdb.com)
- [Documentation](https://www.instantdb.com/docs)
- [Plans](plans/instantdb-plans-pricing.yml)
- [Rate Limits](rate-limits/instantdb-rate-limits.yml)
- [Fin Ops](finops/instantdb-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
