# makke-skills

Collection of open-source AI agent skills (compatible with Claude Code, DSH / DeepSeek Harness, OpenClaw-style runtimes).
Each skill is a self-contained folder with a `SKILL.md` entry file and optional `references/` loaded on demand.

## Skills

| Skill | Status | Install |
|---|---|---|
| [makke-dsh-lan](https://github.com/theorangee-makke/makke-dsh-lan) | ✅ Released | `git clone https://github.com/theorangee-makke/makke-dsh-lan.git ~/.dsh/skills/makke-dsh-lan` |

<!-- Template for the next skill:
| <name> | 🚧 WIP | `git clone ... ~/.dsh/skills/<name>` |
-->

## Conventions

- One skill per repository (allows independent versioning/tags); this repo is the index.
- `SKILL.md` frontmatter: `name` + `description` with trigger words (中英双语).
- Progressive disclosure: main file ≤ 500 lines, deep detail in `references/*.md`.
- Personal/infra-specific values are sanitized to placeholders before publishing.
