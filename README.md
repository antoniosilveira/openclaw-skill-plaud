# OpenClaw Skill Plaud Note Taking

An OpenClaw skill for Plaud note taking workflows through Plaud MCP and the Plaud CLI.

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

Install from ClawHub:

```bash
clawhub install plaud
```

Or inspect it first:

```bash
clawhub inspect plaud
```

Manual install:

```bash
git clone https://github.com/antoniosilveira/openclaw-skill-plaud-note-taking.git plaud
```

Then place the `plaud` folder in your OpenClaw skills directory or install it through your preferred OpenClaw skill workflow.

The skill folder is the repository root. The required skill file is `SKILL.md`.

## ClawHub

This skill is currently published on ClawHub as `plaud`.

- Install: `clawhub install plaud`
- Inspect: `clawhub inspect plaud`
- Update: `clawhub update plaud`

Note: ClawHub reserves the `openclaw-` slug namespace, so `openclaw-skill-plaud-note-taking` cannot be used as the ClawHub slug unless the registry grants access to that namespace.

## Helpful links

- [Plaud website](https://www.plaud.ai/)
- [Plaud MCP documentation](https://docs.plaud.ai/documentation/plaud_app/mcp)
- [Plaud CLI documentation](https://docs.plaud.ai/documentation/plaud_app/cli)
- [Plaud documentation index](https://docs.plaud.ai/llms.txt)

## License

MIT-0
