# Contributing

Thank you for helping! Each repo in this org is one CircleCI function: a Go binary that
runs as a step in a CircleCI job.

## Reporting a bug

Check you're on the latest version, and search the repo's issues first. Then open an issue
with the bug report template.

To report a security problem, see [SECURITY.md](SECURITY.md). Please don't open a public
issue for it.

## Asking for a feature

Open an issue with the feature request template before you write the code, so we can agree
on the flags first. A function's flags are its interface, and changing them later breaks
pipelines.

## Opening a pull request

1. Fork the repo and branch from `main`.
2. Install [Go](https://go.dev/dl/) and [Task](https://taskfile.dev/installation/).
3. Run `task ci` before you push. It runs the same lint, tests and build as CI.
4. Write the PR title like a commit subject. It becomes the changelog entry.

CI doesn't run on pull requests from forks. A maintainer reviews the change, then pushes it
to a branch in the repo to run CI. Each PR needs one approval from
@circleci-functions/functions-maintainers.

Maintainers make releases. See the repo's `RELEASE.md`.

## Code of Conduct

Everyone taking part is expected to follow our [code of conduct](CODE_OF_CONDUCT.md).

## License

The functions are released under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
By contributing, you agree that your contributions are released under it too.
