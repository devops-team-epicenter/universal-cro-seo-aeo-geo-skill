# Universal CRO / SEO / AEO / GEO / UX Skill — v1.2

A reusable, LLM-agnostic operating system for auditing and building websites
that rank in Google, get cited by AI answer engines (ChatGPT, Claude,
Perplexity, Gemini, AI Overviews), and convert — across any industry, stack,
or site type.

Distilled from a real 7-phase production program (guardtress.com), generalized
in v1.1, and hardened in v1.2 with a senior-UX review pass: site-type overlay,
capability manifest, human approval gates, design QA release gate, low-traffic
experimentation branch, privacy/consent guardrails, and a vibe-coding hygiene
sweep that runs at the end of every build phase.

## Structure

```
universal-cro-seo-aeo-geo/
├── SKILL.md                     # Core: variables, principles, overlay,
│                                # capability manifest, approval gates, kickoff
└── references/
    ├── phase-0-audit.md         # Discovery & end-to-end audit
    ├── phase-1-foundations.md   # Technical foundations
    ├── phase-2-aeo-content-engine.md
    ├── phase-3-ux-cro.md        # UX/CRO impl + experimentation + design QA
    ├── phase-4-content-expansion.md
    ├── phase-5-admin-panel.md
    ├── phase-6-offsite.md       # Off-Site Action Packet
    ├── phase-7-sop.md           # Monthly SOP
    ├── guardrails.md            # Content/SEO, security, privacy, hygiene sweep
    └── attribution-and-changelog.md
```

## Install

**Claude (Claude.ai / Claude Desktop / Cowork):** download
`universal-cro-seo-aeo-geo.skill` from Releases (or build it by zipping the
skill folder with a `.skill` extension) and open it in the Claude app — click
**Save skill**.

**Claude Code:** copy the `universal-cro-seo-aeo-geo/` folder into
`~/.claude/skills/` (personal) or `.claude/skills/` in your project.

**Lovable:** copy the folder into your project at
`.agents/skills/universal-cro-seo-aeo-geo/` (see the `lovable/` layout zip in
Releases, ready to drop in).

**Any other LLM (ChatGPT, Gemini, Cursor, v0, Bolt):** paste SKILL.md at the
start of a project, then paste each phase reference file when that phase
begins.

## Usage

1. Fill in the PROJECT VARIABLES block in SKILL.md.
2. The model applies the Site-Type Overlay and runs Phase 0.0 (capability
   manifest) before anything else.
3. Phases 0 → 7 execute in order, stopping at six human approval gates
   (audit sign-off, URL/IA map, AI-crawler allow-list, homepage/pricing copy,
   admin-panel build-vs-buy, design QA).
4. Never let the model fabricate data: every external data dependency has a
   named worksheet/fallback.

## Versioning

See `references/attribution-and-changelog.md` for the full v1.0 → v1.2
lineage and what changed in each pass.

## License

MIT — see LICENSE.
