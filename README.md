# There's a Tool for That

I got tired of telling agents to look for existing tools before every task, so I made this skill.

`find-tools` has your agent check for existing tools, libraries, services and AI skills before it builds something itself, and keeps it from giving up after one search.

## Install

Claude Code (one line at a time):

```text
/plugin marketplace add kwonzweig/there-is-a-tool-for-that
/plugin install find-tools@there-is-a-tool-for-that
```

Codex:

```bash
codex plugin marketplace add kwonzweig/there-is-a-tool-for-that
codex plugin add find-tools@there-is-a-tool-for-that
```

Other agents, with the [skills CLI](https://github.com/vercel-labs/skills):

```bash
npx skills add kwonzweig/there-is-a-tool-for-that
```

## What the agent does

1. Checks what you already have.
2. In an unfamiliar field, learns the current terms first and searches with them.
3. Reads the real docs or `SKILL.md` instead of trusting listings and star counts.
4. Picks one, or tells you what it searched and what it couldn't check. It doesn't claim "there's no tool for that" after one search.

It kicks in before unfamiliar or recurring work, or when you ask for a tool. If Vercel's [find-skills](https://github.com/vercel-labs/skills/tree/main/skills/find-skills) is installed, it uses that to search for skills.

The full instructions are in [SKILL.md](skills/find-tools/SKILL.md).

## License

MIT
