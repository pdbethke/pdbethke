# Peter D. Bethke

**I build backends AI agents can safely operate.**

The thread through everything I have done is data translation — taking data that lives in one system’s logic and reshaping it into what another system, or the business, actually needs. I translate at every layer: data between systems, and systems to the people who use them.

## Open source

**[corral](https://github.com/pdbethke/corralai)**
Corral breaks your code on purpose and checks whether your tests notice. It plants faults that violate a stated guarantee, runs your own suite against each one in a sandbox, and reports how many it killed — measured by execution, never taken on a model’s word.

**[kirby-cost](https://github.com/pdbethke/kirby-cost)**
A from-scratch port of the HERO System 6E character build and cost engine, validated to 100% parity with the reference implementation across 656 fixtures, every character exact on every object. Parity is a release gate, not a one-time claim.

**[sigma-rbac-lab](https://github.com/pdbethke/sigma-rbac-lab)**
Scoped grants, a multi-tenant read/write boundary, and a scoped agent, all verified against a SQL oracle. Every research lab carries its own VERIFY.md, so a skeptical reader can read the code, run the oracle, and use the live workbook — three things to check, not one to take on faith.

**[erd-to-schema](https://github.com/pdbethke/erd-to-schema)**
What Sigma’s assistant rebuilt from a mermaid ERD image and two prompts, with a SQL oracle that verifies its output. This one tests a tool; sigma-rbac-lab is the system I built myself — worth keeping straight, since they are both RBAC and both live on Sigma Public.

**[agent-indexing-lab](https://github.com/pdbethke/agent-indexing-lab)**
The repo backing the article, carrying its own oracle and VERIFY.md so the study’s claims can be checked rather than taken on faith.

**[sportspicker-core](https://github.com/pdbethke/sportspicker-core)**
Dependency-free scoring and aggregation for pick’em contests, written to be an audit subject for corral — the guarantee that corral enforces is exactly what corral audits it against. Included precisely because it shows the corral thesis applied to my own code.


## Platform & product work

**ProductBinder / WebOffice** — *private · commercial · in development*
Product and listing management, a CMS with inline page and navigation editing, an events subsystem with full RFC 5545 recurrence, and a commerce layer covering rate cards, campaigns, invoicing, and accounting sync.

**Media Library**
A Cloudflare-Worker CDN with on-the-fly resize and AVIF negotiation, async video pipelines, multi-provider AI generation behind one adapter, semantic search, and a quarantine-first safety pipeline: Safe Browsing, then ClamAV, then NSFW ML, then CSAM hashing, then lifecycle expiry.

**Agent write-governance (MCP)**
An MCP surface over the production schema: schema-validated, permission-checked, dry-run-by-default with before/after diffs, and an immutable per-call audit trail.

**[Kirby VTT platform](https://kirbyvtt.org)**
Campaign generation, procedural maps, and a combat assistant, where a deterministic engine with seeded, auditable RNG resolves every outcome — the same result every time, from the same seed.

**Self-hosted identity**
Per-tenant branded OIDC/SSO, run as two independent Authentik deployments serving the two product lines separately.

**[Cella](https://cellainc.com)**
Cella could not afford an IT department. I was the whole function, through the company’s growth from under $10M to over $100M in revenue. The substance of the engagement was an enterprise-scale staffing application with extensive third-party integrations and custom APIs, later architected and maintained on AWS — the public website was its visible surface, not its subject.

**R-One integration architecture** — *Randstad USA · 2023–2024*
As integration architect I built the server that abstracted multiple US source systems behind a common layer and streamed them, via Google Pub/Sub, into the Netherlands-based R-One platform’s data warehouse. Cross-border data harmonisation, owned from concept through initial build.

**Product-data transformation for a specialty-chemicals manufacturer**
A product-data transformation API feeding a compliance-document system: it navigates JD Edwards’ opaque, denormalized schema and produces clean, correctly-shaped datasets for the downstream application that generates the compliance documents.


## Featured

**[Ask Charles](https://public.sigmacomputing.com/view-workbook?workbook=50pa3zNuDCZnhaMU1aFdy5)**
A data-center site selector that ranks all 3,144 U.S. counties on the factors that decide a site, with a grounded advisor that re-reasons as the priorities change.


## Contact

[LinkedIn](https://www.linkedin.com/in/peter-d-bethke-07b26b/) · pdbethke@siteshell.net · [peterdbethke.com](https://peterdbethke.com)

<!-- Generated from peterdbethke.com. Edit the site, not this file. -->
