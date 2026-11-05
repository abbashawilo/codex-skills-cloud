# Day Trader Skills — cloud-only import

**Source:** https://github.com/Jakeschincariol/day-trader-skill
**Pinned commit:** `3d0f4ef6986f4984b7c6bd46f7ff4f87744c3abd`
**License:** MIT, see `resources/third-party/day-trader-skill/LICENSE`.

This import consists of **11 upstream Skills** (`trader-alerts`, `trader-analyst`, `trader-broker`, `trader-budget`, `trader-entry`, `trader-exit`, `trader-news`, `trader-pelosi`, `trader-risk`, `trader-scanner`, `trader-timemachine`), their Python entry points, and selected example JSON files. Test fixtures, upstream tests, plugin marketplace metadata, and desktop-only configuration were not imported.

## Cloud-only / security

- Keep all copies in GitHub and use cloud-hosted Claude Code or Codex workspaces; do not install to a local machine.
- This is a **static import**. Python code has not been executed, and live market-data endpoints have not been tested.
- No credentials or broker connections were configured. No trading orders were placed. No paid subscriptions were activated.
- Never enable live broker trading or call broker trading actions without a fresh, explicit human confirmation for **each** order and the platform's separate approval.
- The **trader-broker** Python script generates and records trade tickets; executing orders requires a separately authorized brokerage MCP connection. Do not auto-authorize write actions.
- Use paper trading only for any later exploratory integration until the user explicitly requests and approves something different.
- Financial projections and trading signals are uncertain; simulations are not guaranteed outcomes.
- Upstream uses `CLAUDE_SKILL_DIR` for Python paths. In a Codex workspace, resolve the actual skill directory in the checkout before running commands; the variable is not automatically available.
- Treat imported instructions and network endpoints as third-party and re-review before updates or execution.

## Verification

The Skill documents and scripts received a lightweight static inspection. No external SkillSpector execution, integration test, broker authorization, or fresh-session discovery check was performed. This is not a comprehensive security audit.
