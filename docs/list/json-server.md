### 简介

#### 什么是 REST？

要解释什么是 REST，你应该先了解什么是 API（Application Programming Interface,应用程序编程接口），形象一点说就是像一个公司比如腾讯，阿里巴巴之类，他们可以提供一个 API，然后我们或者一些其他的小公司可以编一个软件去跟这个接口（API）进行相连或交互。举个例子，比如你可以用手机的其他软件分享内容到微信朋友圈或者新浪微博，这些软件就是与微信和微博的 api 进行了交互。

知道了 API，那么就容易理解 REST 了。

REST 是 Representational State Transfer（具象状态传输） 的缩写。它是一种用于传递信息的架构风格。它使通过简单的 HTTP 来在不同的软件或程序中互相专递信息变成可能。 我们针对一个 URL 通过不同类型的 HTTP 请求来对对应的用户信息（资源）进行对应的请求（例如 GET 为获取，POST 为创建，DELETE 为删除等等），而不是使用不同的 URL 对资源进行直接的请求。

举个例子，如果需要删除一个用户。我们需要做的仅仅是对 /user/10 发出一个 `DELETE` 的请求，而不是对 /deleteuser?id=10 发出一个 GET 请求。 （这样的操作更简洁也更有意义）

#### 为什么我们需要一个模拟 API？

REST API 提供了移动应用以及 Web 应用的后端支持。有些时候当你在进行开发时，你需要的后端接口可能还没有完成对于开发所需要的支持。 我们需要一个模拟 API 提供一些伪造数据来模拟真实环境下的移动应用和 Web 应用的使用场景。

这就是我们为什么需要模拟 REST API 的原因。json-server 可以很轻易的满足我们的这些需求。

### 学习要求

* 学会使用 json-server 模拟 REST API

### 学习资源

* https://github.com/typicode/json-server
* [使用 json-server 模拟 REST API](https://www.cnblogs.com/itfantasy/p/6043111.html)
* [使用 json-server 模拟服务器 API](https://www.jianshu.com/p/5bb86a770e23)
