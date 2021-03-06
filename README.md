# weekday [![NPM version](https://img.shields.io/npm/v/weekday.svg?style=flat)](https://www.npmjs.com/package/weekday) [![NPM downloads](https://img.shields.io/npm/dm/weekday.svg?style=flat)](https://npmjs.org/package/weekday) [![Build Status](https://img.shields.io/travis/datetime/weekday.svg?style=flat)](https://travis-ci.org/datetime/weekday)

> Get the name and number of the current weekday. Or get the name of the weekday for a given number.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save weekday
```

## Usage

```js
var weekday = require('weekday');
weekday();
//=> 'Sunday' (current day)

weekday('Sunday');
//=> '1'

weekday(1);
//=> 'Sunday'

weekday(4);
//=> 'Wednesday'
```

## About

### Related projects

* [time-diff](https://www.npmjs.com/package/time-diff): Returns the formatted, high-resolution time difference between `start` and `end` times. | [homepage](https://github.com/jonschlinkert/time-diff "Returns the formatted, high-resolution time difference between `start` and `end` times.")
* [time-stamp](https://www.npmjs.com/package/time-stamp): Get a formatted timestamp. | [homepage](https://github.com/jonschlinkert/time-stamp "Get a formatted timestamp.")
* [week](https://www.npmjs.com/package/week): Get the current week number. | [homepage](https://github.com/jonschlinkert/week "Get the current week number.")
* [year](https://www.npmjs.com/package/year): Simple utility to get the current year with 2 or 4 digits. | [homepage](https://github.com/jonschlinkert/year "Simple utility to get the current year with 2 or 4 digits.")

### Contributors

| **Commits** | **Contributor**<br/> | 
| --- | --- |
| 12 | [jonschlinkert](https://github.com/jonschlinkert) |
| 1 | [brentvatne](https://github.com/brentvatne) |
| 1 | [davidohlin](https://github.com/davidohlin) |

### Building docs

_(This document was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme) (a [verb](https://github.com/verbose/verb) generator), please don't edit the readme directly. Any changes to the readme must be made in [.verb.md](.verb.md).)_

To generate the readme and API documentation with [verb](https://github.com/verbose/verb):

```sh
$ npm install -g verb verb-generate-readme && verb
```

### Running tests

Install dev dependencies:

```sh
$ npm install -d && npm test
```

### Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

### License

Copyright © 2016, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT license](https://github.com/datetime/weekday/blob/master/LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.1.31, on September 19, 2016._