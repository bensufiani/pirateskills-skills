# Pirate Skills for AI agents

[Pirate Skills](https://pirateskills.com) teaches growth marketing and vibe coding to founders and marketers – two free codices, free monthly events in Cologne and online, and two monthly passes with a live 12-week cohort.

This repo brings Pirate Skills into your AI assistant or coding agent: a skill that teaches the agent how to use Pirate Skills, and the address of the Pirate Skills MCP server.

## Install

**Any agent with the skills CLI** (Claude Code, Cursor, Codex, Copilot, Windsurf, Gemini, …):

```
npx skills add bensufiani/pirateskills-skills
```

**Claude Code, as a plugin** (skill and MCP server together):

```
/plugin marketplace add bensufiani/pirateskills-skills
/plugin install pirateskills@pirateskills
```

**Just the MCP server:**

```
claude mcp add --transport http --scope user pirateskills https://pirateskills.com/mcp
codex mcp add pirateskills --url https://pirateskills.com/mcp
```

Claude.ai, Claude Desktop, ChatGPT and Cursor: step by step at [pirateskills.com/agents](https://pirateskills.com/agents).

## What your agent can do

- **Without an account:** search the Growth Codex, the Builder Codex and the Insights; list upcoming events; show the passes and their prices.
- **Once you sign in** (your agent asks first): register you for a free event, show your access and gold wallet, book a call with Ben, start a checkout – you always pay on Stripe's own page; no agent ever charges a card.

## What's in here

| Path | What it is |
|---|---|
| `skills/pirateskills/SKILL.md` | The skill – the same file as [pirateskills.com/skills/pirateskills/SKILL.md](https://pirateskills.com/skills/pirateskills/SKILL.md) |
| `.claude-plugin/` | The Claude Code plugin and marketplace manifests |
| `.mcp.json`, `.cursor/mcp.json` | The MCP server, for Claude Code and Cursor |
| `AGENTS.md` | Short rules for an agent using Pirate Skills |

## Docs

- [Docs](https://pirateskills.com/docs) – the MCP server, the HTTP API, the CLI, every tool ([as Markdown](https://pirateskills.com/docs.md))
- [llms.txt](https://pirateskills.com/llms.txt) · [Prices](https://pirateskills.com/pricing.md) · [Sign-in for agents](https://pirateskills.com/auth.md)
- MCP registry: `com.pirateskills/pirateskills` · CLI: [`npm install -g pirateskills`](https://www.npmjs.com/package/pirateskills)

Questions: contact@pirateskills.com · MIT licensed · © Pirate Skills GmbH
