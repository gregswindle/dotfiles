# Contributing to `eslint-plugin-swagger`

:family: We warmly welcome contributors, and we follow the [Contributor Covenant Code of Conduct][code-of-conduct-url] for respectful and friendly interaction.

## 1. Table of contents
<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [1. Table of contents](#1-table-of-contents)
- [2. Contributions, issues, and pull requests](#2-contributions-issues-and-pull-requests)
- [3. Review open issues](#3-review-open-issues)
	- [3.1. Issue `Type` labels](#31-issue-type-labels)
		- [3.1.1. 🏷️  `Type: Build` label](#311-type-build-label)
		- [3.1.2. 🏷️  `Type: Chore` label](#312-type-chore-label)
		- [3.1.3. 🏷️  `Type: CI` (continuous-integration) label](#313-type-ci-continuous-integration-label)
		- [3.1.4. 🏷️  `Type: Defect` ("Bug") label](#314-type-defect-bug-label)
		- [3.1.5. 🏷️  `Type: Docs` label](#315-type-docs-label)
		- [3.1.6. 🏷️  `Type: Duplicate` label](#316-type-duplicate-label)
		- [3.1.7. 🏷️  `Type: Feature` label](#317-type-feature-label)
		- [3.1.8. 🏷️  `Type: Fix` label](#318-type-fix-label)
		- [3.1.9. 🏷️  `Type: Performance` label](#319-type-performance-label)
		- [3.1.10. 🏷️  `Type: Question` label](#3110-type-question-label)
		- [3.1.11. 🏷️  `Type: Refactor` label](#3111-type-refactor-label)
		- [3.1.12 🏷️  `Type: Revert` label](#3112-type-revert-label)
		- [3.1.13. 🏷️  `Type: Spike` label](#3113-type-spike-label)
		- [3.1.14. 🏷️  `Type: Style` label](#3114-type-style-label)
		- [3.1.15. 🏷️  `Type: Test` label](#3115-type-test-label)
	- [3.2. `Status` issue labels](#32-status-issue-labels)
		- [3.2.1 🏷️  `Status: Abandoned` label](#321-status-abandoned-label)
		- [3.2.2. 🏷️  `Status: Accepted` label](#322-status-accepted-label)
		- [3.2.3. 🏷️  `Status: Available` label](#323-status-available-label)
		- [3.2.4. 🏷️  `Status: Blocked` label](#324-status-blocked-label)
		- [3.2.5. 🏷️  `Status: Completed` label](#325-status-completed-label)
		- [3.2.6. 🏷️  `Status: In Progress` label](#326-status-in-progress-label)
		- [3.2.7. 🏷️  `Status: On Hold` label](#327-status-on-hold-label)
		- [3.2.8. 🏷️  `Status: Pending` label](#328-status-pending-label)
		- [3.2.9. 🏷️  `Status: Review Needed` label](#329-status-review-needed-label)
		- [3.2.10. 🏷️  `Status: Revision Needed` label](#3210-status-revision-needed-label)
		- [3.2.11. 🏷️  `Status: Won't Fix` label](#3211-status-wont-fix-label)
	- [3.3. `Priority` issue labels](#33-priority-issue-labels)
		- [3.3.1. 🏷️  `Priority: Critical` label](#331-priority-critical-label)
		- [3.3.2. 🏷️  `Priority: High` label](#332-priority-high-label)
		- [3.3.3. 🏷️  `Priority: Medium` label](#333-priority-medium-label)
		- [3.3.4. 🏷️  `Priority: Low` label](#334-priority-low-label)
- [4. Submitting pull requests](#4-submitting-pull-requests)
- [5. Assignee responsibilities](#5-assignee-responsibilities)
- [6. Planning](#6-planning)
	- [6.1. Projects](#61-projects)
	- [6.2. Milestones](#62-milestones)
	- [6.3. Due dates](#63-due-dates)
- [7. Development (working with source code)](#7-development-working-with-source-code)
	- [7.1. Follow appropriate style guidelines](#71-follow-appropriate-style-guidelines)
	- [7.2. Practice behavior-driven development (BDD)](#72-practice-behavior-driven-development-bdd)
- [8. Summary](#8-summary)
- [9. Related articles](#9-related-articles)

<!-- /TOC -->


## 2. Contributions, issues, and pull requests

Contributions are stories with a beginning, a middle, and an end, all told through issues and pull requests. The best way to start is to

1. [Peruse open issues][issues-url] and add comments
2. [Create a new issue][issue-new-url]
3. [View the product backlog][product-backlog-url]
4. [Review open pull requests (PRs)][prs-url] and add comments
5. [Open a new pull request][pr-url]

## 3. Review open issues

Contributions start with clear communication, and [issues][issues-url] are a great way to collaborate asynchronously with colleagues.

Whenever you save a comment or edit an issue, the right stakeholders will be notified.

> #### :eyes: Scan open issues before creating a new one
> Please review the Backlog and open issues before you create a new issue. If your issue is urgent, there might well be an issue `Type: Hotfix` created already.

If you find your issue has already been reported, let your voice be heard!

* "Vote" for the issue with emojis:
    * For: :thumbsup:

    * Against: :thumbsdown:

* Add meaningful comments to the existing issue.

Issues are entries in a communal to-do list, and we categorize items in our to-do list to help us quickly identify, sort, and resolve issues.

### 3.1. Issue `Type` labels

`Type` labels categorize issues and pull requests by the kind of work required to complete the issue.

#### 3.1.1. 🏷️  `Type: Build` label

Issues related to product builds. The AngularJS Git commit message format is

```

build(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>

```

#### 3.1.2. 🏷️  `Type: Chore` label

Issues related to miscellaneous non-functional changes (usually "maintenance" changes). The AngularJS Git commit message format is

```

chore(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 3.1.3. 🏷️  `Type: CI` (continuous-integration) label

Issues related to continuous integration, delivery, and deployment tasks. The AngularJS Git commit message format is

```

ci(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 3.1.4. 🏷️  `Type: Defect` ("Bug") label


#### 3.1.5. 🏷️  `Type: Docs` label

Public API documentation can be the "secret sauce" in a software product. In fact, `PRODUCT_NAME`'s README lists two badges that assess how well `PRODUCT_NAME` has been documented.

The AngularJS Git commit message format is

```

docs(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 3.1.6. 🏷️  `Type: Duplicate` label


#### 3.1.7. 🏷️  `Type: Feature` label

New feature or enhancement requests. The AngularJS Git commit message format is

```

feat(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 3.1.8. 🏷️  `Type: Fix` label

A potential fix for a `Type: Defect`. The AngularJS Git commit message format is

```

fix(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 3.1.9. 🏷️  `Type: Performance` label

Performance improvement issues. The AngularJS Git commit message format is

```

perf(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 3.1.10. 🏷️  `Type: Question` label


#### 3.1.11. 🏷️  `Type: Refactor` label

Source code design **improvements that do not affect product behavior**. The AngularJS Git commit message format is

```

refactor(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 3.1.12 🏷️  `Type: Revert` label

Tasks that revert to a previous commit hash. The AngularJS Git commit message format is

```

revert(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

#### 3.1.13. 🏷️  `Type: Spike` label


#### 3.1.14. 🏷️  `Type: Style` label

Issues related to style guideline compliance, especially `ESLint` errors and warnings. The AngularJS Git commit message format is

```

style(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```


#### 3.1.15. 🏷️  `Type: Test` label

Test coverage tasks. The AngularJS Git commit message format is

```

test(<scope>): <subject>
<BLANK LINE>
<[body]>
<BLANK LINE>
<footer>
```

### 3.2. `Status` issue labels

`Status` labels indicate the level of work done (or that needs to be done). The `Status` of an issue or pull request is always relative to two simple extremes: `Open` or `Closed`.

#### 3.2.1 🏷️  `Status: Abandoned` label


#### 3.2.2. 🏷️  `Status: Accepted` label


#### 3.2.3. 🏷️  `Status: Available` label


#### 3.2.4. 🏷️  `Status: Blocked` label


#### 3.2.5. 🏷️  `Status: Completed` label


#### 3.2.6. 🏷️  `Status: In Progress` label


#### 3.2.7. 🏷️  `Status: On Hold` label


#### 3.2.8. 🏷️  `Status: Pending` label


#### 3.2.9. 🏷️  `Status: Review Needed` label


#### 3.2.10. 🏷️  `Status: Revision Needed` label


#### 3.2.11. 🏷️  `Status: Won't Fix` label


### 3.3. `Priority` issue labels

`Priority` labels indicate how important an issue or pull request is to the community, and usually dictate precedence.

> :warning: Issues require real people who balance work and life to review your issue, so don't label issues as `Priority: High` or greater unless they really apply. Abusing priority labels only make `Priority` labels meaningless.

#### 3.3.1. 🏷️  `Priority: Critical` label


#### 3.3.2. 🏷️  `Priority: High` label


#### 3.3.3. 🏷️  `Priority: Medium` label


#### 3.3.4. 🏷️  `Priority: Low` label


## 4. Submitting pull requests


## 5. Assignee responsibilities

Assignees are responsible for completing an issue. Do not assign an issue to someone unless they agree to it.

Self-assignment is good! You can always clone the develop branch and issue a pull request to queue a code review.

## 6. Planning

### 6.1. Projects


### 6.2. Milestones
The creation of new milestones is by group consensus only. Don't do it on your own.

### 6.3. Due dates
A milestone with a due date should have a "responsible person" listed in the description. That doesn't mean that person is the sole person to work on it, just that they're the one responsible for coordinating efforts around that chunk of work.

Once a milestone has a due date, only issues okay'd by the responsible person can be added. This ensures that a chunk of work can be delivered by the promised due date.


## 7. Development (working with source code)


### 7.1. Follow appropriate style guidelines


### 7.2. Practice behavior-driven development (BDD)

Write specs (i.e., unit tests). Behavior-driven development specifications are executable documentation. By the way, 100% code coverage is the norm, not the exception.

## 8. Summary

Thank you for contributing, and welcome to the community!

## 9. Related articles



[commitplease-url]: https://www.npmjs.com/package/commitplease
[git-commit-guidelines-url]: https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#commit
[label-status-available-url]: ../labels/Status%3A%20Available
[new-issue-url]: ../issues/new
[open-issues-url]: ../issues
[pr-url]: ../pulls
[semantic-release-url]: https://github.com/semantic-release/semantic-release
