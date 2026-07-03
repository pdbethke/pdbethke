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
identity, verification gates, and a fully attributed audit trail. It absorbed my
earlier agentic write-governance platform: five-gate validated writes, dry-run by
default with before/after diffs, immutable per-call audit, and the multi-agent
file-claim broker that grew into the corral itself. Watch it live: `make demo-mission`.

**Multi-Tenant Publishing Platform** — *the SaaS a media business runs on* (private, commercial)
The complete platform a regional media & publishing business runs on: product and
listing management, a CMS with inline page and navigation editing, an events
subsystem with full RFC 5545 recurrence, and a commerce layer — rate cards,
campaigns, invoicing, accounting sync. A Django/DRF core behind a versioned
TypeScript SDK (with Svelte components) consumed by a SvelteKit admin and SSR
public sites; per-tenant branded SSO on self-hosted OIDC (Authentik); semantic +
vector search; and an agent-governed MCP write surface over the whole schema.
15+ coordinated repos with a cascading CI/CD pipeline onto self-hosted
infrastructure. The Media Library below is its media + AI engine.

**Media Library** — *AI-native, multi-tenant media platform*
Full media management (Cloudflare-Worker CDN with on-the-fly resize/AVIF, async video
pipelines) plus an AI layer: multi-provider generation behind one adapter, an
MCP/agent research-and-synthesis hub, semantic search. Quarantine-first safety
through five layers (Safe Browsing → ClamAV → NSFW ML → CSAM hashing → lifecycle
expiry). Shipped as a reusable SDK + SvelteKit app powering two product lines.

**Kirby** — *a virtual-tabletop platform for the HERO System* (private, in development)
A constellation of FastAPI services around Foundry VTT: campaign generation, a
combat assistant where **an LLM selects tactical intent but a deterministic
engine and seeded, auditable RNG resolve every outcome** (the model never invents
numbers), AI text/image generation routed through the media platform's engine,
and its own identity provider (self-hosted Authentik). Same governance thesis as
everything above — AI proposes, a deterministic layer decides — applied to games.

**HERO System rules engine** — *a licensed tabletop rules engine, proven to parity*
A licensed, from-scratch Python implementation of the HERO System 6E
character-cost rules, built solely as **Kirby's internal costing core — it mirrors
the system faithfully and is not a competitor to Hero Designer**. Hero Designer is
the reference implementation it honors: validated to **100% parity across 28,593
calculations** (1,000+ unit tests, 650+ fixtures) precisely so the VTT resolves
costs exactly as the official tool does. FastAPI + SvelteKit interface; rulebook
RAG answers "what's the actual rule" with page-level citations.

*Apart from corralai, these are private projects — inquiries are welcome.*

## Experience

- **President & Lead Consultant**, SiteShell.net — *2001–present.* Full-stack
  consultancy; sole architect on most engagements, owning data modeling through
  deployment, hardening, and years-long maintenance. ~20 years in Python/Django, now
  focused on AI-agent-operable platforms.
- **Integration Architect / Lead Software Application Developer**, Randstad USA —
  *2022–2024.* Multi-region integration architecture for the enterprise R-One
  platform; enterprise-scale AWS applications; software lead in cross-functional Agile teams.

## What clients say

> “Peter and I have been working together for many years, from when my company had
> a revenue stream of less than \$10 million. Needless to say, we couldn't afford
> an IT department, much less a full-time programmer or consultant. I don't
> remember how we met, but he was a godsend. Peter, with his innate intelligence
> and deep knowledge of technology, was able to clearly understand our business
> needs, translate them into the technological equivalent and deliver the results
> that allowed us to grow to over \$100 million in revenue. We eventually formed
> an IT department, but whenever we had business challenges that (we suspected)
> had a technological solution, he was the first and only person we would call.
> To summarize: highly intelligent, speaks tech to the tech people and translates
> to the business people, able to understand business processes and convert them
> to tech solutions, very hands-on and always answers a call — all great traits
> we've appreciated in our business relationship.”
>
> — **Rossi Bonugli**, co-founder, Cella, Inc. (now part of Randstad US Technologies Group)

> “I had the pleasure of working with Peter over the course of many years on
> several high-impact projects. Peter is extremely professional, collaborative
> and a partner in the truest sense of the word. Peter cared very much about the
> success of our business. I highly recommend Peter and wouldn't hesitate to work
> with him again in the future.”
>
> — **Conor Smith**, former co-CEO, Cella, Inc. (now part of Randstad US Technologies Group)

## Education & affiliations

M.A. Screenwriting, USC · B.A. English, Middlebury College ·
Partner at Divio (DjangoCMS); DjangoCMS Association member ·
First Dan Black Belt, Jidokwan Taekwondo 🥋

## Contact

[LinkedIn](https://www.linkedin.com/in/peter-dbethke-07b26b) · pdbethke@gmail.com
