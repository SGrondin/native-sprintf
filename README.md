# native-sprintf [![version][npm-version]][npm-url] [![License][npm-license]][license-url]

> unnamed package

[![Build Status][travis-image]][travis-url]
[![Downloads][npm-downloads]][npm-url]
[![Code Climate][codeclimate-quality]][codeclimate-url]
[![Coverage Status][codeclimate-coverage]][codeclimate-url]
[![Dependencies][david-image]][david-url]

## Install

```bash
npm install --save native-sprintf
```

## API

### sprintf()

```js
var sprintf = require('native-sprintf').sprintf

sprintf('%s', 'foo')
```

### vsprintf()

```js
var vsprintf = require('native-sprintf').vsprintf

vsprintf('%s', ['foo'])
```

----
> :copyright: [simongrondin.name](http://simongrondin.name/) &nbsp;&middot;&nbsp;
> License: [ISC](LICENSE) &nbsp;&middot;&nbsp;
> Github: [@sgrondin](https://github.com/sgrondin) &nbsp;&middot;&nbsp;

[license-url]: http://choosealicense.com/licenses/isc/

[travis-url]: https://travis-ci.org/sgrondin/native-sprintf
[travis-image]: https://img.shields.io/travis/sgrondin/native-sprintf.svg?style=flat-square

[npm-url]: https://www.npmjs.com/package/native-sprintf
[npm-license]: https://img.shields.io/npm/l/native-sprintf.svg?style=flat-square
[npm-version]: https://img.shields.io/npm/v/native-sprintf.svg?style=flat-square
[npm-downloads]: https://img.shields.io/npm/dm/native-sprintf.svg?style=flat-square

[codeclimate-url]: https://codeclimate.com/github/sgrondin/native-sprintf
[codeclimate-quality]: https://img.shields.io/codeclimate/github/sgrondin/native-sprintf.svg?style=flat-square
[codeclimate-coverage]: https://img.shields.io/codeclimate/coverage/github/sgrondin/native-sprintf.svg?style=flat-square

[david-url]: https://david-dm.org/sgrondin/native-sprintf
[david-image]: https://img.shields.io/david/sgrondin/native-sprintf.svg?style=flat-square
