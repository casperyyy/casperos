# Casper OS — Claude Code Project Instructions

## Project Overview
Casper OS is a personal task operating system that orchestrates Claude Code, ClickUp, Notion, Gmail, and automation agents to manage Casper Yang's businesses and projects.

## Connected Services
- **ClickUp** — Task management (MCP connected, read/write)
- **Notion** — Knowledge base and docs (MCP connected)
- **Gmail** — Email triage and communication (MCP connected)
- **GitHub** — Code and automation (gh CLI)
- **Supabase** — Database backend (MCP connected)
- **Vercel** — Deployment platform (MCP connected)

## Key Workflows
- Daily task triage via ClickUp
- Email processing via Gmail MCP
- Knowledge capture in Notion
- Automated reporting via GitHub Actions

## Conventions
- All automation scripts go in `.github/workflows/`
- Agent definitions go in `agents/`
- Skill files go in `skills/`
- Use gstack `/browse` for all web browsing tasks
