# McMaster University (mcmaster)

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
