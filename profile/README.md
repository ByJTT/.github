# ByJTT — Projects & Mods

Small, focused, reliable releases. Minimal footprint, clear docs, safe-by-default behavior.

## Game mods

### WoW Forever
- **[wow-forever-buff-reminder-addon](https://github.com/ByJTT/wow-forever-buff-reminder-addon)** — minimal Druid buff reminder (Mark of the Wild & Thorns). Shown only when missing; click to cast. Taint-safe, 1 Lua file + TOC.

*More games/mods will be added here over time.*

## Organization (scales to more games)

- **Default: one mod per repo** under this org. Use clear, searchable names that identify the game and purpose (example: `wow-forever-buff-reminder-addon`). Add topics like `wow-forever`, `<game>`, `mod`, `addon`.
- **New game?** Add a new section above + a new repo following the same pattern. No monorepo required unless a game genuinely needs a shared framework/tooling.
- **Repo name vs install name:** repo names can be SEO-friendly; the in-game folder/addon name must follow the game loader’s requirements (document the exact install path in each repo).
- **Non-mod projects** (apps/tools/libraries) can live in the same org with clear naming/topics so game mods remain easy to find.

## Standards

- Keep mods/addons **minimal**, dependency-light, and well-documented.
- Prefer **taint-safe / non-invasive** implementations where the platform requires it.
- Releases use **SemVer** + changelogs; version metadata (TOC/manifest), changelog, and git tags stay in sync.
- Public repos avoid personal data, secrets, account data, and local machine paths.
- Issues/PRs include version, game/client build, steps to reproduce, and diagnostics (no account data). Where useful, include `README` install steps, `llms.txt`, and `AGENTS.md` for AI/agent-friendly discovery.
