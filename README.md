# Math.clz32 <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Math.clz32` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @taktikorg/sequi-tenetur
```

## Usage/Examples

```js
console.log(Math.clz32(1)); // 31
console.log(Math.clz32(1000)); // 22
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@taktikorg/sequi-tenetur
[npm-version-svg]: https://versionbadg.es/taktikorg/sequi-tenetur.svg
[deps-svg]: https://david-dm.org/taktikorg/sequi-tenetur.svg
[deps-url]: https://david-dm.org/taktikorg/sequi-tenetur
[dev-deps-svg]: https://david-dm.org/taktikorg/sequi-tenetur/dev-status.svg
[dev-deps-url]: https://david-dm.org/taktikorg/sequi-tenetur#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikorg/sequi-tenetur.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/sequi-tenetur.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/sequi-tenetur.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/sequi-tenetur
[codecov-image]: https://codecov.io/gh/taktikorg/sequi-tenetur/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/taktikorg/sequi-tenetur/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/taktikorg/sequi-tenetur
[actions-url]: https://github.com/taktikorg/sequi-tenetur/actions
