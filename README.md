## How to use

First, install the dependencies locally and Mocha globally.

```bash
$ npm install --global mocha
$ npm install
```
Then, use the following commands

```javascript
// basic usage
mocha add.test.js
// 生成报告
mocha --recursive --reporter mochawesome
// es6
mocha --require @babel/register
// 异步
mocha -t 5000 -s 1000 src/demo05/timeout.test.js
mocha -t 3000 src/demo05/async.test.js
mocha -t 3000 src/demo05/promise.test.js
// 其他
mocha --watch
```
- [hooks](https://github.com/ruanyf/mocha-demos/tree/master/demo06)
- [exclusive/inclusive Tests](https://github.com/ruanyf/mocha-demos/tree/master/demo07)
- [browser testing](https://github.com/ruanyf/mocha-demos/tree/master/demo08)
- [generating spec](https://github.com/ruanyf/mocha-demos/tree/master/demo09)

## License
MIT