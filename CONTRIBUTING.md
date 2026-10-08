# Contributing to OpenMeshTak

Thank you for helping. This guide applies to every OpenMeshTak repository that has no
`CONTRIBUTING.md` of its own.

## Before you start

- Read the [documentation](https://openmeshtak.github.io/openmeshtak-docs/) for how OpenMeshTak
  is meant to work.
- For anything larger than a small fix, open an issue first so we can agree on the approach.
- Report security problems privately, as described in [SECURITY.md](SECURITY.md).

## Pull requests

- Keep one pull request to one change.
- Write commit messages as [Conventional Commits](https://www.conventionalcommits.org/), for
  example `fix(api): reject empty callsigns`.
- Run the repository's checks before you open the pull request; its README names them.
- Add or update tests for changed behavior.
- Never commit real certificates, private keys, Meshtastic PSKs, API keys or personal data.

## Compatibility

TAK, iTAK and Meshtastic compatibility is only claimed after a test with the real client. Describe
the app or firmware version you tested with in your pull request.
