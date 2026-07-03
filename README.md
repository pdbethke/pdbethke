# Peter D. Bethke

**Full-Stack Software Architect — AI-Agent Systems, Security & Multi-Tenant Platforms**

I build backends that AI agents can **safely operate**, not just call — the governance
layer that makes AI autonomy shippable. Current work centers on agent-operable
platforms where every action is schema-validated, permission-checked, dry-run by
default, and audit-logged: **AI proposes; a deterministic, auditable layer decides.**

Nearly three decades of full-stack engineering spent at the frontier — early
team-based CMS → enterprise document systems → today's agentic AI and multi-tenant
security. I went deep on identity and safety because autonomy without guardrails is
a liability: self-hosted multi-tenant OIDC, deploy-gated pentest suites,
quarantine-first content pipelines.

I work where business meets engineering — degrees in English and screenwriting
trained me to turn business problems into systems, and to explain those systems back
to the people who fund them.

## Selected work

**[corralai](https://github.com/pdbethke/corralai)** — *coordinated multi-agent, multi-model* (public, Elastic-2.0)
An MCP-native brain a herd of coding agents — different models, different harnesses,
different machines — coordinate, remember, and re-plan through. Transactional
coordination (SQLite), analytical memory (DuckDB), bwrap-jailed execution, OIDC
identity, verification gates, and a fully attributed audit trail. Watch it live:
`make demo-mission`.

**Media Library** — *AI-native, multi-tenant media platform*
Full media management (Cloudflare-Worker CDN with on-the-fly resize/AVIF, async video
pipelines) plus an AI layer: multi-provider generation behind one adapter, an
MCP/agent research-and-synthesis hub, semantic search. Quarantine-first safety
through five layers (Safe Browsing → ClamAV → NSFW ML → CSAM hashing → lifecycle
expiry). Shipped as a reusable SDK + SvelteKit app powering two product lines.

**Agentic Write-Governance Platform (MCP)** — *AI agents safely operating a production database*
An MCP server embedded in a Django ASGI app: ~60 ORM-backed tools behind five-gate
write validation, dry-run-by-default with before/after diffs, atomic opt-in commits,
and an immutable audit trail — plus a multi-agent file-claim broker so several coding
agents work one repo without collisions.

**Domain Rules Engine + Governed LLM Decisioning**
A from-scratch Python port of a complex rules engine, validated to **100% parity
across 28,593 test cases**. An LLM selects tactical intent; a seeded RNG and the
deterministic engine resolve outcomes — the model never invents numbers. Rulebook
RAG answers "what's the actual rule," with citations.

## Experience

- **President & Lead Consultant**, SiteShell.net — *2001–present.* Full-stack
  consultancy; sole architect on most engagements, owning data modeling through
  deployment, hardening, and years-long maintenance. ~20 years in Python/Django, now
  focused on AI-agent-operable platforms.
- **Integration Architect / Lead Software Application Developer**, Randstad USA —
  *2022–2024.* Multi-region integration architecture for the enterprise R-One
  platform; enterprise-scale AWS applications; software lead in large Agile teams.

> *“…the first and only person we would call.”* — Co-founder, Cella, Inc.
> (client from under \$10M through \$100M+ revenue)

## Education & affiliations

M.A. Screenwriting, USC · B.A. English, Middlebury College ·
Partner at Divio (DjangoCMS); DjangoCMS Association member ·
First Dan Black Belt, Jidokwan Taekwondo 🥋

## Contact

[LinkedIn](https://www.linkedin.com/in/peter-dbethke-07b26b) · pdbethke@gmail.com
