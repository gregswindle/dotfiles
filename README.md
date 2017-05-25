# `.files` (dotfiles)
> :page_facing_up: run-commands, configurations, checklists, templates, labels, and other stuff I'm constantly copying from one repo to another (till I consolidate into a custom generator or something :triumph:).

## 1. Table of contents
<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [1. Table of contents](#1-table-of-contents)
- [2. GitHub](#2-github)
	- [2.1. Issue templates](#21-issue-templates)
	- [2.2. Contribution guidelines](#22-contribution-guidelines)
	- [2.3. Issue labels](#23-issue-labels)
	- [2.4. Commit messages and CHANGELOGs](#24-commit-messages-and-changelogs)
- [3. License](#3-license)

<!-- /TOC -->

## 2. GitHub

Software configuration management aids.

### 2.1. Issue templates

* [`ISSUE_TEMPLATE.md`][issue-template-url] - A standard template notes to guide reporters.
* [`PULL_REQUEST_TEMPLATE.md`][pr-template-url] - A simple PR template focused on quality assurance, security, and dependency drift.

### 2.2. Contribution guidelines

* [`CODE_OF_CONDUCT.md`][coc-url] - Contributor covenant code of conduct.
* [`CONTRIBUTING.md`][contributing-url] - Succinct yet detailed guidelines centered on Issues and Pull Requests.

### 2.3. Issue labels

* [`.git-labels`][git-labels-url] - A common set of Issue labels for unambiguous, consistent issue categorization.

### 2.4. Commit messages and CHANGELOGs

* [`commitplease`][commitplease-url] - Pre-commit hook that enforces the [AngularJS commit guidelines][angularjs-commit-guidelines-url].
* [`standard-version`][standard-version-url] - Automatic versioning and CHANGELOG generation, using GitHub's squash button and [conventional commit messages][conventional-commits-url].
* [`semantic-release`][semantic-release-url] - Fully automated package publishing.

## 3. License

[![License][license-badge]][license-url]  © 2017 Greg Swindle

[angularjs-commit-guidelines-url]: https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#commit
[coc-url]: .github/CODE_OF_CONDUCT.md
[commitplease-url]: https://github.com/jzaefferer/commitplease
[contributing-url]: .github/CONTRIBUTING.md
[conventional-commits-url]: https://conventionalcommits.org/
[git-labels-url]: .git-labels/README.md
[issue-template-url]: .github/ISSUE_TEMPLATE.md
[license-badge]: https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square
[license-url]: ./LICENSE
[pr-template-url]: .github/PULL_REQUEST_TEMPLATE.md
[semantic-release-url]: https://github.com/semantic-release/semantic-release
[standard-version-url]: https://github.com/conventional-changelog/standard-version
