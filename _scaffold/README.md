# Quarantined scaffold artifacts — SS&C Geneva

Moved here 2026-10-17 during a provenance review. **These files are not part of the live profile.**

`openapi/_original/ssc-geneva-fund-accounting-openapi.yml` is **not an SS&C contract**. It was
generated as a placeholder (around commit 45135c7) without any SS&C source:

- Its server is `https://api.ssctech.example.com/geneva/v1` — a reserved `example.com` host that does not exist
- Its license URL is SS&C's privacy page
- It describes six generic paths (portfolios, positions, trades, NAV, investors) that are not evidenced anywhere SS&C publishes

Everything else in this folder was derived from that placeholder or generated alongside it, and
carries no independent evidence:

- `openapi/` — the placeholder and the five split OpenAPIs (investors, nav, portfolios, positions, trades) cut from it
- `collections/`, `postman/` — Postman and Open Collection files generated from those OpenAPIs
- `examples/`, `json-schema/`, `json-structure/`, `json-ld/`, `vocabulary/` — invented payloads, schemas and terms for the same entities
- `agentic-access/`, `authentication/` — classified/derived from the placeholder OpenAPI (Bearer/Basic auth is not evidenced)
- `rules/` — Spectral rulesets written against the placeholder
- `plans/`, `rate-limits/`, `finops/` — scaffold tiers, quotas and billing pointing at the example.com host

SS&C publishes **no** public API reference, **no** machine-readable specification, **no** API
pricing and **no** rate-limit documentation for Geneva. Geneva is enterprise software; SS&C provides
its integration documentation to licensed clients through its client portals.

Per the network convention — record what a provider actually publishes and skip what is honestly
absent — the correct state for Geneva is **absent**, not scaffolded. Kept rather than deleted so the
pass that produced them can be traced. Do not restore without provider-published evidence.
