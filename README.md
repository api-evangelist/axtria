# Axtria

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

Axtria is an AI-first cloud software and data analytics company for the life sciences
industry, founded in 2010 and headquartered in Berkeley Heights, New Jersey. Its cloud
products — Axtria DataMAx, Axtria InsightsMAx.ai, Axtria SalesIQ, Axtria MarketingIQ and
Axtria CustomerIQ — serve pharmaceutical, biotech, medical device, animal health and
consumer health commercial teams. Axtria reports 3,600+ employees serving 100+ life
sciences companies, including 16+ of the top 20 pharmaceutical enterprises.

- https://www.axtria.com/
- https://forgeglobal.com/axtria_stock/ (secondary market listing)

## API surface

**None public.** Enrichment probes on 2026-07-31 found no OpenAPI/Swagger document, no
GraphQL endpoint, no MCP server, no A2A agent card, no `/.well-known/` document, no
webhook or event catalog, no SDK in any public package registry, and no Axtria GitHub
organization.

Axtria runs a real product documentation host at `https://docs.axtria.com/`, but it is
**HTTP Basic-auth gated to customers** (401 on every path). Platform integration — Veeva
CRM / Veeva Vault CRM, Salesforce, Marketo and 20+ life sciences data sources over SFTP
and APIs — is delivered under enterprise contract rather than a self-service developer
surface. The InsightsMAx.ai launch positions "Agents, Apps and APIs", but no public
contract accompanies it.

## Artifacts

| Dir | File | Method |
|---|---|---|
| `changelog/` | `axtria-changelog.yml` | searched — seasonal release train, 15 entries across 4 products |
| `lifecycle/` | `axtria-lifecycle.yml` | searched — versioning, deprecation, SLA, status-page posture |
| `conformance/` | `axtria-conformance.yml` | searched — GDPR/UK GDPR/CCPA/HIPAA/FCRA named; no published certification |
| `security/` | `axtria-domain-security.yml` | probed — TLS 1.3 + HSTS on all hosts; SPF + DMARC `p=reject`; no DNSSEC, no CAA |
| `well-known/` | `axtria-well-known.yml` | probed — evidence of absence across every host |
| `packages/` | `axtria-packages.yml` | searched — evidence of absence across 7 registries |
| `llms/` | `axtria-llms.txt` | generated |
