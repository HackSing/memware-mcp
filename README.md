# Memware

**One Memory. Every Agent. Always Knows You.**

Website: **[aiware.life](https://aiware.life)**

Memware gives every MCP-compatible AI agent—Claude Code, Codex, Cursor, Antigravity, and web/mobile clients—one shared, durable memory of who you are, what you prefer, and what you're actively building.

---

## Why Memware?

- **Automatic turn capture**: Stop-hook adapters record completed turns automatically in Claude Code, Codex, and Antigravity—persistence never relies on the model "remembering" to call a tool.
- **Cross-agent task handoff (`memory_resume`)**: Start designing in Claude Code, switch to Codex to implement, and continue on mobile web without repeating context.
- **14 MCP Memory Tools**: `memory_status`, `memory_warmup`, `memory_get_context`, `memory_profile`, `memory_remember`, `memory_threads`, `memory_process`, `memory_search`, `memory_list`, `memory_update`, `memory_delete`, `memory_resume`, `memory_archive`, `memory_reset`.
- **Two deployment tracks**:
  - **Memware Cloud** ([aiware.life](https://aiware.life)) — Zero-config managed extraction & embeddings, Remote MCP (`https://mcp.aiware.life/mcp`), multi-device sync, visual memory dashboard, and on-the-go personal agent chat.
  - **Memware Local** — Self-contained single-file binary (`darwin-arm64`, `linux-x64`, `windows-x64`) with local SQLite storage and Bring-Your-Own-Key (BYOK).

---

## Repository Contents

This public repository hosts Memware's **distribution artifacts, agent configuration templates, release notes, and public issue tracker**:

- [`templates/claude-settings-hooks.json`](templates/claude-settings-hooks.json) — Claude Code Stop-hook configuration
- [`templates/codex-hooks.json`](templates/codex-hooks.json) — Codex CLI Stop-hook configuration
- [`templates/claude-md-snippet.md`](templates/claude-md-snippet.md) — `CLAUDE.md` recall instructions
- [`templates/agents-md-snippet.md`](templates/agents-md-snippet.md) — `AGENTS.md` / `.cursorrules` recall & handoff instructions

---

## Support & Feedback

- **Website & Dashboard**: [https://aiware.life](https://aiware.life)
- **Bug Reports & Feature Requests**: [GitHub Issues](https://github.com/HackSing/memware-mcp/issues/new/choose)
- **Community & Showcases**: [GitHub Discussions](https://github.com/HackSing/memware-mcp/discussions)
- **Security Advisories**: See [SECURITY.md](SECURITY.md)

Copyright (c) 2026 Memware ([aiware.life](https://aiware.life)). All rights reserved.
