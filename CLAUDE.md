# CLAUDE.md — iknowkungfu

## What this is
OpenClaw skill published on ClawHub. Helps AI agents discover and understand available OpenClaw skills — a skill directory meta-skill. 103 real skills in catalogue.

## Stack
OpenClaw skill (SKILL.md + data files). No web app, no Next.js.

## Critical rules
- **Published on ClawHub** — breaking changes require a version bump and republish.
- **Semantic versioning** — MAJOR.MINOR.PATCH. Catalogue updates = minor version.
- **Catalogue accuracy** — skill entries must be real, verified OpenClaw skills. Never add fake or unverified skills to the catalogue.
- **103 skills in catalogue** as of v1.1.0 — sourced from awesome-openclaw-skills list.
- **One change, one version, one publish** — no rapid-fire versions.
- **Test before publishing** — verify locally before `openclaw skills publish`.
- **Paperclip project:** iknowkungfu (31e4fa6e-f7fe-4276-b006-4a02128ea6a9).
- **WHO-90** tracks ClawHub stats.

## Known gotchas
- ClawHub hourly rate limits on installs.
- `--name "Display Name"` required on CLI publish.
- Chinese README (简体中文) exists — if updating README, update both English and Chinese versions.
