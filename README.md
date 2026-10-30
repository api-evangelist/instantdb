# InstantDB

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

InstantDB (Instant) is a realtime client-side database and Firebase alternative that gives apps a sync engine with multiplayer, offline mode, and optimistic updates by default. It exposes an HTTP Admin API (api.instantdb.com) for server-side InstaQL queries and InstaML transactions, plus auth, storage, presence, and a realtime WebSocket sync layer.

**Areas:** Database · Real-Time · Sync · Backend · Local-First

## InstantDB on APIs.io

Everything profiled for InstantDB is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/instantdb/](https://apis.io/providers/instantdb/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [InstantDB Realtime Sync API](https://apis.io/apis/instantdb/instantdb-realtime-sync-api/) — The realtime sync transport - a persistent WebSocket at wss://api.instantdb.com/runtime/session over which the client Reactor sends init, add-query,…
- [InstantDB Auth API](https://apis.io/apis/instantdb/instantdb-auth-api/) — Server-side authentication, tokens, and users.
- [InstantDB Presence API](https://apis.io/apis/instantdb/instantdb-presence-api/) — Room presence lookups.
- [InstantDB Query API](https://apis.io/apis/instantdb/instantdb-query-api/) — InstaQL read queries.
- [InstantDB Storage API](https://apis.io/apis/instantdb/instantdb-storage-api/) — File upload, listing, and deletion.
- [InstantDB Transactions API](https://apis.io/apis/instantdb/instantdb-transactions-api/) — InstaML transaction writes.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [InstantDB Realtime Sync (WebSocket)](https://apis.io/asyncapis/instantdb/instantdb-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/runtime/session](https://apis.io/channels/instantdb/runtime-session/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [instantdb](https://apis.io/servers/instantdb/instantdb/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Instantdb Agentic Access](https://apis.io/agentic-access/instantdb/instantdb-agentic-access/)

#### Collections (6)

Postman and Open Collection request collections.

- [InstantDB Admin HTTP API](https://apis.io/collections/instantdb/open-instantdb/)
- [InstantDB Admin HTTP Auth API](https://apis.io/collections/instantdb/open-instantdb-auth-api/)
- [InstantDB Admin HTTP Auth Presence API](https://apis.io/collections/instantdb/open-instantdb-presence-api/)
- [InstantDB Admin HTTP Auth Query API](https://apis.io/collections/instantdb/open-instantdb-query-api/)
- [InstantDB Admin HTTP Auth Storage API](https://apis.io/collections/instantdb/open-instantdb-storage-api/)
- [InstantDB Admin HTTP Auth Transactions API](https://apis.io/collections/instantdb/open-instantdb-transactions-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [InstantDB — asyncapi rules](https://apis.io/rules/instantdb/instantdb-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Instantdb Authentication](https://apis.io/security/instantdb/instantdb-authentication/)
- [Instantdb Domain Security](https://apis.io/security/instantdb/instantdb-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Instantdb Plans Pricing](https://apis.io/plans/instantdb/instantdb-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Instantdb Rate Limits](https://apis.io/rate-limits/instantdb/instantdb-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Instantdb Finops](https://apis.io/finops/instantdb/instantdb-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.instantdb.com)
- [Documentation](https://www.instantdb.com/docs)
- [Blog](https://www.instantdb.com/rss.xml)
- [GitHub](https://github.com/instantdb)

## API Evangelist rating

**Kin Score 31.1** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 58.0 |
| Contract governance | 13.6 |
| Operational transparency | 10.5 |
| Developer ergonomics | 32.1 |
| Access clarity | 7.9 |

**Agent readiness 47.4** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/instantdb/](https://apis.io/providers/instantdb/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for InstantDB: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/instantdb/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
