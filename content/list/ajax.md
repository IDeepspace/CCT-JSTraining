### 简介

AJAX（异步 JavaScript 和 XML，Asynchronous JavaScript + XML）, 其本身不是一种新技术，而是一个在 2005 年被 Jesse James Garrett 提出的新术语，用来描述一种使用现有技术集合的‘新’方法，包括: [HTML](https://developer.mozilla.org/en-US/docs/HTML) or [XHTML](https://developer.mozilla.org/en-US/docs/XHTML), [Cascading Style Sheets](https://developer.mozilla.org/en-US/docs/CSS), [JavaScript](https://developer.mozilla.org/en-US/docs/JavaScript), [The Document Object Model](https://developer.mozilla.org/en-US/docs/DOM), [XML](https://developer.mozilla.org/en-US/docs/XML), [XSLT](https://developer.mozilla.org/en-US/docs/XSLT), 以及最重要的 [XML HttpRequest object](https://developer.mozilla.org/en-US/docs/DOM/XMLHttpRequest)。当使用结合了这些技术的 AJAX 模型以后， 网页程序能够快速地将渐步更新呈现在用户界面上，不需要重载（刷新）整个页面。这使得程序能够更快地回应用户的操作。

尽管 X 在 Ajax 中代表 XML, 但由于 JSON 的许多优势，比如更加轻量以及作为 Javascript 的一部分，目前 JSON 的使用比 XML 更加普遍。JSON 和 XML 都被用于在 Ajax 模型中打包信息。

### 学习资源

* 菜鸟教程 —— [AJAX 教程](http://www.runoob.com/ajax/ajax-tutorial.html)
* 菜鸟教程 —— [jQuery AJAX 方法](http://www.runoob.com/jquery/jquery-ref-ajax.html)
* [axios 英文文档](https://github.com/axios/axios)
* [axios 中文文档](https://segmentfault.com/a/1190000008470355)

### 学习步骤

单单看教程，没有上手写代码，对 AJAX 使用方法的理解是模糊的。我们来按照下面的学习步骤来理解：

> 注：练习中使用的是 axios

Axios 是一个基于 promise 的 HTTP 库，可以工作于浏览器中，也可以在 node.js 中使用，提供了一个 API 用来处理 XMLHttpRequests 和 node 的 http 接口

可能很多人会疑问：用 jquery 的 get/post 不就很好了，为什么要用 Axios？原因主要有：

1. Axios 支持 node.js，jquery 不支持
2. Axios 基于 promise 语法标准，jquery 在 3.0 版本中才全面支持
3. Axios 是一个小巧而专业的 HTTP 库，jquery 是一个大而全的库，如果有些场景不需要使用 jquery 的其他功能，只需要 HTTP 相关功能，这时使用 Axios 会更适合

#### 练习

* [练习一：json-server 创建 mock 数据](https://shimo.im/doc/I4kAT7Z975AvWT7o?r=G7O833)
* [练习二：发送 get 请求获取数据并渲染在页面上](https://shimo.im/doc/NZxSbNrZnSQkVcly?r=G7O833)
* [练习三：发送 post 请求新增一条数据](https://shimo.im/doc/G0ssQ3e6ArsavWW2?r=G7O833)
* [练习四：删除数据与改善代码结构](https://shimo.im/doc/5nXWO89JGRgAg9Os?r=G7O833)

#### 理解代码

* 读懂 [简易版在线影城](https://github.com/CoolCodeTribe/simple-theater.git) 的代码：https://github.com/CoolCodeTribe/simple-theater.git
