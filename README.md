# Dymexjs - Reusable workfows

[![Released under the MIT license.](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![All Contributors][all-contributors-badge]](#contributors-)
[![PRs welcome!](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](.github/CONTRIBUTING)
[![Code of Conduct][coc-badge]][coc]

A collection of reusable GitHub Actions workflows to be used by @dymexjs packages

## Table of Contents

- [Dymexjs - Reusable workfows](#dymexjs---reusable-workfows)
  - [Table of Contents](#table-of-contents)
  - [Usage](#usage)
  - [Workflows](#workflows)
    - [All Contributors](#all-contributors)
    - [Codacy Analisys and Coverage](#codacy-analisys-and-coverage)
    - [Dependency Review](#dependency-review)
    - [Lint PR](#lint-pr)
    - [Publish NPM](#publish-npm)
    - [Release Drafter](#release-drafter)
    - [Run Tests](#run-tests)
    - [Update Changelog](#update-changelog)
  - [Code of Conduct](#code-of-conduct)
  - [How to Contribute](#how-to-contribute)
  - [License 📝](#license-)
  - [Contributors ✨](#contributors-)

## Usage

Just call the choosen workflows from github actions

## Workflows

### All Contributors

> all-contributors.yml

Fills in missing allcontributors entries for a repository

Runs

- [All Contributors Auto Action](https://github.com/JoshuaKGoldberg/all-contributors-auto-action)

### Codacy Analisys and Coverage

> codacy-analysis.yml

GitHub Action for running Codacy static analysis on over 40 supported languages and returning identified issues in the code, and also to send coverage reports to codacy.

Runs

- [Codacy Analysis CLI GitHub Action](https://github.com/codacy/codacy-analysis-cli-action)
- [Codacy Coverage Reporter GitHub Action](https://github.com/codacy/codacy-coverage-reporter-action)

### Dependency Review

> dependency-review.yml

The dependency review action scans your pull requests for dependency changes, and will raise an error if any vulnerabilities or invalid licenses are being introduced.

Runs

- [dependency-review-action](https://github.com/actions/dependency-review-action/)

### Lint PR

> lint-pr.yml

GitHub Action that ensures that your pull request titles match the Conventional Commits spec. Typically, this is used in combination with a tool like semantic-release to automate releases

Runs

[action-semantic-pull-request](https://github.com/amannn/action-semantic-pull-request/)

### Publish NPM

> publish-npm.yml

Publish packages to npm automatically in GitHub Actions by updating the version number.

Runs

- [Fast, easy publishing to NPM](https://github.com/JS-DevTools/npm-publish/)
  
### Release Drafter

> release-drafter.yml

Drafts your next release notes as pull requests are merged into master

Runs

- [Release Drafter](https://github.com/release-drafter/release-drafter/)

*Notes:* You need a `release-drafter.yml` file in `.github/` to configure the action

### Run Tests

> run-tests.yml

This workflow runs the tests suites of the package in various node versions and SO's.

### Update Changelog

> update-changelog.yml

A GitHub Action to update a changelog with the latest release notes.
Also updates `package.json` version

Runs

- [github-action-package](https://github.com/jaywcjlove/github-action-package/)
- [changelog-updater Action](https://github.com/stefanzweifel/changelog-updater-action/)

## Code of Conduct

We expect everyone to abide by our [**Code of Conduct**](.github/CODE_OF_CONDUCT.md). Please read it.

## How to Contribute

Check out our [**Contributing Guide**](.github/CONTRIBUTING.md) for information on contributing.

## License 📝

Licensed under the [MIT License](./LICENSE).

## Contributors ✨

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

[all-contributors-badge]: https://img.shields.io/github/all-contributors/dymexjs/reusable_workflows?color=orange&style=flat-square
[coc]: .github/CODE_OF_CONDUCT.md
[coc-badge]: https://img.shields.io/badge/code%20of-conduct-ff69b4.svg?style=flat-square
