# Math.log1p <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Math.log1p` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-@bobyzgirlllnpm/hic-nesciunt-quod).

## Getting started

```sh
npm install --save @bobyzgirlllnpm/hic-nesciunt-quod
```

## Usage/Examples

```js
var assert = require('assert');
var x = 0.007;

// Compute log(1 + x)
assert.equal(Math.log1p(x), 0.006975613736425242);

assert.equal(Math.log1p(6.3890560989306495), 2);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@bobyzgirlllnpm/hic-nesciunt-quod
[npm-version-svg]: https://versionbadg.es/bobyzgirlllnpm/hic-nesciunt-quod.svg
[deps-svg]: https://david-dm.org/bobyzgirlllnpm/hic-nesciunt-quod.svg
[deps-url]: https://david-dm.org/bobyzgirlllnpm/hic-nesciunt-quod
[dev-deps-svg]: https://david-dm.org/bobyzgirlllnpm/hic-nesciunt-quod/dev-status.svg
[dev-deps-url]: https://david-dm.org/bobyzgirlllnpm/hic-nesciunt-quod#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@bobyzgirlllnpm/hic-nesciunt-quod.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@bobyzgirlllnpm/hic-nesciunt-quod.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@bobyzgirlllnpm/hic-nesciunt-quod.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@bobyzgirlllnpm/hic-nesciunt-quod
[codecov-image]: https://codecov.io/gh/bobyzgirlllnpm/hic-nesciunt-quod/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/bobyzgirlllnpm/hic-nesciunt-quod/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/bobyzgirlllnpm/hic-nesciunt-quod
[actions-url]: https://github.com/bobyzgirlllnpm/hic-nesciunt-quod/actions
