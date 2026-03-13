This is a python app

## Project Structure

- `src/retirement/` — package source code
- `tests/` — pytest tests

## Commands

- Run tests: `uv run pytest`
- Lint: `uv run ruff check`
- Format: `uv run ruff format`
- Install pre-commit hooks: `uv run pre-commit install`

## Tooling

- **uv** — package and project manager
- **pytest** — test framework
- **ruff** — linter and formatter
- **pre-commit** — runs ruff and pytest before each commit
- **GitHub Actions** — CI runs ruff and pytest on push/PR to main
