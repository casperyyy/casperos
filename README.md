# Casper OS

Personal task operating system for Casper Yang — powered by Claude Code, ClickUp, Notion, Gmail, and automation agents.

## Architecture

```
Casper OS
├── Claude Code          — AI command center
├── ClickUp              — Task management (MCP connected)
├── Notion               — Knowledge base (MCP connected)
├── Gmail                — Communication (MCP connected)
├── GitHub Actions       — Scheduled automations
├── gstack               — Browser QA & testing
└── agents marketplace   — Reusable agent templates
```

## Getting Started

1. Clone this repo
2. Ensure Claude Code is configured with MCP servers (ClickUp, Notion, Gmail)
3. Install gstack: `claude mcp add gstack -- npx -y @anthropic-ai/gstack@latest`
4. Run skills via `/` commands in Claude Code

## Project Structure

```
casperos/
├── README.md
├── CLAUDE.md             — Claude Code project instructions
├── .github/
│   └── workflows/        — GitHub Actions automations
├── agents/               — Custom agent definitions
├── skills/               — Custom skill files
├── templates/            — Reusable templates
└── docs/                 — Documentation
```

## Owner

Casper Yang (CasperYYYY) — Calgary, AB
