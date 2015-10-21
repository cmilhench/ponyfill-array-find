# ponyfill-array-find [![Build Status](https://travis-ci.org/cmilhench/ponyfill-array-find.svg?branch=master)](https://travis-ci.org/cmilhench/ponyfill-array-find)

> ES6 [`Array.find()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find) ponyfill

> Ponyfill: A polyfill that doesn't overwrite the native method


## Install

```
$ npm install ponyfill-array-find --save
```


## Usage

```js
var proxyfn = require('ponyfill-array-find');
[4, 5, 8, 12].find(isPrime);
//=> 5
```


## License

MIT © [Colin Milhench](http://milhen.ch)
