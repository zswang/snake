# snake

简易贪吃蛇

主要是示例 jdists + jfogs + uglify 用法

```js
/*<jdists encoding="jfogs,uglify" type="reverse">*/
function Snake(options) {
    var self = this;
    options = options || {};
    this.colCount = options.colCount || 20;
    this.rowCount = options.rowCount || 20;
    this.parent = options.parent || document.body; // 容器
    // ...
}
// ...
/*</jdists>*/
```

+ 先对代码做一次 jfogs 混淆
+ 然后再做一次 uglify 压缩

[线上演示](http://jhtmls.com/snake/)

## 使用

### 安装依赖

```bash
$ npm install
```

## 编译

```bash
$ npm run dist
```
