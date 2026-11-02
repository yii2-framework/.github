# Contributing to yii2-framework

Thank you for your interest in contributing. Please read this guide before submitting issues or pull requests.

By participating in this project, you agree to abide by the [Code of Conduct](CODE_OF_CONDUCT.md).

## Before you start

Each repository documents its own requirements. Check the target repository's `README.md` and `composer.json` for:

- the supported PHP versions and dependencies,
- the test framework and the quality scripts to run (`composer run` lists them),
- the coding standard and any repository-specific rules.

Do not assume that every package shares the same PHP version, test framework or branch name.

## Reporting issues

- Use the issue forms of the affected repository. Provide a minimal reproduction, the expected and actual behavior and
  the package version.
- Do not open public issues for security vulnerabilities. See [SECURITY.md](SECURITY.md) for reporting instructions.

## Pull requests

1. Fork the repository and create a feature branch from its default branch.
2. Keep changes focused: one logical change per pull request.
3. Run the repository's test and quality scripts before submitting, and describe the checks you ran.
4. Preserve backward compatibility unless the change is explicitly intended to break it; document any behavior,
   configuration or dependency impact.
5. Use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for commit messages when the repository
   follows them.
