# @hishprorg/vel-magnam-accusantium <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Determine if the JS environment has Symbol support. Supports spec, or shams.

## Example

```js
var hasSymbols = require('@hishprorg/vel-magnam-accusantium');

hasSymbols() === true; // if the environment has native Symbol support. Not polyfillable, not forgeable.

var hasSymbolsKinda = require('@hishprorg/vel-magnam-accusantium/shams');
hasSymbolsKinda() === true; // if the environment has a Symbol sham that mostly follows the spec.
```

## Supported Symbol shams
 - get-own-property-symbols [npm](https://www.npmjs.com/package/get-own-property-symbols) | [github](https://github.com/WebReflection/get-own-property-symbols)
 - core-js [npm](https://www.npmjs.com/package/core-js) | [github](https://github.com/zloirock/core-js)

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@hishprorg/vel-magnam-accusantium
[2]: https://versionbadg.es/inspect-js/@hishprorg/vel-magnam-accusantium.svg
[5]: https://david-dm.org/inspect-js/@hishprorg/vel-magnam-accusantium.svg
[6]: https://david-dm.org/inspect-js/@hishprorg/vel-magnam-accusantium
[7]: https://david-dm.org/inspect-js/@hishprorg/vel-magnam-accusantium/dev-status.svg
[8]: https://david-dm.org/inspect-js/@hishprorg/vel-magnam-accusantium#info=devDependencies
[11]: https://nodei.co/npm/@hishprorg/vel-magnam-accusantium.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hishprorg/vel-magnam-accusantium.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hishprorg/vel-magnam-accusantium.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hishprorg/vel-magnam-accusantium
[codecov-image]: https://codecov.io/gh/inspect-js/@hishprorg/vel-magnam-accusantium/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@hishprorg/vel-magnam-accusantium/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@hishprorg/vel-magnam-accusantium
[actions-url]: https://github.com/hishprorg/vel-magnam-accusantium/actions
