---
title: Managing Releases
layout: doc
---

# Managing Releases

Releases are when a project formally publishes a new version so the community can use it. There are two types of releases:

* Regular releases that follow [semantic versioning](http://semver.org/) and are considered production-ready.
* Prereleases that are not considered production-ready and are intended to give the community a preview of upcoming changes.

## Setting up a Release Environment

In order to run a release, be sure that:

1. You have [eslint.github.io](https://github.com/eslint/eslint.github.io) checked out into the same directory as the project (such as ESLint itself). Some projects automatically update the website.
1. You are logged in to npm. If not, [log in](https://docs.npmjs.com/cli/adduser).

## Regular Releases

You can run a regular release with the following command:

```
$ npm run release
```

The [release tool](https://github.com/eslint/eslint-release) will inspect the commit history and determine the correct next version. It will also handle publishing to both GitHub and npm with the correct names and tags. Each project may have additional steps for pushing a release, but the basic steps are the same for all.

## Prereleases

You can run a prerelease with the following command:

```
$ npm run prerelease -- <release version>
```

You need to replace `<release version>` with a prerelease version. Prelease versions are in the form 0.0.0-tag.0, such as 2.0.0-beta.1. For example:

```
$ npm run prerelease -- 2.0.0-beta.1
```

As with regular releases, the release tool will handle the common parts of the release process. The biggest differences are that it will use the version you specify instead of calculating one and it will push to npm using the `next` tag instead of `latest`.
