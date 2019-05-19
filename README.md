# tiny

![npm](https://img.shields.io/npm/v/@chucxin/tiny.svg?style=flat-square)

It's funny.

## Install
```
$ npm install @chucxin/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```


