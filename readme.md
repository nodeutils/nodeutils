# [nodeutils](https://www.npmjs.com/package/nodeutils)
##### A range of node utilities to aid your development.

## Installation

Install the package via `npm`:

```
$ npm install nodeutils --save
```

## Usage

Every nodeutils package is available as a poperty of nodeutils, in camelCase.

# Packages

## reqhere
Simple straightforward tool to allow you to require locally. [[Read More]](https://www.npmjs.com/package/@nodeutils/reqhere)
```
require("nodeutils").reqhere();
```

## defaultsDeep
Like lodash's defaultsDeep, but with no mutation and with preservation of arrays. [[Read More]](https://www.npmjs.com/package/@nodeutils/defaults-deep)
```
var defaultsDeep = require("nodeutils").defaultsDeep;
var merged = defaultsDeep(mostImportant, nextImportant, leastImportant...);
```
