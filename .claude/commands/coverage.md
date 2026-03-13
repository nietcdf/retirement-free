Run pytest with coverage and summarise uncovered lines.

First ensure pytest-cov is installed:
```
uv add --dev pytest-cov
```

Then run:
```
uv run pytest --cov=retirement --cov-report=term-missing
```

Report which lines lack coverage and suggest tests to add.
