# First Citizens BancShares

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

First Citizens BancShares is a super-regional financial holding company (parent of First-Citizens Bank & Trust) providing general banking, trust, investment, insurance, and asset-management services to individuals, businesses, and professionals. Its programmable surface runs through Silicon Valley Bank (SVB) — acquired in 2023 and now a division of First Citizens — whose Apigee-backed developer portal at developer.svb.com publishes a family of commercial banking REST APIs covering authorization, account balance, transfers, ACH, instant payments, wires, stop payment, virtual cards, webhooks, and reference/reachability. Access is partner-gated (commercial onboarding); consumer account data is reachable via the Plaid aggregator.

**Areas:** Banking · Financial Services · Commercial Banking · Payments · ACH · Wire Transfers · Virtual Cards · Open Banking · Trust · Investment · Insurance · United States

## First Citizens BancShares on APIs.io

Everything profiled for First Citizens BancShares is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/first-citizens-bancshares/](https://apis.io/providers/first-citizens-bancshares/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [SVB Authorization API](https://apis.io/apis/first-citizens-bancshares/svb-authorization-api/) — The Authorization API issues OAuth2 access tokens for the SVB commercial banking platform (now part of First Citizens). Partners exchange client credentials…
- [SVB Account Balance API](https://apis.io/apis/first-citizens-bancshares/svb-account-balance-api/) — The Account Balance API returns current and available balance information for SVB commercial deposit accounts. Clients query /v1/accounts/balances to…
- [SVB Account Transfer API](https://apis.io/apis/first-citizens-bancshares/svb-account-transfer-api/) — The Account Transfer API moves funds between a client's own SVB accounts. Partners create transfers at /v1/payment/account-transfers and retrieve transfer…
- [SVB ACH Transfers API](https://apis.io/apis/first-citizens-bancshares/svb-ach-transfers-api/) — The ACH Transfers API (v2.1) originates domestic ACH credits and debits, verified ACH transfers, and IAT (International ACH Transaction) domestic entries.…
- [SVB Instant Payments API](https://apis.io/apis/first-citizens-bancshares/svb-instant-payments-api/) — The Instant Payments API sends and tracks real-time payments over U.S. instant rails. Partners create payments at /v1/payment/instant-payments and retrieve…
- [SVB Wires API](https://apis.io/apis/first-citizens-bancshares/svb-wires-api/) — The Wires API (v2.1) initiates and manages domestic and international wire transfers. Partners create wires at /v2/payment/wires, retrieve wire status by…
- [SVB Stop Payment API](https://apis.io/apis/first-citizens-bancshares/svb-stop-payment-api/) — The Stop Payment API places and inspects stop-payment orders on checks drawn against SVB commercial accounts. Partners create stop requests at…
- [SVB Virtual Cards API](https://apis.io/apis/first-citizens-bancshares/svb-virtual-cards-api/) — The Virtual Cards API (v2.0) issues and manages virtual card numbers (VCN) for accounts-payable, procurement, and travel spend. It exposes…
- [SVB Webhook API](https://apis.io/apis/first-citizens-bancshares/svb-webhook-api/) — The Webhook API (v2.0) delivers asynchronous event notifications for payment and account activity. Partners manage event-types, events, publishers, and…
- [SVB Reference API](https://apis.io/apis/first-citizens-bancshares/svb-reference-api/) — The Reference API provides look-up and reachability data supporting the payment products. It exposes…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [First Citizens Bancshares Webhooks](https://apis.io/asyncapis/first-citizens-bancshares/first-citizens-bancshares-webhooks/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [First Citizens Bancshares Authentication](https://apis.io/security/first-citizens-bancshares/first-citizens-bancshares-authentication/)
- [First Citizens Bancshares Domain Security](https://apis.io/security/first-citizens-bancshares/first-citizens-bancshares-domain-security/)
- [First Citizens Bancshares Vulnerability Disclosure](https://apis.io/security/first-citizens-bancshares/first-citizens-bancshares-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.firstcitizens.com)
- [Documentation](https://developer.svb.com/apis/docs-home)
- [Support](https://developer.svb.com/contact)
- [Blog](https://www.firstcitizens.com/wealth/insights)
- [Security](https://firstcitizensbank.responsibledisclosure.com)
- [Terms of service](https://www.firstcitizens.com/terms-of-use)
- [Privacy policy](https://www.firstcitizens.com/privacy)
- [GitHub](https://github.com/svb)

## API Evangelist rating

**Kin Score 33.6** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 39.0 |
| Contract governance | 4.5 |
| Operational transparency | 28.9 |
| Developer ergonomics | 21.4 |
| Access clarity | 34.2 |

**Agent readiness 22.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.4** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/first-citizens-bancshares/](https://apis.io/providers/first-citizens-bancshares/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for First Citizens BancShares: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/first-citizens-bancshares/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
