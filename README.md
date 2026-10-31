# ScalpStream

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

ScalpStream operates a family of machine-payable data APIs built for autonomous agents: RecallScout (active US FDA, NHTSA and CPSC recalls with severity normalised across the three regulators), AirScout (global air quality with an EPA-based outdoor-exertion verdict and the cleanest window ahead), BorderScout (all 85 US ports of entry ranked by drive-plus-wait time per lane), FuelScout (cheapest fuel - station-level for Spain, France and Italy, official regional averages for the US) and ScalpStream Research (impersonal ranked options, dividend, crypto and yield feeds). Every service is a plain HTTPS GET priced at a flat $0.01 per request and settled per request over x402 (HTTP 402) in USDC on Base, Arbitrum or Polygon or XRP/RLUSD on the XRP Ledger - no accounts, no API keys, no subscriptions - with a free preview on every host, an A2A agent card and JSON-RPC endpoint per service, and a first-party local MCP server (scalpmcp) that buys from all of them with the user's own wallet.

**Areas:** Company · Agents · A2A · x402 · Micropayments · MCP · Open Data · Product Recalls · Air Quality · Border Crossings · Fuel Prices · Market Research

## ScalpStream on APIs.io

Everything profiled for ScalpStream is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/scalpstream-com/](https://apis.io/providers/scalpstream-com/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [RecallScout](https://apis.io/apis/scalpstream-com/recallscout/) — Machine-payable US recall lookups over x402. Given a product, brand, ingredient or vehicle (make/model/year), returns active recalls across FDA…
- [AirScout](https://apis.io/apis/scalpstream-com/airscout/) — Machine-payable air-quality queries over x402 with global coverage: current US AQI and pollutant breakdown for a lat/lon, an EPA (AirNow) based verdict on…
- [BorderScout](https://apis.io/apis/scalpstream-com/borderscout/) — Machine-payable US border-crossing queries over x402. Ranks all 85 US ports of entry by all-in time - the drive there plus the live CBP wait once there -…
- [FuelScout](https://apis.io/apis/scalpstream-com/fuelscout/) — Machine-payable cheapest-fuel queries over x402. Station-level prices for Spain, France and Italy and official regional averages for the US, by location and…
- [ScalpStream Research](https://apis.io/apis/scalpstream-com/scalpstream-research/) — Machine-payable, impersonal research feeds over x402: ranked 0-30 DTE options candidates (/picks), dividend and tax-free municipal income (/dividends),…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [scalpstream](https://apis.io/servers/scalpstream-com/scalpstream/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Scalpstream Com Research](https://apis.io/schemas/scalpstream-com/scalpstream-com-research/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Scalpstream Com Authentication](https://apis.io/security/scalpstream-com/scalpstream-com-authentication/)
- [Scalpstream Com Domain Security](https://apis.io/security/scalpstream-com/scalpstream-com-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Scalpstream Com Plans Pricing](https://apis.io/plans/scalpstream-com/scalpstream-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Scalpstream Com Rate Limits](https://apis.io/rate-limits/scalpstream-com/scalpstream-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://scalpstream.com/)
- [Documentation](https://recallscout.scalpstream.com/.well-known/x402)
- [Getting started](https://www.scalpstream.com/#Products)
- [Pricing](https://www.scalpstream.com/)
- [Blog](https://www.scalpstream.com/blog)
- [GitHub](https://github.com/DV1-321)

## API Evangelist rating

**Kin Score 25.2** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 76.7 |
| Contract quality | 12.0 |
| Contract governance | 18.2 |
| Operational transparency | 18.4 |
| Developer ergonomics | 36.9 |
| Access clarity | 10.5 |

**Agent readiness 17.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/scalpstream-com/](https://apis.io/providers/scalpstream-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for ScalpStream: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/scalpstream-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
