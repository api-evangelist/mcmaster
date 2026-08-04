# McMaster University (mcmaster)

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

McMaster University is a public research university in Hamilton, Ontario, Canada, ranked #176 in the QS World University Rankings 2025. This repository catalogs McMaster's public developer and API footprint as an [APIs.json](https://apisjson.org/) provider profile for the API Evangelist network. McMaster operates a gated institutional API service developer portal (MacID authentication required) and a publicly accessible MacSphere DSpace OAI-PMH repository interface.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/mcmaster/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=mcmaster-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Canada, Ontario, Research, Open Access, Library

## APIs

- **McMaster API Service Developer Portal** — institutional API management portal; gated behind MacID authentication and registration, so the catalog is not publicly browsable. Docs: https://developer.api.mcmaster.ca/
- **MacSphere OAI-PMH Repository Interface** — public OAI-PMH 2.0 metadata-harvesting endpoint for the MacSphere DSpace institutional repository (`https://macsphere.mcmaster.ca/server/oai/request`). Docs: https://library.mcmaster.ca/research/getting-started-macsphere

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/mcmaster-plans-pricing.yml](plans/mcmaster-plans-pricing.yml)
- Rate Limits: [rate-limits/mcmaster-rate-limits.yml](rate-limits/mcmaster-rate-limits.yml)
- FinOps: [finops/mcmaster-finops.yml](finops/mcmaster-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.mcmaster.ca/
- Developer Portal: https://developer.api.mcmaster.ca/
- GitHub: https://github.com/mcmaster-university
- LinkedIn: https://ca.linkedin.com/school/mcmaster-university/
- Status: https://uts.mcmaster.ca/status/

## Notes

- The developer portal at developer.api.mcmaster.ca resolves (HTTP 200) but is fully gated behind MacID authentication; no API names, endpoints, or documentation are publicly verifiable, so none are fabricated here.
- The MacSphere OAI-PMH endpoint was confirmed live (`verb=Identify` returns repository name "Macsphere at McMaster University"); the legacy `/oai/request` path returns 404.
- The `mcmaster-university` GitHub organization exists (id 47285564) but currently has zero public repositories.
- No dedicated `status.mcmaster.ca` subdomain exists; the UTS status page is used instead.

## Maintainers

- Kin Lane — kin@apievangelist.com
