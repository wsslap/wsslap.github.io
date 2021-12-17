JavaScript 的核心语法其实很精简，只包括了：

- 基本的语法构造：操作符、控制结构、语句等；
- 标准库：Array（数组）、Date（日期时间）、Math（数学库）等等；
- 除此之外的所有其他特性，都是由宿主所提供的API，仅仅是通过JavaScript进行调用。

如浏览器，它额外提供了如下三大类API：
- 浏览器控制类：操作浏览器
- DOM（文档对象模型，在Mozilla官方网站，它也属于Web API）类：操作网页的各种元素
- Web类：实现互联网的各种功能

若是服务器（Node.js），则会提供各种和服务提供相关的API，如：

- 文件操作API
- 网络通信API
- 进程和线程API
- 性能和监控API
  
……

而移动或者桌面应用的API，则都与操作系统特性紧密相关，如：文件操作、系统通知、硬件交互等等。我最常用的代码编辑器Visual Studio Code其实就是基于JavaScript（微软开发的JavaScript超集TypeScript）开发的，所以现在流行的“全栈”（Full Stack）主要是基于JavaScript提出，也是当今几乎唯一的真正全栈开发语言。

著名程序员 Jeff Atwood 甚至提出了一条Atwood定律：
#### **Any application that can be written in JavaScript will eventually be written in JavaScript.** <!-- {docsify-ignore} -->

## [开始学习](01/javascript/gaishu)<!-- {docsify-ignore} -->