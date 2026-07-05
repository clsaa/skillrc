# skills/INDEX.md — Master Manifest & Compatibility Matrix

This is the machine-readable manifest for the Agent Onboarding Kit: it lists every curated skill, its category, its compatibility with each target agent, its star count, and a link to its detail page. Agents should read this file to decide what to install (see `AGENTS.md` for the full procedure).

## Legend

- ✅ — supported
- ⚠️ — works but not officially documented
- ❌ — not supported

## Core skills

| # | Skill | Type | Claude Code | Codex | OpenCode | Stars |
|---|-------|------|:-----------:|:-----:|:--------:|-------|
| 1 | [Superpowers](./superpowers.md) | Framework | ✅ | ✅ | ✅ | 246k |
| 2 | [SuperClaude Framework](./superclaude-framework.md) | Framework | ✅ | ❌ | ❌ | 23.4k |
| 3 | [MiniMax Skills](./minimax-skills.md) | Bundle | ✅ | ✅ | ✅ | 12.9k |
| 4 | [Anthropic Official Skills](./anthropic-official-skills.md) | Bundle | ✅ | ⚠️ | ⚠️ | 158k |
| 5 | [Vercel Agent Skills](./vercel-agent-skills.md) | Bundle | ✅ | ✅ | ✅ | 28.6k |
| 6 | [Planning with Files](./planning-with-files.md) | Collection | ✅ | ✅ | ✅ | 24.4k |
| 7 | [Context Engineering Skills](./context-engineering-skills.md) | Collection | ✅ | ✅ | ✅ | 16.9k |
| 8 | [Composio Skills](./composio-skills.md) | Collection | ✅ | ✅ | ⚠️ | 0.1k |
| 9 | [Antfu Skills](./antfu-skills.md) | Collection | ✅ | ✅ | ✅ | 5.5k |
| 10 | [Awesome Agent Skills](./awesome-agent-skills.md) | Directory | ✅ | ✅ | ✅ | 27.2k |

## Extra picks

Opinionated extras oriented toward AI, architecture, and full-stack work. The core 10 above already cover those three areas — AI: Context Engineering (#7), Composio/MCP (#8); architecture: Superpowers (#1), Planning with Files (#6); full-stack: Vercel (#5), MiniMax (#3), Antfu (#9). The 5 picks below extend those.

| # | Skill | Type | Claude Code | Codex | OpenCode | Stars |
|---|-------|------|:-----------:|:-----:|:--------:|-------|
| 1 | [addyosmani Agent Skills](./extra-addyosmani-agent-skills.md) | Collection | ✅ | ✅ | ✅ | 68.8k |
| 2 | [skill-creator](./extra-skill-creator.md) | Bundle | ✅ | ⚠️ | ⚠️ | 158k |
| 3 | [Awesome MCP Servers](./extra-awesome-mcp-servers.md) | Directory | ✅ | ✅ | ✅ | 90k |
| 4 | [Antigravity Awesome Skills](./extra-antigravity-awesome-skills.md) | Directory | ✅ | ✅ | ✅ | 42.3k |
| 5 | [Composio Awesome Claude Skills](./extra-awesome-claude-skills.md) | Directory | ✅ | ⚠️ | ⚠️ | 67k |
| 6 | [Taste Skill](./extra-taste-skill.md) | Collection | ✅ | ✅ | ✅ | 55.7k |
| 7 | [UI/UX Pro Max Skill](./extra-ui-ux-pro-max-skill.md) | Collection | ✅ | ⚠️ | ⚠️ | 100k |
| 8 | [Graphify](./extra-graphify.md) | Collection | ✅ | ✅ | ✅ | 77.2k |
| 9 | [ponytail](./extra-ponytail.md) | Collection | ✅ | ✅ | ✅ | 74k |
| 10 | [caveman](./extra-caveman.md) | Collection | ✅ | ✅ | ✅ | 84.1k |

## Triage log (reviewed, not added)

Deep-checked candidates rejected with a dated reason, so future self-iterate runs neither re-review them needlessly nor re-skip others on weak signals (see `SELF-UPDATE.md` §B.2). A logged rejection may be revisited if the repo materially changes.

- [headroom](https://github.com/headroomlabs-ai/headroom) — 2026-07-04 — compression library/proxy/MCP server, not an agent skill (out of scope).
- [Agent-Reach](https://github.com/Panniantong/Agent-Reach) — 2026-07-04 — web-access CLI/MCP tooling, not a SKILL.md-style skill (out of scope).
- [mattpocock/skills](https://github.com/mattpocock/skills) — 2026-07-04 — Claude Code-only (`.claude` conventions); manifest prefers cross-agent.
- [get-shit-done](https://github.com/gsd-build/get-shit-done) — 2026-07-04 — Claude Code-only system; manifest prefers cross-agent.

---

Compatibility and star counts as of 2026-07.
