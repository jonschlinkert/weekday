# weekday [![NPM version](https://badge.fury.io/js/weekday.svg)](http://badge.fury.io/js/weekday)

> Get the name and number of the current weekday. Or get the name of the weekday for a given number.

## Install with [npm](npmjs.org)

```bash
npm i weekday --save
```

## Run tests

```bash
npm test
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

## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/weekday/issues)

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb](https://github.com/assemble/verb) on December 07, 2014. To update, run `npm i -g verb && verb`._
