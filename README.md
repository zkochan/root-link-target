# root-link-target

> Gets the shortest directory to which a file can be linked

<!--@shields('npm', 'travis')-->
[![npm version](https://img.shields.io/npm/v/root-link-target.svg)](https://www.npmjs.com/package/root-link-target) [![Build Status](https://img.shields.io/travis/zkochan/root-link-target/master.svg)](https://travis-ci.org/zkochan/root-link-target)
<!--/@-->

## Installation

```sh
npm i -S root-link-target
```

## Usage

```js
const rootLinkTarget = require('root-link-target')

canLink.sync('C:\\sub\\dir\\foo.txt')
//> C:\\
```

## API

### `rootLinkTarget.sync(filename): string`

Returns the shortest directory to which `filename` can be linked

### `rootLinkTarget(filename): Promise<string>`

## License

[MIT](./LICENSE) © [Zoltan Kochan](https://www.kochan.io/)
