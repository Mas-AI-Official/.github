# Contributing

MAS-AI repositories use small, reviewable changes.

## Pull Request Rules

- Keep changes scoped to one purpose.
- Include tests or a clear reason tests are not applicable.
- Do not commit secrets, credentials, generated caches, local browser profiles, or private company data.
- Use GitHub Actions with least-privilege permissions.
- Prefer squash merges for feature branches.

## Local Checks

Run the relevant stack checks before opening a PR:

- Node/Next.js: `npm ci`, `npm run lint --if-present`, `npm test --if-present`, `npm run build --if-present`
- Python: install the project dependencies, then run `pytest` when tests exist

If a repo has a stricter local `AGENTS.md`, `CLAUDE.md`, or project README, follow that first.
