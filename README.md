# array-unique [![NPM version](https://badge.fury.io/js/array-unique.svg)](http://badge.fury.io/js/array-unique)  [![Build Status](https://travis-ci.org/jonschlinkert/array-unique.svg)](https://travis-ci.org/jonschlinkert/array-unique) 

> Return an array free of duplicate values. Fastest ES5 implementation.

## Install with [npm](npmjs.org)

```bash
npm i array-unique --save
```

## Running tests
Install dev dependencies.

```bash
npm i -d && npm test
```

## Usage

```js
var unique = require('array-unique');

unique(['a', 'b', 'c', 'c']);
//=> ['a', 'b', 'c']
```

## API


## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/array-unique/issues)

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2015 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on March 11, 2015._