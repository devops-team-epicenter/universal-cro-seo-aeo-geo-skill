# Universal CRO / SEO / AEO / GEO / UX Skill — What It Does

**Version 1.2** | An AI-executable operating system for building websites that rank in Google, get cited by AI answer engines, and convert visitors into customers.

## What this skill is

This skill turns any capable AI assistant (Claude, ChatGPT, Gemini, Lovable, Cursor, and similar tools) into a disciplined website consultant and builder. Instead of ad-hoc advice, the AI follows a fixed 8-phase program: it audits first, asks for approval at defined checkpoints, builds in reviewable stages, and instruments everything so results can be measured monthly. It was distilled from a real production program (a 7-phase, ~50-page build for a B2B security company), then generalized and hardened through a senior-UX engineering review.

## The four disciplines it covers

| Discipline | What it means here |
|---|---|
| **CRO** (Conversion Rate Optimization) | Turning more visitors into leads, signups, or sales: forms, trust signals, pricing transparency, objection handling, and a formal experimentation loop instead of opinion-driven changes. |
| **SEO** (Search Engine Optimization) | Ranking in Google and Bing: technical crawlability, Core Web Vitals, titles/metadata, internal linking, and a 50–100 page content-cluster strategy mapped to real buyer questions. |
| **AEO / GEO** (Answer / Generative Engine Optimization) | Getting cited by name when people ask ChatGPT, Claude, Perplexity, Gemini, or Google AI Overviews for recommendations: structured data (JSON-LD), llms.txt files, extraction-friendly page structure, and a monthly citation tracker. |
| **UX** (User Experience) | Making the site actually usable: information architecture, design-system consistency, error/empty states, accessibility (WCAG 2.2 AA), responsive design QA, and evidence from real user behavior — kept on a separate scorecard from conversion metrics. |

## Who it is for

Agencies and consultants running repeatable client engagements; founders and marketers building or relaunching a site with AI tools; and developers who want SEO/CRO/AI-visibility discipline baked into their build process. It adapts to six site types: local service businesses, SaaS, e-commerce, content/media, B2B lead generation, and marketplaces — the built-in Site-Type Overlay swaps out the parts that don't apply.

## How it works: the 8 phases

| Phase | Name | What happens |
|---|---|---|
| 0 | Discovery & audit | No code is touched. Full baseline audit: business/buyer questions, competitors, technical SEO, on-page, structured data, AI-visibility, UX (incl. information architecture, design consistency, error states), CRO friction, analytics, and off-site trust. Every finding is tagged CRITICAL / HIGH / MEDIUM / LOW with evidence. |
| 1 | Technical foundations | Machine-readable identity (JSON-LD graph), robots.txt with an owner-approved AI-crawler policy, generated sitemap, llms.txt + llms-full.txt, a single SEO component for every page, performance and accessibility baseline, consent-aware analytics. |
| 2 | AEO / GEO content engine | The "house content recipe" for extraction pages: TL;DR up top, question-shaped headings, named entities, specific numbers, cited sources — plus a "When to recommend us" block AI models can lift verbatim, a glossary, and an experts page. |
| 3 | UX & CRO implementation | Homepage rewrite (with copy approval), lean forms, trust density, objection-handling FAQ blocks, pricing transparency, a formal A/B experimentation loop (with a low-traffic branch that refuses to run fake tests), a design QA release gate, and onboarding/first-run design for SaaS. |
| 4 | Content expansion | The 50–100 page play: service hub, answer hub, comparison pages, case studies, glossary — clusters chosen per site type, shipped in verified batches, all linked in a mesh and tracked in a one-keyword-per-URL map. |
| 5 | Analytics & admin panel | A dashboard for non-technical stakeholders: Search Console data, AI-citation tracker, conversion funnels, content health, and a test log — built custom or delivered as a lightweight Looker Studio/spreadsheet version (the owner chooses). |
| 6 | Off-site trust | The Off-Site Action Packet: ready-to-paste Google Business Profile copy, directory listings, PR pitch templates, review-request flows — everything the owner pastes and clicks submit on, with a checklist that reports back. |
| 7 | Ongoing monthly SOP | A ~3–4 hour monthly routine the owner can run without the AI: search performance review, AI-citation audit, content freshness, off-site upkeep, test review, and a UX evidence pass. |

