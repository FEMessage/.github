# FEMessage Contributing Guide

👍🎉 First off, thanks for taking the time to contribute! 🎉👍

Before submitting your contribution, please make sure to take a moment and read through the following guidelines:

- [Code of Conduct](https://github.com/FEMessage/.github/blob/master/CODE_OF_CONDUCT.md)
- [I don't want to read this whole thing, I just have a question!!!](#i-dont-want-to-read-this-whole-thing-i-just-have-a-question)
- [Issue Reporting Guidelines](#issue-reporting-guidelines)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Development Setup](#development-setup)

## I don't want to read this whole thing, I just have a question!!!

**Note:** Please don't file an issue to ask a question. 

You can join our dingtalk chat group to ask a question.

![](https://user-images.githubusercontent.com/9384365/61931590-9c6e6c80-afb3-11e9-9c1f-0d61313a1bfb.png)

## Issue Reporting Guidelines

- Always create new issues using [template](https://github.com/FEMessage/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md).

## Pull Request Guidelines

- You'd better take a moment to konw about our component developing tool: [vue-sfc-cli](https://github.com/FEMessage/vue-sfc-cli)

- Please submit Pull Request using [template](https://github.com/FEMessage/.github/blob/master/.github/PULL_REQUEST_TEMPLATE.md)

- The `master` branch is just a snapshot of the latest stable release. All development should be done in `dev` branches. **Do not submit PRs against the `master` branch.**

- **DO NOT** checkin `dist` in the commits.

- It's OK to have multiple small commits as you work on the PR - GitHub will automatically squash it before merging.

## Development Setup

You will need [Node.js](http://nodejs.org) **version 8+**

After cloning the repo, run:

``` bash
$ yarn # install the dependencies of the project
```

### Committing Changes

Commit messages should follow the [commit message convention](https://conventionalcommits.org/) so that changelogs can be automatically generated. Commit messages will be automatically validated upon commit. If you are not familiar with the commit message convention, you can use `npm run commit` instead of `git commit`, which provides an interactive CLI for generating proper commit messages.

### Commonly used NPM scripts

``` bash
# develop with hot reload
$ yarn dev

# if add new feature, you may need add releated docs
$ vi docs/xxx.md

# run unit tests
$ yarn test
```

