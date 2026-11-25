# acuris-geo-com

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

Acuris Geo provides developer APIs for global address validation and geocoding across more than 240 countries, delivering point-coordinate precision, forward and reverse geocoding, UK Royal Mail PAF data (UDPRN/UPRN), and eIDAS 2.0 EUDI Wallet verification. The service offers real-time responses and includes an open-source MCP server for AI assistants such as Claude, Cursor, and Copilot. It serves worldwide customers seeking reliable location data and compliance-ready address services.

**Areas:** Company · Geocoding · Address Validation · Location Data

## acuris-geo-com on APIs.io

Everything profiled for acuris-geo-com is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/acuris-geo-com/](https://apis.io/providers/acuris-geo-com/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [acuris-geo-com Account API](https://apis.io/apis/acuris-geo-com/acuris-geo-com-account-api/) — Key check and account-related helpers
- [acuris-geo-com Billing API](https://apis.io/apis/acuris-geo-com/acuris-geo-com-billing-api/) — Stripe-hosted self-serve subscription checkout
- [acuris-geo-com Config API](https://apis.io/apis/acuris-geo-com/acuris-geo-com-config-api/) — Client configuration for forms
- [acuris-geo-com Geocoding API](https://apis.io/apis/acuris-geo-com/acuris-geo-com-geocoding-api/) — Rooftop / reference-database geocoding
- [acuris-geo-com Postcode lookup API](https://apis.io/apis/acuris-geo-com/acuris-geo-com-postcode-lookup-api/) — UK postcode → all addresses (Royal Mail PAF)
- [acuris-geo-com Suggest API](https://apis.io/apis/acuris-geo-com/acuris-geo-com-suggest-api/) — Autocomplete-style suggestions
- [acuris-geo-com Validation API](https://apis.io/apis/acuris-geo-com/acuris-geo-com-validation-api/) — Address validation and free-tier transactions
- [acuris-geo-com Versioned aliases (v1) API](https://apis.io/apis/acuris-geo-com/acuris-geo-com-versioned-aliases-v1-api/) — Stable `/v1/*` mirrors of the core endpoints. Behaviour is identical to the unversioned routes above — same engine, same response schema — but the path is…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [acuris-geo-com-mcp.yml](https://apis.io/servers/acuris-geo-com/acuris-geo-com-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [acuris-geo-com Agentic Access](https://apis.io/agentic-access/acuris-geo-com/acuris-geo-com-agentic-access/)

#### JSON Schema (7)

The data models the API reads and writes.

- [DevKeyResponse](https://apis.io/schemas/acuris-geo-com/acuris-geo-com-dev-key-response/)
- [ForwardGeocodeResponse](https://apis.io/schemas/acuris-geo-com/acuris-geo-com-forward-geocode-response/)
- [GeocodeResponse](https://apis.io/schemas/acuris-geo-com/acuris-geo-com-geocode-response/)
- [PostcodeAddress](https://apis.io/schemas/acuris-geo-com/acuris-geo-com-postcode-address/)
- [ReverseResponse](https://apis.io/schemas/acuris-geo-com/acuris-geo-com-reverse-response/)
- [SuggestItem](https://apis.io/schemas/acuris-geo-com/acuris-geo-com-suggest-item/)
- [ValidateResponse](https://apis.io/schemas/acuris-geo-com/acuris-geo-com-validate-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Acuris Geo Com Context](https://apis.io/jsonld/acuris-geo-com/acuris-geo-com-context/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [acuris-geo-com Suggest Api Certification Overlay](https://apis.io/overlays/acuris-geo-com/acuris-geo-com-suggest-api-certification-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [acuris-geo-com API Rules](https://apis.io/rules/acuris-geo-com/acuris-geo-com-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [acuris-geo-com Authentication](https://apis.io/security/acuris-geo-com/acuris-geo-com-authentication/)
- [acuris-geo-com Domain Security](https://apis.io/security/acuris-geo-com/acuris-geo-com-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [acuris-geo-com Scopes](https://apis.io/scopes/acuris-geo-com/acuris-geo-com-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [acuris-geo-com Plans Pricing](https://apis.io/plans/acuris-geo-com/acuris-geo-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [acuris-geo-com Rate Limits](https://apis.io/rate-limits/acuris-geo-com/acuris-geo-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://acuris-geo.com/)
- [Getting started](https://api.acuris-geo.com/docs)
- [API reference](https://api.acuris-geo.com/docs)
- [Support](https://api.acuris-geo.com/support)
- [Terms of service](https://www.acuris-geo.com/terms/)
- [Privacy policy](https://www.acuris-geo.com/privacy-policy/)
- [GitHub](https://github.com/Acuris-GmbH)
- [Status](https://api.acuris-geo.com/status)

## API Evangelist rating

**Kin Score 54.8** — strong · rubric 0.28.1 · scored 2026-11-21

| Facet | Score |
|---|---|
| Discoverability | 58.3 |
| Contract quality | 64.2 |
| Contract governance | 33.3 |
| Operational transparency | 19.0 |
| Developer ergonomics | 66.0 |
| Access clarity | 59.6 |

**Agent readiness 38.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |
| Onboarding Descriptor | — |
| Dns Aid Index | na |
| Markdown Negotiation | na |

**Regulatory alignment 28.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/acuris-geo-com/](https://apis.io/providers/acuris-geo-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for acuris-geo-com: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/acuris-geo-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
