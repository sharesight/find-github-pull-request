# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
 - [#231](https://github.com/sharesight/find-github-pull-request/pull/231) - Bump tough-cookie from 4.0.0 to 4.1.3
 - [#233](https://github.com/sharesight/find-github-pull-request/pull/233) - Bump semver from 6.3.0 to 6.3.1
 - [#235](https://github.com/sharesight/find-github-pull-request/pull/235) - Bump word-wrap from 1.2.3 to 1.2.4
 - [#243](https://github.com/sharesight/find-github-pull-request/pull/243) - Bump @types/node from 17.0.33 to 20.5.1

## [1.2.0] - 2023-02-09

 - [#200](https://github.com/sharesight/find-github-pull-request/pull/200) - Several dependency upgrades including Github actions, which deprecates Node 12 actions.

## [1.1.2] - 2022-03-14

 - [#101](https://github.com/sharesight/find-github-pull-request/pull/101) - Fetch the PR for an eventName of 'workflow_run'

## [1.1.1] - 2022-03-09

 - [#98](https://github.com/sharesight/find-github-pull-request/pull/98) - Fetch the PR with the correct `repo.owner`, `repo.repo`…not hardcoded to the documentation example.
 - [#99](https://github.com/sharesight/find-github-pull-request/pull/99) - Run `yarn jest` while building.

## [1.1.0] - 2022-03-09

 - [#95](https://github.com/sharesight/find-github-pull-request/pull/96) & [#96](https://github.com/sharesight/find-github-pull-request/pull/96) = Returning new outputs: `base-ref` and `base-sha`.
    - This required additional functionality to fetch a full `pull_request` object via API, meaning `inputs.token` is now required.

## [1.0.1] - 2021-12-21

- Added Dependabot
- Additional CI improvements
- Lots of dependency upgrades

## [1.0.0] - 2021-09-07

Basically the initial working release.

**PRs:**

- [#2](https://github.com/sharesight/find-github-pull-request/pull/2)
- [#3](https://github.com/sharesight/find-github-pull-request/pull/3)
- [#4](https://github.com/sharesight/find-github-pull-request/pull/4)
- [#5](https://github.com/sharesight/find-github-pull-request/pull/5)
- [#6](https://github.com/sharesight/find-github-pull-request/pull/6)

#### [0.0.1] – [0.0.4] - 2021-09-06

Tinkering and initial working release.
