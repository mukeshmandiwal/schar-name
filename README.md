# schar-name

[![travis build](https://img.shields.io/travis/mukeshmandiwal/schar-name.svg?style=flat-square)](https://travis-ci.org/mukeshmandiwal/schar-name)
[![codecov coverage](https://img.shields.io/codecov/c/github/mukeshmandiwal/schar-name.svg?style=flat-square)](https://codecov.io/github/mukeshmandiwal/schar-name)
[![version](https://img.shields.io/npm/v/schar-name.svg?style=flat-square)](http://npm.im/schar-name)
[![downloads](https://img.shields.io/npm/dm/schar-name.svg?style=flat-square)](http://npm-stat.com/charts.html?package=schar-name&from=2015-08-01)
[![MIT License](https://img.shields.io/npm/l/schar-name.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=flat-square)](https://github.com/semantic-release/semantic-release)

Get random names from Star Wars characters.

<a href="https://app.codesponsor.io/link/PKGFLnhDiFvsUA5P4kAXfiPs/mukeshmandiwal/schar-name" rel="nofollow"><img src="https://app.codesponsor.io/embed/PKGFLnhDiFvsUA5P4kAXfiPs/mukeshmandiwal/schar-name.svg" style="width: 888px; height: 68px;" alt="Sponsor" /></a>

![schar-name](other/starwars-names.gif)

## Installation

This package is distributed via npm:

```
npm install schar-name
```

## Usage

```javascript
var names = require("schar-name");
var allNames = names.all;
var randomName = names.random();
var threeRandomNames = names.random(3);
```

### Project Setup

This project assumes you have [NodeJS 8](http://nodejs.org/) or greater installed. You should
also have [npm v5+(https://www.npmjs.com/) or greater installed as well (this comes packaged
with Node 8). You'll also need a recent version of [git](https://git-scm.com/) installed
as well.

You may have come to this project from different varying sources. There are a
different series of branches for each workshop/course I've done. To get started with
the project, start with this:

1. [Sign up](https://github.com/join) for a GitHub Account (if you don't already have one)
2. [Fork](https://help.github.com/articles/fork-a-repo/) this repo
3. [Clone](https://help.github.com/articles/cloning-a-repository/) your fork
4. In the directory you cloned the repository, run `git fetch --all`

If you get any failures at this point something is wrong and needs to be fixed. Remember,
[Google](https://google.com) and [StackOverflow](https://stackoverflow.com) are your friends.

You might find it helpful to see a list of the available branches. Run: `git branch` for that.
