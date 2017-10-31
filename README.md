# Amaze UI address
## qq群：82447172
---
**更新内容：**
1. 修复丢失省份
2. 修复移动端滑动失效BUG

### address
Amaze UI 中国地区级联组件 

- [使用示例](http://topoadmin.github.io/address/docs/demo.html)
- [API文档](http://github.com/topoadmin/address/blob/master/docs/api.md)

**使用说明：**
1. 获取 Amaze UI address

  - [直接下载](https://github.com/topoadmin/address/archive/master.zip)

2. 在 Amaze UI 样式之后引入 address 样式（`dist` 目录下的 CSS）：

  Amaze UI address 依赖 Amaze UI 样式。

  ```html
  <link rel="stylesheet" href="dist/amazeui.min.css"/>
  <link rel="stylesheet" href="dist/amazeui.address.min.css"/>
  ```

3. 引入 address 插件（`dist` 目录下的 JS）：
  ```html
  <script src="dist/jquery.min.js"></script>
  <script src="dist/amazeui.min.js"></script>
  `<!-- 可选： 建议引入 iscroll 原文件, 妹子内置 lite 版功能比较少 -->`
  <script src="dist/iscroll.min.js"></script>	
  <script src="dist/address.min.js"></script>
  ```

4. 初始化 address:

  ```js
  $(function() {
      $('#address').address();
  });
  ```
