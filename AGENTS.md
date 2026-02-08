# Repository Guidelines

## Project Structure & Module Organization
- `skills/`: Each skill lives in its own folder with `SKILL.md` and optional `references/`, `scripts/`, or `assets/`.
- `notes/`: Local scratch notes (ignored by git).
- Root files: `README.md`, `LICENSE`, `CHANGELOG.md`, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`.

## Build, Test, and Development Commands
There is no build or test system configured in this repository. Changes are primarily documentation edits.
- Example check: `rg -n "SmartThings" README.md` to verify content updates.
- Example validation: `rg -n "MIT|Apache" README.md CONTRIBUTING.md LICENSE` to confirm licensing text is consistent.

## Coding Style & Naming Conventions
- Markdown only; keep sections concise and task-focused.
- Use sentence case for prose, Title Case for section headings.
- Use backticks for file paths and commands (e.g., `skills/smartthings-api`).
- Skill names are kebab-case folder names (e.g., `smartthings-edge-driver`).

## Testing Guidelines
No automated tests. If you add scripts in `skills/*/scripts/`, document how to run them in the corresponding `SKILL.md`.

## Commit & Pull Request Guidelines
No enforced commit format is defined. Keep commit messages short and descriptive (e.g., “Update README badges”).
PRs should include:
- A clear summary of changes.
- Links to related issues if applicable.
- Updates to `CHANGELOG.md` when releasing.

## Agent-Specific Instructions
- `SKILL.md` should stay lean; large reference material belongs in `references/`.
- Prefer official SmartThings documentation links in `references/`.
- If adding new skills, follow the existing structure under `skills/`.
