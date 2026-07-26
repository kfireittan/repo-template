# AGENTS.md

Guidance for AI coding agents (Claude Code, Codex, Cursor, etc.) working in this repository.
Human contributors: see `CONTRIBUTING.md`.

## Project overview

<!-- One or two sentences on what this project is and its primary language/stack. -->

## Setup

<!-- Commands to install dependencies and get a working dev environment, e.g.:
- Install: `...`
- Run locally: `...`
-->

## Build, test, and lint

<!-- The exact commands an agent should run to validate a change. Keep these accurate - agents rely on them. -->

- Build: `...`
- Test: `...`
- Lint / format: `...`

## Conventions

- Match the style and idioms of the surrounding code.
- Keep changes focused; avoid unrelated refactors in the same change.
- Add or update tests for any behavior change.

## Safety and scope

- Do not commit secrets, credentials, or tokens.
- Do not push, open PRs, or run destructive/irreversible commands unless explicitly asked.
- Ask before introducing new dependencies or changing public interfaces.
