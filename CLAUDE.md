# CLAUDE.md

This file provides guidance for AI assistants working in this repository.

## Repository Overview

This is a **GitHub profile repository** (`pollo3198/pollo3198`). Its sole purpose is to display a custom README on the owner's GitHub profile page at github.com/pollo3198. The `README.md` in the root is automatically rendered by GitHub as the profile landing page.

## Repository Structure

```
pollo3198/
└── README.md   # GitHub profile page — the only file that matters
```

There is no build system, no dependencies, no tests, and no application code.

## Owner Context

- **Name:** Pollo
- **Role:** Motion designer, cofounder and director at Verso Studio (https://versostudio.es/)
- **Self-described:** amateur coder

## Development Guidelines

### Editing the Profile

The only file to edit is `README.md`. Changes here are immediately reflected on the GitHub profile once merged to `main`.

**Conventions:**
- Keep the tone personal and approachable — this is a public-facing personal page.
- Markdown is rendered by GitHub; standard GitHub Flavored Markdown (GFM) is supported.
- HTML is allowed within the README for advanced layouts (badges, centering, etc.).
- Avoid adding files that aren't relevant to the profile presentation.

### Branch Workflow

- Default branch: `main`
- Feature branches: use descriptive names (e.g. `claude/add-claude-documentation-tlkP9`)
- Changes go through feature branches → PR → merge to `main`

### What AI Assistants Should (and Should Not) Do

**Do:**
- Edit `README.md` to update profile content, add sections, or improve formatting.
- Add standard GitHub profile enhancements (badges, stats cards, etc.) when requested.
- Create a CLAUDE.md if asked (this file).

**Do not:**
- Add application code, build systems, CI/CD pipelines, or dependencies unless explicitly requested.
- Create extra files unless there is a clear reason for them.
- Change the personal voice or factual details about the owner without direction.

## Git Workflow

```bash
# Make changes, then:
git add README.md
git commit -m "descriptive message"
git push -u origin <branch-name>
```

No linting, formatting checks, or test suites need to be run — there is no code to validate.