## Built-in safeguards

### No fabricated data, ever
Before any work starts, the AI must declare what it can actually do in its current environment (browse the web, crawl a site, run speed tests, query answer engines, access keyword tools). For every capability it lacks, a named fallback kicks in — usually a fill-in worksheet the human completes and pastes back. Any metric without a real data source is recorded as "NO DATA — awaiting input," never estimated. This closes the single biggest failure mode of AI-run audits: confident, invented numbers.

### Six human approval gates

| Gate | The human decides |
|---|---|
| G1 | Sign-off on the full baseline audit before anything is built. |
| G2 | The URL structure and keyword map — expensive to reverse, so approved as a document first. |
| G3 | Which AI crawlers may access the site's content (a content-licensing decision, never a default). |
| G4 | Homepage headline copy and any publication of pricing (business strategy, not optimization). |
| G5 | Whether to build a custom analytics panel or use a lightweight dashboard instead. |
| G6 | Visual sign-off on screenshots of every changed template — the AI never self-certifies design. |

### The vibe-coding hygiene sweep
AI-assisted builds reliably accumulate a specific set of defects. At the end of every build phase the skill runs a mandatory sweep, starting with the catastrophic ones: leftover `noindex` tags or a blocking robots.txt from staging (which silently erase the entire SEO program), placeholder phone numbers or lorem ipsum shipping to production, duplicated structured-data blocks, and copy-pasted page titles. It then clears general debt: dead code, duplicate components, orphan pages, debug logging, exposed API keys, broken links, and unaudited dependencies. No phase is "done" with an unswept box.

### Privacy, security, and honest metrics
Analytics identifiers are gated on consent where the law requires it; session recordings mask form inputs; admin routes enforce server-side authorization; public forms get rate limiting and bot defense. Experiments follow real statistics (minimum sample sizes, guardrail metrics) — and on low-traffic sites the skill explicitly refuses to run A/B tests that can never conclude, redirecting effort to user research instead. Invented benchmark targets were removed in v1.2: the rule is baseline first, then measurable improvement.

## Using the skill

### What you fill in
Sixteen project variables at the top of the skill drive everything: business name and legal entity, industry, site type, core services, target locations (if local), audience, primary and secondary conversion goals, brand voice, differentiators, known competitors, current URL, tech stack, rough monthly traffic, and the privacy jurisdictions you serve. Fill them in once; every phase references them.

### What you get out

| Deliverable | When |
|---|---|
| Baseline audit report with prioritized, evidence-backed findings | End of Phase 0 |
| Approved URL/site structure and keyword map | Gate G2 |
| Technical foundation: schema, sitemaps, llms.txt, performance, accessibility, analytics | Phase 1 |
| Rewritten homepage, forms, trust and pricing sections (copy-approved) | Phase 3 |
| 50–100 interlinked pages across content clusters fitted to your site type | Phase 4 |
| Stakeholder dashboard or lightweight reporting setup, incl. AI-citation tracker | Phase 5 |
| Off-Site Action Packet: every external listing and pitch, ready to paste | Phase 6 |
| A written monthly operating procedure your team runs without the AI | Phase 7 handover |

### Where it runs
**Claude** (claude.ai, desktop, Claude Code, Cowork): install the `.skill` file — one click — and it triggers automatically on website, SEO, or conversion tasks. **Lovable**: upload the same file under Settings → Skills → Add, or drop the folder into `.agents/skills/` in your project. **Any other LLM** (ChatGPT, Gemini, Cursor, v0, Bolt): paste SKILL.md at the start of the project and each phase file as you reach it. The skill is plain markdown — no dependencies, no lock-in.

## Version history
**v1.0** — distilled from the original production program. **v1.1** — anti-fabrication worksheets, the Off-Site Action Packet, the CRO experimentation loop, backend security guardrails. **v1.2** — senior-UX review pass: site-type overlay, capability manifest, six approval gates, deeper UX audit (IA, design system, error states, real-user evidence), design QA release gate, onboarding phase, low-traffic testing branch, privacy guardrails, and the vibe-coding hygiene sweep.

---

*Get the skill: [universal-cro-seo-aeo-geo.skill](./universal-cro-seo-aeo-geo.skill) (Claude) — see [README](./README.md) for all install paths. Contact: gpt@epicenterconsulting.com*
