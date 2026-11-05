# Source inventory

All 20 requested public GitHub repositories were inspected at their detected default branch and recorded at the source commit SHA in `skills-manifest.json`.

Classification is based on static tree inspection. `REGISTERED_SKILL_SOURCE` means one or more genuine `SKILL.md` files were selected. Application/framework sources without a selected compatible Skill are recorded as `REFERENCE_ONLY` or `APPLICATION_NOT_INSTALLED`.

See `skills-manifest.json` for the exact SHA, branch, selected paths, counts, and installation status for every source.

No source repository was cloned into this library. Only selected Skill source files were saved.

## Incremental sources added

The following ten repositories were inspected and appended in the current incremental update. Exact branches, commits, classifications, licenses, and selected paths are in `skills-manifest.json`.

- `public-apis/public-apis` — reference-only; no genuine Skill found.
- `DietrichGebert/ponytail` — genuine Skills; canonical `skills/` paths selected.
- `alibaba/open-code-review` — genuine Skills; duplicate plugin mirrors excluded.
- `tirth8205/code-review-graph` — genuine Skills.
- `kepano/obsidian-skills` — genuine Skills.
- `obra/superpowers` — genuine Skills.
- `NVIDIA/SkillSpector` — genuine Skill; test fixtures excluded.
- `cloudflare/security-audit-skill` — genuine Skill; audit runtime inactive.
- `trycompai/crm` — application with embedded `.agents/skills/` Skills; application not installed.
- `krayin/laravel-crm` — application with embedded `.github/skills/` Skills; application not installed.

## Marketing, SEO, design, and AI sources added

- `gcpdev/llm-council-skill` — one stored-only LLM Council Skill; external model/API requirements deferred.
- `aiwithremy/claude-skills-llm-council` — one distinct root LLM Council Skill; preserved separately.
- `mvanhorn/last30days-skill` — one stored-only research Skill; network/account access deferred.
- `cheaper-inference/OmniRoute` — embedded Skills collected; application, proxy, server, MCP, and routing runtime excluded.
- `headroomlabs-ai/headroom` — application/framework reference-only; no genuine Skill found.
- `joeseesun/qiaomu-seo` — one stored-only SEO Skill.
- `vercel-labs/agent-skills` — six distinct Skills imported; three byte-identical existing Skills skipped.
- `nextlevelbuilder/ui-ux-pro-max-skill` — seven canonical `.claude/skills/` Skills imported; generated mirrors excluded.
- `zubair-trabzada/geo-seo-claude` — sixteen GEO/SEO Skills imported.
- `AgriciDaniel/claude-seo` — thirty-five Skills imported; duplicate DataForSEO path skipped and distinct extension image Skill preserved with a path-qualified identity.

## Added day-trading source (2026-11-05)

- [Jakeschincariol/day-trader-skill](https://github.com/Jakeschincariol/day-trader-skill) — 11 genuine Skills with Python entry points, pinned to `3d0f4ef6986f4984b7c6bd46f7ff4f87744c3abd`; MIT license preserved; static source copy only. No executions, accounts, credentials, or broker integration configured. Cloud Python/market-network access and actual Codex discovery remain untested.
