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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

This is a repository for tracking the APIs, SDKs, and other developer resources for First Citizens BancShares (FCB).

First Citizens BancShares is a super-regional financial holding company and the parent of First-Citizens Bank & Trust, providing general banking, trust, investment, insurance, and asset-management services.

## APIs

First Citizens does not operate a first-party developer portal on firstcitizens.com. Its real programmable surface comes through **Silicon Valley Bank (SVB)** — acquired in 2023 and now a division of First Citizens — whose Apigee-backed developer portal at [developer.svb.com](https://developer.svb.com) publishes a family of commercial banking REST APIs (base URL `https://api.svb.com`, OAuth2 + JSON Web Signature):

- **SVB Authorization API** — OAuth2 token issuance + JWS request signing
- **SVB Account Balance API** — real-time account balances
- **SVB Account Transfer API** — book transfers between own accounts
- **SVB ACH Transfers API** — domestic, verified, and IAT ACH (Plaid instant account verification)
- **SVB Instant Payments API** — real-time payments
- **SVB Wires API** — domestic and international wires
- **SVB Stop Payment API** — stop-check orders
- **SVB Virtual Cards API** — virtual card numbers for AP, procurement, travel
- **SVB Webhook API** — asynchronous event subscriptions
- **SVB Reference API** — instant-payments reachability look-ups

Access is partner-gated (commercial onboarding). Consumer account data on firstcitizens.com is reachable via the **Plaid** aggregator. No downloadable OpenAPI/Swagger is published — the portal renders an interactive reference client-side.

## Tags

- Banking
- Financial Services
- Commercial Banking
- Payments
- ACH
- Wire Transfers
- Virtual Cards
- Open Banking
- United States

## Properties

- [Website](https://www.firstcitizens.com)
- [Developer Portal (SVB)](https://developer.svb.com)
- [Documentation](https://developer.svb.com/apis/docs-home)
- [GitHub (SVB)](https://github.com/svb)
- [LinkedIn](https://www.linkedin.com/company/first-citizens-bank)
