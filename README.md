# startup

A combined Antigravity skill library — ~540 agent skills spanning engineering, product, marketing, sales, design, and executive/C-suite roles, built for use inside [Google Antigravity](https://antigravity.google/).

## What's in here

`.agents/skills/` — one folder per skill, each with its own `SKILL.md`. Sourced and merged from two libraries:

- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) — broad cross-functional skill library (engineering, product, marketing, C-suite advisory, compliance, security)
- [andywxy1/ceo-plugin](https://github.com/andywxy1/ceo-plugin) — role-based agent personas across engineering, marketing, sales, design, and strategy

Skills were converted and merged into a single flat structure (`.agents/skills/<skill-name>/SKILL.md`) so Antigravity can load them all from one project.

## Usage

1. Clone this repo.
2. Open the folder in Antigravity.
3. Ask it directly: `what skills are available?` — Antigravity auto-loads relevant skills based on task context.

## Note

Source repos were audited for hidden/malicious content using claude-skills' built-in `skill-security-auditor` before merging. The original source repos aren't included here — only the extracted, converted skills.
