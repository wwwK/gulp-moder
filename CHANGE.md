# v0.1.x

### v0.1.0

实现基本功能：

- 支持更新时生成模块文件后缀名（基于文件内容 MD5）；
- 支持替换文件内 Map 标签内容；
- 支持生成模块 Map 文件；
- 支持追加 Map 到主 Map；

### v0.1.1

- 更新 `index.js` `rename()` 方法；
- 更新 README.md，`moder.js` 链接地址错误的问题；

### v0.1.2

- 整理代码 @`index.js`；
- 更新 README.md；

### v0.1.3

- 修复自动写入模块名错误（即已定义模块名，还会再加入模块名）的问题；
- 更新 `writeMapToJSON()` 和 `replaceMap()` 方法，都新增一个参数 `remap`，用于从外部传入模块 Map 对象，方便适应任务需要； 
- 新增成员属性 `suffixPrefix` 用于给文件名后缀加一个前缀，默认为 `_`；
- 更新 README.md；
- 更新测试实例；

### v0.1.4

- 新增：配置项 `versionQuery`，用于不使用 MD5 后缀文件名，改为使用 Query String 来实现版本标注；
- 更新文档及测试实例；