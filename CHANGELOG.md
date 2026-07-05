# Changelog

All self-iteration runs are logged here (newest first), following the spirit of
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/). This project uses
date-based entries rather than SemVer versions. See [`SELF-UPDATE.md`](./SELF-UPDATE.md).

## [Unreleased]

## [2026-07-05]

### Added
- 2 extra picks (both cross-agent, per-agent installs verified from upstream READMEs): [ponytail](./skills/extra-ponytail.md) (`DietrichGebert/ponytail`, ~74k — YAGNI / code-minimalism skill) and [caveman](./skills/extra-caveman.md) (`JuliusBrussee/caveman`, ~84.1k — output-token reduction). Both were seen in an earlier discovery pass and initially skipped; re-reviewed and confirmed ✅✅✅.
- README skills badge updated to 10 core + 10 extra.

### Changed
- Curation mechanism hardened after a triage post-mortem (the two picks above were skipped in the 07-04 run on description-derived signals): `scripts/discover.sh` hints are renamed to `desc:*` and explicitly marked non-rejecting; `SELF-UPDATE.md` §B.2 gained triage rules (rejection requires the same verification rigor as acceptance; never judge by tone) and a persistent **Triage log** in `skills/INDEX.md`, seeded with the 07-04 deep-checked rejections.

## [2026-07-04] — Self-iterate run

### Added
- 3 new extra picks discovered via `scripts/discover.sh` and verified: [Taste Skill](./skills/extra-taste-skill.md) (`Leonxlnx/taste-skill`, ~55.7k), [UI/UX Pro Max Skill](./skills/extra-ui-ux-pro-max-skill.md) (`nextlevelbuilder/ui-ux-pro-max-skill`, ~100k), and [Graphify](./skills/extra-graphify.md) (`Graphify-Labs/graphify`, ~77.2k).
- Graphify was first parked in a "Candidates (needs human review)" section, then promoted once its explicit per-agent install commands (Claude Code / Codex / OpenCode) were verified from its README.

### Changed
- Star refresh: Superpowers 245k→246k; addyosmani Agent Skills 68.7k→68.8k. All other entries unchanged at manifest precision.

### Notes
- Repos flagged/dead: none. E2E gate: 41 checks, 0 failed. `scripts/discover.sh` surfaced ~117 candidates; skipped agent-harnesses/desktop apps/MCP-proxies (out of scope) and Claude-only tools (prefer cross-agent).

## [2026-07-03]

### Added
- Seeded 10 core skills + 5 extra picks. Star counts and compatibility verified as of 2026-07.
