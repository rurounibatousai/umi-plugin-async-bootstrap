# umi-plugin-async-bootstrap

[![NPM version](https://img.shields.io/npm/v/umi-plugin-async-bootstrap.svg?style=flat)](https://npmjs.org/package/umi-plugin-async-bootstrap)
[![NPM downloads](http://img.shields.io/npm/dm/umi-plugin-async-bootstrap.svg?style=flat)](https://npmjs.org/package/umi-plugin-async-bootstrap)

支持umi异步启动

## Install

```bash
# or yarn
$ npm install
```

```bash
$ npm run build --watch
$ npm run start
```

## Usage

Configure in `.umirc.js`,

```js
export default {
  // umi项目可以不用注入
  plugins: [
    ['umi-plugin-async-bootstrap'],
  ],
}
```

## LICENSE

MIT
