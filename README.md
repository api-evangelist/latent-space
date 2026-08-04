# Latent Space

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

Latent Space is an artificial intelligence company building generative models for
businesses and creatives. General Catalyst describes it as creating "AI technology
for predictive analytics and data-driven insights." The company raised a Series A
from Greylock and General Catalyst.

Backed by: general-catalyst, greylock

## Enrichment status (2026-07-19)

Identity verified; **no public developer surface exists**. Every path on
`latentspace.co` (apex and www) returns HTTP 302 to `https://x.com/latentspaceai`,
no `docs`/`api`/`developer`/`app`/`status` subdomains resolve in DNS, no
`/.well-known/` documents are served, no `llms.txt` is published, and the
`latentspaceai` GitHub organization has no public repositories.

No API, OpenAPI/AsyncAPI/GraphQL spec, SDK, CLI, MCP server, sandbox, changelog,
status page, or documentation was found — so the spec-derived artifacts
(`openapi/`, `mcp/`, `skills/`, `overlays/`, `errors/`, `conventions/`,
`data-model/`, `scopes/`, `authentication/`) are not applicable rather than missing.

Artifacts captured:

- `security/latent-space-domain-security.yml` — probed TLS/HSTS/DNSSEC/CAA/SPF/DMARC
- `well-known/latent-space-well-known.yml` — well-known discovery probe results
- `llms/latent-space-llms.txt` — generated llms.txt

Sources: <https://www.generalcatalyst.com/companies/latent-space>,
<https://x.com/latentspaceai>
