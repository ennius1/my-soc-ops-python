# Project Guidelines

## Mandatory Development Checklist
Agents MUST run these commands to verify changes:
- [ ] **Lint**: uv run ruff check .
- [ ] **Test**: uv run pytest
- [ ] **Run**: uv run uvicorn app.main:app --reload --host 0.0.0.0 --port 8000

## Architecture
**Soc Ops**: Python (FastAPI + Jinja2 + HTMX) Social Bingo.
- pp/main.py (routes), pp/templates/ (UI), 	ests/ (suite).

## Conventions
- **Code/HTMX**: Strict typing. Prefer returning small Jinja2 fragments over full page reloads.
- **Design/CSS**: Unique UI with custom utility classes. See .github/instructions/css-utilities.instructions.md & rontend-design.instructions.md.
- **Preview Restriction**: NO VS Code Simple Browser. See .github/instructions/general.instructions.md.
