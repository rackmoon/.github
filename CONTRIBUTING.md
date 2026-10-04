# Contributing to RackMoon

Thanks for your interest in RackMoon. The project is in its early design stage, so the most useful contributions right now are feedback, real use cases and questions.

## Before you start

- **Small fixes** such as typos, docs or obvious bugs: open a pull request directly.
- **Larger changes** such as new features, provider plugins or API changes: open an issue first, so we agree on the approach before you spend time on code.
- **Security issues**: do not open a public issue. Follow the [security policy](SECURITY.md).

## Pull requests

1. Fork the repository and branch from `main`, using a name like `feat/short-description` or `fix/short-description`.
2. Keep each pull request focused on one change.
3. Add or update tests and docs for what you change.
4. Make sure the project builds and all tests pass.
5. Fill in the pull request template: what changed, why, and how to verify it.

## Commit messages

We follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/):

```
<type>(<scope>): <subject>
```

- `type` is one of `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`, `perf`, `ci` or `revert`.
- `subject` is lowercase and imperative, at most 50 characters, with no period at the end.
- The body, when needed, explains why rather than what.

Examples:

```
feat(billing): add per-second usage pricing
fix(provider): retry provisioning after a timeout
```

## Code and docs

- Write code comments, commit messages and pull request descriptions in English.
- Comment on why the code does something, not on what it does.
- User-facing docs may be bilingual, in English and Chinese.

## License

By contributing, you agree that your contributions are licensed under the license of the repository you contribute to.
