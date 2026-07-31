# Pravah CLI Agent Skill

Teaches compatible AI agents to safely inspect and manage tasks, goals, operations, and planning context through the Pravah CLI.

View the skill on [skills.sh](https://skills.sh/snehit70/pravah-cli-skill/pravah-cli).

## Install

Install it with the Agent Skills CLI:

```bash
npx skills add https://github.com/snehit70/pravah-cli-skill --skill pravah-cli
```

Or with Bun:

```bash
bunx skills add snehit70/pravah-cli-skill --skill pravah-cli
```

The skill expects the `pravah` command to be installed and authenticated. In a Pravah source checkout, agents can fall back to `bun run pravah -- <command>`.
