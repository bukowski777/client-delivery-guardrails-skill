# Repository Agent Instructions

This repository contains the reusable `client-delivery` Agent Skill for Codex and Claude Code. When editing it, optimize for clear operational behavior rather than narrative history.

## Editing Rules

- Keep `client-delivery/SKILL.md` compact and high-signal.
- Put detailed procedures in `client-delivery/references/`.
- Put reusable output structures in `client-delivery/templates/`.
- Do not add client names, private URLs, secrets, screenshots, production credentials, or private infrastructure procedures.
- Prefer checklists, decision gates, and copy-safe commands over long explanations.
- Keep examples generic and anonymized.

## Validation

Run before proposing changes:

```bash
bash scripts/validate-skill.sh
```

For install changes, also run:

```bash
bash -n install.sh scripts/validate-skill.sh
./install.sh --dry-run
```
