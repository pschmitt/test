# Agent guidance

This repository is a small test/sample repository with documentation and a GPG artifact; no application build system is present.

## Development

- Do not inspect, decrypt, export, or replace cryptographic artifacts unless the task explicitly requires it.
- Keep any added examples synthetic and free of secrets or private infrastructure identifiers.

## CI

- Before changing GitHub Actions, inspect the current guidance in `pschmitt/ci-workflows`. Use `@main` in every `uses:` reference to a shared workflow or action.
