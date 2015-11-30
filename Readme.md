
# is-promise

[![Build status][travis-image]][travis-url]
[![Git tag][git-image]][git-url]
[![NPM version][npm-image]][npm-url]
[![Code style][standard-image]][standard-url]

Check whether a value is a promise.

## Installation

    $ npm install @micro-js/is-promise

## Usage

```js
var isPromise = require('@micro-js/is-promise');

isPromise({then: function () {...}}) // => true
isPromise(null) // => false
isPromise({}) // => false
isPromise({then: true})// => false
```

## API

### isPromise(value)

- `value` - value to test

**Returns:** boolean


## License

MIT

[travis-image]: https://img.shields.io/travis/micro-js/is-promise.svg?style=flat-square
[travis-url]: https://travis-ci.org/micro-js/is-promise
[git-image]: https://img.shields.io/github/tag/micro-js/is-promise.svg
[git-url]: https://github.com/micro-js/is-promise
[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat
[standard-url]: https://github.com/feross/standard
[npm-image]: https://img.shields.io/npm/v/@micro-js/is-promise.svg?style=flat-square
[npm-url]: https://npmjs.org/package/@micro-js/is-promise
