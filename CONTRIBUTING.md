# Contributing

Thank you for your interest in contributing.

## How to Contribute

1. Fork the repository and create a feature branch from `main`.
2. Keep changes scoped and focused on one improvement.
3. Update documentation when behavior or configuration changes.
4. Open a pull request with a clear summary and validation notes.

## Pull Request Expectations

- Keep pipeline logic secure and avoid hardcoded credentials.
- Use secret references (`secrets.*`, variable groups, or environment variables).
- Preserve multi-stage promotion flow (Dev -> Test -> Production).
- Ensure quality gates remain enforced before promotions.

## Validation Checklist

Before submitting a PR, verify:

1. YAML syntax is valid.
2. Stage/job dependencies are correct.
3. Security-sensitive values are not committed.
4. Any new required variables are documented in the PR.

## Code of Conduct

Please be respectful and constructive in reviews and discussions.
