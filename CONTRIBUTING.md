# Contributing

Thanks for your interest! This is an archived school project, kept as a portfolio piece: small fixes and improvements are welcome, large rewrites are not the goal.

## Prerequisites

- Python 3.11 and Jupyter.
- The call datasets (`calls_a1.csv` … `calls_a4.csv`) are confidential and not part of the repository: without them the notebooks cannot be re-executed.

## Build and run

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt jupyter
jupyter notebook src/
```

## Workflow

1. Open an issue first for anything beyond a small fix.
2. Create a branch from `main` named `type/short-topic` (`fix/…`, `feat/…`, `docs/…`, `chore/…`).
3. Write commits following [Conventional Commits](https://www.conventionalcommits.org/) (`type(scope): description`), the body explaining *why*.
4. Open a pull request using the template; the CI must be green.
5. Pull requests are merged with **squash and merge**.

## Versioning

The project follows [Semantic Versioning](https://semver.org/). Record user-visible changes under `## [Unreleased]` in [CHANGELOG.md](CHANGELOG.md). A release is published by pushing a `vX.Y.Z` tag on `main`: the Release workflow creates the GitHub Release from the matching CHANGELOG section.

## Rules

- Never commit secrets, credentials or personal data.
- By contributing, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md) and that your contribution is licensed under the [MIT License](LICENSE).
