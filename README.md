# sdd-claude-template

A [Copier](https://copier.readthedocs.io/) template for bootstrapping new projects with a shared Claude Code + OpenSpec workflow setup: `.claude/` agents, skills, and commands, a `CLAUDE.md` with baseline conventions, and an intent-driven OpenSpec schema.

## Use this template

```bash
copier copy gh:cemalcici/sdd-claude-template <destination>
```

You'll be prompted for:

| Variable        | Purpose                                   | Default       |
|------------------|--------------------------------------------|---------------|
| `project_name`   | Used as the generated project's README title | *(required)*  |
| `author_name`    | Copyright holder in `LICENSE`              | `Cemal Cici`  |
| `year`           | Copyright year in `LICENSE`                | `2026`        |

## Update a project generated from this template

Copier records your answers in `.copier-answers.yml` inside the generated project. To pull in template changes later, run this from inside that project:

```bash
copier update
```

## What's included

Everything under [`template/`](template/) is copied into the new project: `.claude/` (agents, skills, commands), `CLAUDE.md`, `openspec/` (intent-driven schema + config), `.gitignore`, `README.md`, and `LICENSE`.
