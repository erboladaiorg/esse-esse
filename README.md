# @erboladaiorg/esse-esse <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@erboladaiorg/esse-esse');
const Eval = require('@erboladaiorg/esse-esse/eval');
const Range = require('@erboladaiorg/esse-esse/range');
const Ref = require('@erboladaiorg/esse-esse/ref');
const Syntax = require('@erboladaiorg/esse-esse/syntax');
const Type = require('@erboladaiorg/esse-esse/type');
const URI = require('@erboladaiorg/esse-esse/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@erboladaiorg/esse-esse
[npm-version-svg]: https://versionbadg.es/ljharb/@erboladaiorg/esse-esse.svg
[deps-svg]: https://david-dm.org/ljharb/@erboladaiorg/esse-esse.svg
[deps-url]: https://david-dm.org/ljharb/@erboladaiorg/esse-esse
[dev-deps-svg]: https://david-dm.org/ljharb/@erboladaiorg/esse-esse/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@erboladaiorg/esse-esse#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@erboladaiorg/esse-esse.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@erboladaiorg/esse-esse.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@erboladaiorg/esse-esse.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@erboladaiorg/esse-esse
[codecov-image]: https://codecov.io/gh/ljharb/@erboladaiorg/esse-esse/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@erboladaiorg/esse-esse/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@erboladaiorg/esse-esse
[actions-url]: https://github.com/erboladaiorg/esse-esse/actions
