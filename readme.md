# vite-plugin-rewrite-all [![npm](https://img.shields.io/npm/v/vite-plugin-rewrite-all.svg)](https://www.npmjs.com/package/vite-plugin-rewrite-all)

Vite plugin that fix dev server not rewriting the path includes a dot [vite#2190](https://github.com/vitejs/vite/issues/2190)

### Installation

```
npm install --save-dev vite-plugin-rewrite-all
```

### Usage

Add it to vite.config.js

```js
import pluginRewriteAll from 'vite-plugin-rewrite-all';

export default {
  plugins: [pluginRewriteAll()]
}
```

As long as you can rewriting all path, this should work for you.

### License

[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2021-present, AlphaTr
