# OpenClaw Plaud Skill

An OpenClaw skill for working with Plaud recordings through Plaud MCP and the Plaud CLI.

## What it helps agents do

- List recent Plaud recordings
- Find recordings by date or keyword
- Read transcripts and summaries
- Extract topics, decisions, speakers, and action items
- Draft follow-up notes from recordings
- Export summaries and transcripts
- Diagnose Plaud MCP or CLI authentication

## Requirements

- OpenClaw
- Node.js 20 or newer
- Plaud MCP configured, or Plaud CLI installed

## Plaud MCP setup

```bash
openclaw mcp set plaud '{"command":"npx","args":["-y","@plaud-ai/mcp@latest"]}'
```

Then authenticate through the Plaud MCP login flow.

## Plaud CLI setup

```bash
npm install -g @plaud-ai/cli@latest
plaud login
plaud me
```

## Skill install

Clone this repo into your OpenClaw skills directory or install it through your preferred OpenClaw skill workflow.

The skill folder is the repository root. The required skill file is `SKILL.md`.

## License

MIT
