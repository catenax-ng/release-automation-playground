# Release automation playground

This reposiory contains experiments for automatic GitHub release creation.
There are examples for different automation tools and project languages.

## Release please appraoch

This repos release pipeline uses the [release-please-action](https://github.com/google-github-actions/release-please-action).
It is based on [release-please](https://github.com/googleapis/release-please) and uses Pull Requests to prepare new GitHub releases.
You need to follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), so release please can create proper `CHANGELOG.md` files.

## Building documentation

Check out [the release workflow from line 23-36](.github/workflows/release.yaml#L23-36) to see an example on how to build a PDF of your .md docs and
upload it as release artifact
