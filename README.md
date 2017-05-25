#  Node.js `.files` (dotfiles)
> :computer: Run-commands, configurations, checklists, templates, labels, and other stuff I'm constantly copying from one repo to another (till I consolidate into a custom generator or something :triumph:).

[![License][license-badge]][license-url]

## 1. Table of contents
<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [1. Table of contents](#1-table-of-contents)
- [2. Legend](#2-legend)
- [3. GitHub](#3-github)
	- [3.1. Repository generators](#31-repository-generators)
	- [3.2. Issue templates](#32-issue-templates)
	- [3.3. Contribution guidelines](#33-contribution-guidelines)
	- [3.4. Issue labels](#34-issue-labels)
- [3.5. Commit messages and `CHANGELOG`](#35-commit-messages-and-changelog)
- [4. Documentation](#4-documentation)
	- [4.1. `README` tools](#41-readme-tools)
	- [4.2. API docs](#42-api-docs)
- [5. Licenses](#5-licenses)

<!-- /TOC -->
## 2. Legend

The following emojis represent resource categories. Hopefully they're helpful for scanning.

| Emoji | Definition |
|:-----:|:-----------|
| :name_badge: | Badges |
| :construction: | Build tools and services |
| :twisted_rightwards_arrows: | CD (automated **C**ontinuous **D**eployment services) |
| :repeat: | CI (automated **C**ontinuous **I**ntegration services) |
| :rocket: | Deployment relata |
| :page_facing_up: | Docs; templates; configs; files |
| :octocat: | GitHub relata |
| 🏷️    | Issue labels |
| :copyright: | Licensing tools and info |
| :chart_with_upwards_trend: | Report generators and tools |
| :zap: | Source code; executables |
| :100: | Test automation (unit, functional, perf.) |

## 3. GitHub

> :octocat: Software configuration management aids.

### 3.1. Repository generators

:name_badge: :construction: :page_facing_up: :octocat: :copyright: :zap: [`generator-github-create`][generator-github-create-url] - Yeoman generator for GitHub authentication; repository creation; README Badges; local git initialization; and local commits and pushes.

### 3.2. Issue templates

> :octocat: Add these files to a `.github` directory at the root of your repository and GitHub will automatically use them as issue and pull request templates.

* :page_facing_up: [`/.github/ISSUE_TEMPLATE.md`][issue-template-url] - A standard template notes to guide reporters.
* :page_facing_up: [`/.github/PULL_REQUEST_TEMPLATE.md`][pr-template-url] - A simple PR template focused on quality assurance, security, and dependency drift.

### 3.3. Contribution guidelines

* :page_facing_up: [`/.github/CODE_OF_CONDUCT.md`][coc-url] - Contributor covenant code of conduct.
* :page_facing_up: [`/.github/CONTRIBUTING.md`][contributing-url] - Succinct yet detailed guidelines centered on Issues and Pull Requests.

### 3.4. Issue labels

* 🏷️  [`.git-labels`][git-labels-url] - A common set of Issue labels for unambiguous, consistent issue categorization.

## 3.5. Commit messages and `CHANGELOG`

* :zap: [`commitplease`][commitplease-url] - Pre-commit hook that enforces the [AngularJS commit guidelines][angularjs-commit-guidelines-url].
* :twisted_rightwards_arrows: :octocat: :rocket: :zap: [`semantic-release`][semantic-release-url] - Fully automated package publishing.
* :repeat: :octocat: :zap: [`standard-version`][standard-version-url] - Automatic versioning and `CHANGELOG.md` generation, using GitHub's squash button and [conventional commit messages][conventional-commits-url].

## 4. Documentation

> :page_facing_up: A well-documented software product often enjoys greater adoption that a similar product with higher quality and more features.

### 4.1. `README` tools

> `README.md` is your repository's "home" page.

* :name_badge: :construction: :page_facing_up: :octocat: :copyright: :zap: [`generator-github-create`][generator-github-create-url] - Yeoman generator for GitHub authentication; repository creation; README Badges; local git initialization; and local commits and pushes.
* :page_facing_up: [`emoji cheat sheet`][emoji-cheat-sheet-url] - Emojis add meaning and flavor to your communications (when used judiciously).
* :page_facing_up: [GitHub Flavored Markdown cheatsheet][gh-flavored-md-cheatsheet-url] - Gist with simple examples for easy reference.
* :page_facing_up: [Mastering Markdown • GitHub Guide][mastering-md-gh-guide-url] - Learn GitHub's markdown syntax in three minutes.
* :name_badge: :repeat: :chart_with_upwards_trend: [`ScoreMe`][score-me-url] - Generates a `README` documentation quality scores (0-100) and badges. (Used as part of [`CocoaPods`' Quality Index calculations][cocoapods-qa-indexes-url] for Pods.)

### 4.2. API docs

* :page_facing_up: :zap: [`JSDoc`][jsdoc-url] - The de-facto API documentation generator for Javascript.
* :page_facing_up: :zap: [`jsdoc-to-markdown`][jsdoc-to-markdown-url] - Creates markdown API documentation from `JSDoc`-annotated Javascript.<br>
> **:repeat: Tip**: generate `JSDoc` markdown with every push and commit the docs to your GitHub repository's Wiki for API doc automation!

* :name_badge: :page_facing_up: :chart_with_upwards_trend: :zap: [`ESDoc`][esdoc-url] - Automated API documentation tool with available hosting services, linting, and coverage reports. 

## 5. Licenses

> :copyright: The open source community's freedom to innovate and share depends on social and legal contracts.

* :copyright: :page_facing_up: [`Choose a Creative Commons license`][choose-ccl-url] - Media license guidance.
* :copyright: :page_facing_up: [`Choose an open source license`][choose-osl-url] - Software license guidance.
* :copyright: :zap: [`generator-license`][generator-license-url] - Generate a LICENSE file for your project using Yeoman.
* :copyright: :zap: [`generator-license-cc`][generator-license-cc-url] - Generate a Creative Commons LICENSE for your Creative Work.
* :copyright: :page_facing_up: [`Open Source Initiative: FAQ`][osi-faq-url] - Frequently asked questions about open source licensing.

---

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a> This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

2017, [Greg Swindle][author-url].

[angularjs-commit-guidelines-url]: https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#commit
[author-url]: https://github.com/gregswindle
[choose-ccl-url]: https://creativecommons.org/share-your-work/
[choose-osl-url]: https://choosealicense.com
[coc-url]: .github/CODE_OF_CONDUCT.md
[cocoapods-qa-indexes-url]: https://guides.cocoapods.org/making/quality-indexes.html
[commitplease-url]: https://github.com/jzaefferer/commitplease
[contributing-url]: .github/CONTRIBUTING.md
[conventional-commits-url]: https://conventionalcommits.org/
[emoji-cheat-sheet-url]: https://www.webpagefx.com/tools/emoji-cheat-sheet/
[esdoc-url]: https://esdoc.org/manual/usage/feature.html
[generator-github-create-url]: https://github.com/trainerbill/generator-github-create
[generator-license-cc-url]: https://github.com/ek9/generator-license-cc
[generator-license-url]: https://github.com/jozefizso/generator-license
[gh-flavored-md-cheatsheet-url]: https://gist.github.com/stevenyap/7038119
[git-labels-url]: .git-labels/README.md
[issue-template-url]: .github/ISSUE_TEMPLATE.md
[jsdoc-to-markdown-url]: https://github.com/jsdoc2md/jsdoc-to-markdown
[jsdoc-url]: http://usejsdoc.org
[license-badge]: https://i.creativecommons.org/l/by-sa/4.0/80x15.png
[license-url]: ./LICENSE
[mastering-md-gh-guide-url]: https://guides.github.com/features/mastering-markdown/
[nodejs-new-pantone-white-img]: assets/img/nodejs-new-pantone-white.png
[osi-faq-url]: https://opensource.org/faq
[pr-template-url]: .github/PULL_REQUEST_TEMPLATE.md
[score-me-url]: http://clayallsopp.github.io/readme-score/?url=https://github.com/gregswindle/dotfiles
[semantic-release-url]: https://github.com/semantic-release/semantic-release
[standard-version-url]: https://github.com/conventional-changelog/standard-version
