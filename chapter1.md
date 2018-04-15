## 2.0 Servlet简介
---
Servlet是用Java编写的服务器端程序，主要功能在于交互式地浏览和修改数据，生成动态Web内容。它是作为来自Web浏览器或其他 HTTP 客户端的请求和 HTTP 服务器上的数据库或应用程序之间的中间层。

## 2.1 Servlet生命周期
---
Servlet 生命周期可被定义为从创建直到毁灭的整个过程。以下是 Servlet 遵循的过程：

1.Servlet 通过调用 init () 方法进行初始化。

2.Servlet 调用 service() 方法来处理客户端的请求。

3.Servlet 通过调用 destroy() 方法终止（结束）。

4.最后，Servlet 是由 JVM 的垃圾回收器进行垃圾回收的。
