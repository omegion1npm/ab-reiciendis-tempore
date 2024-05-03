# @omegion1npm/ab-reiciendis-tempore <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@omegion1npm/ab-reiciendis-tempore');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@omegion1npm/ab-reiciendis-tempore
[npm-version-svg]: https://versionbadg.es/inspect-js/@omegion1npm/ab-reiciendis-tempore.svg
[deps-svg]: https://david-dm.org/inspect-js/@omegion1npm/ab-reiciendis-tempore.svg
[deps-url]: https://david-dm.org/inspect-js/@omegion1npm/ab-reiciendis-tempore
[dev-deps-svg]: https://david-dm.org/inspect-js/@omegion1npm/ab-reiciendis-tempore/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@omegion1npm/ab-reiciendis-tempore#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@omegion1npm/ab-reiciendis-tempore.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@omegion1npm/ab-reiciendis-tempore.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@omegion1npm/ab-reiciendis-tempore.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@omegion1npm/ab-reiciendis-tempore
[codecov-image]: https://codecov.io/gh/inspect-js/@omegion1npm/ab-reiciendis-tempore/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@omegion1npm/ab-reiciendis-tempore/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@omegion1npm/ab-reiciendis-tempore
[actions-url]: https://github.com/omegion1npm/ab-reiciendis-tempore/actions
