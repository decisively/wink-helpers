
# wink-helpers

> Low level helper functions for Javascript arrays and objects used in wink

### [![Build Status](https://api.travis-ci.org/decisively/wink-helpers.svg?branch=master)](https://travis-ci.org/decisively/wink-porter2-stemmer) [![Coverage Status](https://coveralls.io/repos/github/decisively/wink-helpers/badge.svg?branch=master)](https://coveralls.io/github/decisively/wink-porter2-stemmer?branch=master)

<img align="right" src="https://decisively.github.io/wink-logos/logo-title.png" width="100px" >

**wink-helpers** is a part of **[wink](https://www.npmjs.com/~sanjaya)**, which is a family of Machine Learning NPM packages. They consist of simple and/or higher order functions that can be combined with NodeJS `stream` and `child processes` to create recipes for analytics driven business solutions.

[Stemming](https://en.wikipedia.org/wiki/Stemming) reduces an inflected word into its base form, for example *learning* to *learn*. It is used extensively in Natural Language Processing (NLP).

## Installation
Use **[npm](https://www.npmjs.com/package/wink-helpers)** to install:
```
npm install wink-helpers --save
```


## Usage
```javascript

// Load porter stemmer V2
var stem = require( 'wink-helpers' );

console.log( stem( 'properly' ) );
// -> proper

console.log( stem( 'borrowed' ) );
// -> borrow

console.log( stem( 'stemming' ) );
// -> stem
```

## Need Help?
If you spot a bug and the same has not yet been reported, raise a new [issue](https://github.com/decisively/wink-porter2-stemmer/issues) or consider fixing it and sending a pull request.


## Copyright & License
**wink-porter2-stemmer** is copyright 2017 GRAYPE Systems Private Limited.

It is licensed under the under the terms of the GNU Affero General Public License as published by the Free
Software Foundation, version 3 of the License.
