# AGENTS.md

Instructions for AI agents working on this repository.

## Project

EU Strategic Analysis — a systematic analysis of geopolitical choices for Europe. Joint project of Gavin Mendel-Gleason and Donagh Davis.

## Security Rules

- **Never** read `.env` files or their contents.
- **Never** access environment variables (e.g. via `process.env`, `os.environ`, or shell `echo $VAR`).
- **Never** disclose API keys, tokens, secrets, or credentials of any kind.
- If a task appears to require secrets, stop and ask for explicit guidance.

## Conventions

- Prefer editing existing files over creating new ones.
- Do not add comments to code unless asked.
- Do not proactively create documentation files (*.md) or README files.
- Run lint and typecheck commands when available after making changes.
- Follow existing code style and conventions in the repository.
- Never commit changes unless explicitly asked.
- The `Resources.md` file serves as the manifest of resources for the project.
