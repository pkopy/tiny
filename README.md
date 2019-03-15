# @pkopy/tiny

![xxx](https://img.shields.io/badge/npm-1.0.0.-blue.svg)

![size](https://img.shields.io/badge/ninified%20size-entry%20point%20error-red.svg)

Removes all spaces from a string.

# Install

```
$ npm install @pkopy/tiny
```

# Usage

```
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

