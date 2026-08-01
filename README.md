# Axtria

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
