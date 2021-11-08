1.在你的 `webpack.config.js` 文件中引入。
2.在 `plugins` 里面 new 该插件。
## Usages
```js
const RemoveStrict = require('webpack-strict-remove-plugin');

// webpack-config.js
module.exports = {
  plugins: [
    new RemoveStrict(),
  ]
}
```