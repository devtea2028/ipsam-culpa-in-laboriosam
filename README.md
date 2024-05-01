# Math.imul <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Math.imul` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @devtea2028/ipsam-culpa-in-laboriosam
```

## Usage/Examples

```js
console.log(Math.imul(2, 4)); // 8
console.log(Math.imul(-1, 8)); // -8
console.log(Math.imul(-2, -2)); // 4
console.log(Math.imul(0xffffffff, 5)); // -5
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@devtea2028/ipsam-culpa-in-laboriosam
[npm-version-svg]: https://versionbadg.es/devtea2028/ipsam-culpa-in-laboriosam.svg
[deps-svg]: https://david-dm.org/devtea2028/ipsam-culpa-in-laboriosam.svg
[deps-url]: https://david-dm.org/devtea2028/ipsam-culpa-in-laboriosam
[dev-deps-svg]: https://david-dm.org/devtea2028/ipsam-culpa-in-laboriosam/dev-status.svg
[dev-deps-url]: https://david-dm.org/devtea2028/ipsam-culpa-in-laboriosam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2028/ipsam-culpa-in-laboriosam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2028/ipsam-culpa-in-laboriosam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2028/ipsam-culpa-in-laboriosam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2028/ipsam-culpa-in-laboriosam
[codecov-image]: https://codecov.io/gh/devtea2028/ipsam-culpa-in-laboriosam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/devtea2028/ipsam-culpa-in-laboriosam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/devtea2028/ipsam-culpa-in-laboriosam
[actions-url]: https://github.com/devtea2028/ipsam-culpa-in-laboriosam/actions
