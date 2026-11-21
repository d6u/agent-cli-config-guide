# Agent CLI & Desktop App Config Guide

Interactive architecture reference comparing how **Claude Code (CLI + Desktop)**, **Codex (CLI + Desktop App)**, and **Antigravity (CLI + Desktop App)** manage global, project, and subdirectory configurations.

**Live Site:** https://d6u.github.io/agent-cli-config-guide/

## Covered Pillars

1. **Standing Instructions** — `CLAUDE.md`, `.claude/rules/*.md`, `AGENTS.md`, `AGENTS.override.md`, `GEMINI.md`, and `.agents/rules/*.md`
2. **MCP Server Configs** — `~/.claude.json`, `.mcp.json`, `managed-mcp.json`, `claude_desktop_config.json`, `config.toml` (`[mcp_servers.*]`), and `mcp_config.json`
3. **Skills & Custom Commands** — `SKILL.md` progressive disclosure, CLI-exclusive paths, and precedence / coexistence rules
4. **Configs & Settings** — `settings.json`, `config.toml`, discovery manifests, and App vs. CLI deltas

## Interactive Views

- **Comparison Matrix** with pillar, tool, scope, OS (`macOS` / `Windows` / `Linux`), and `App ≠ CLI Only` filters
- **Merge & Precedence Simulator** across 4 live scenarios (Instructions Walk, MCP Collision, Skill Ladder, Config & Arrays)
- **Filesystem Explorer** with example config snippets
- **Critical Gotchas & Limits**
