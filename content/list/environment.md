## 学前准备

参加学习的同学，事先应该准备好开发环境及开发工具。

### 1、安装 Git

请到官网 https://git-scm.com/ 或国内的下载站，下载安装包，然后按默认选项安装即可。

安装完成后，在开始菜单里找到 `Git -> Git Bash` ，蹦出一个类似命令行窗口的东西，就说明 Git 安装成功！

安装 Git 之后，需要学习一下如何使用它：[Git 参考教程](http://ideepspace.gitee.io/mybook-git/docs/)

同时，你也得学习下如何使用 github 或者码云：[GitHub 使用教程详解](http://blog.csdn.net/kabulore/article/details/51801337)

### 2、安装 Node

请到 Node 官网 https://nodejs.org/en/ , 或者国内镜像 http://npm.taobao.org/mirrors/node , 下载最新版本的安装包。

安装完成后，命令行执行下面的命令，确认是否安装成功，安装成功会显示 git 版本号。

```
$ node -v
v 8.9.3
```

Node 的模块管理器 npm 会一起安装好。由于 Node 的官方模块仓库网速太慢，模块仓库需要切换到阿里的源。

```
$ npm config set registry https://registry.npm.taobao.org/
```

执行下面的命令，确认是否切换成功。

```
$ npm config get registry
```

### 3、安装 vscode

请到官网 https://code.visualstudio.com/ 下载安装包，安装时注意勾选创建桌面快捷方式。

安装好 vscode 之后，我们还需要安装一些插件和修改配置信息，来让它变得更便于我们做开发。

手动安装下面的插件：

```
advanced-new-file
ESLint
HTML Snippets
JavaScript (ES6) code snippets
jQuery Code Snippets
Node Debug 2
Path Intellisense
Prettier - Code formatter
React Native Tools
Reactjs code snippets
Ternjs
vscode-styled-components
```

用户配置文件

```
{
    "terminal.integrated.confirmOnExit": true,
    "terminal.integrated.shell.windows": "D:\\Program Files\\Git\\bin\\bash.exe",
    "atomKeymap.promptV3Features": true,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.formatOnPaste": true,
    "window.zoomLevel": 0,
    "prettier.semi": false,
    "prettier.singleQuote": true,
    "editor.formatOnSave": true,
    "emmet.includeLanguages": {
        "vue-html": "html",
        "javascript": "javascriptreact"
    },
    "explorer.confirmDragAndDrop": false,
    "files.trimFinalNewlines": true,
    "explorer.confirmDelete": false,
    "files.insertFinalNewline": true,
    "files.autoSave": "onFocusChange"
}
```

vscode 自带的 terminal 默认是不支持 linux 命令的，不是很好用，所以改成了 git 的 shell(第二行，根据自己的 Git 安装地址修改)

### 4、安装 Chrome

Google Chrome 是由 Google 开发的一款设计简单、高效的 Web 浏览工具。是我们开发时必不可少。请在官网下载安装：https://www.google.cn/chrome/ 。

Chrome 可以安装很多插件，你可以在 Chrome 浏览器的应用商店下载所需要的插件，也可以在网络上下载离线安装包来安装。

### 5、安装 lantern

开发时，我们需要搜索很多资料，教程。由于某些原因，国内无法访问国外网站，lantern 可以解除这个烦恼。

蓝灯(Lantern)最新版本下载：https://github.com/getlantern/lantern/releases/tag/latest

### 6、安装 Postman

Postman 是一个 HTTP 通信测试工具，REST API 的练习会用到它。

请到官网 https://www.getpostman.com/ 下载独立安装包；也可以参考这篇文章 http://www.cnblogs.com/mafly/p/postman.html , 下载 Chrome 浏览器的插件，它们的效果一样。

### 7、安装 Typora

Typora 是一款 Markdown 编辑器，拥有 Windows、macOS、Linux 客户端，可以算作一款 Windows 下难得的好看、优美的客户端。

请到官网 https://www.typora.io/ 下载安装包，并学会使用 markdown 语法，markdown 语法说明：https://www.appinn.com/markdown/

### 8、安装有道云笔记

有道云笔记是一款比较优秀的云笔记软件，免费账户所具备的功能已经完全足够我们使用。支持 markdown 语法，支持云端同步，支持云协作。在学习的过程中，你可以直接使用它来记笔记，也可以将写好的 markdown 笔记备份到它上面。

请到官网http://note.youdao.com/ 下载安装。

### 9、使用石墨文档

石墨文档是一款轻便、简洁的在线协作文档工具。支持多人同时对文档编辑和评论,让你与他人轻松完成协作撰稿、方案讨论、会议记录和资料共享等工作。

网页版：https://shimo.im/

### 10、使用 ProcessOn

ProcessOn 是一个在线作图工具的聚合平台，它可以在线画流程图、思维导图、UI 原型图、UML、网络拓扑图、组织结构图等等。

网页版：https://www.processon.com/
