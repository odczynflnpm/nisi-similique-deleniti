# @odczynflnpm/nisi-similique-deleniti <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @odczynflnpm/nisi-similique-deleniti
```

## Usage/Examples

```js
var regexTester = require('@odczynflnpm/nisi-similique-deleniti');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@odczynflnpm/nisi-similique-deleniti
[npm-version-svg]: https://versionbadg.es/ljharb/@odczynflnpm/nisi-similique-deleniti.svg
[deps-svg]: https://david-dm.org/ljharb/@odczynflnpm/nisi-similique-deleniti.svg
[deps-url]: https://david-dm.org/ljharb/@odczynflnpm/nisi-similique-deleniti
[dev-deps-svg]: https://david-dm.org/ljharb/@odczynflnpm/nisi-similique-deleniti/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@odczynflnpm/nisi-similique-deleniti#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@odczynflnpm/nisi-similique-deleniti.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@odczynflnpm/nisi-similique-deleniti.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@odczynflnpm/nisi-similique-deleniti.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@odczynflnpm/nisi-similique-deleniti
[codecov-image]: https://codecov.io/gh/ljharb/@odczynflnpm/nisi-similique-deleniti/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@odczynflnpm/nisi-similique-deleniti/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@odczynflnpm/nisi-similique-deleniti
[actions-url]: https://github.com/odczynflnpm/nisi-similique-deleniti/actions
