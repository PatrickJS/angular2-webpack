# Angular 2 Webpack



```es6
var path = require('path');
var ng2webpack = require('angular2-webpack');

var srcPath = path.join(__dirname + 'src');

module.exports = {
  module: {
    preLoaders: [
      ng2webpack.loaders()
    ]
  },
  plugins: [
    ng2webpack.plugins(srcPath)
  ]
}
```
