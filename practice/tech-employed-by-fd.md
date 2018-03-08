# 前端开发者们使用的 Web 技术

![](../images/web-tech-employed.jpg "http://www.2n2media.com/compare-front-end-development-and-back-end-development")

<cite>Image source: <a href="http://www.2n2media.com/compare-front-end-development-and-back-end-development">http://www.2n2media.com/compare-front-end-development-and-back-end-development</a> </cite>

以下的 web 核心技术被前端开发者所使用（最好按顺序来学习它们）：

1. 超文本标签语言（又称为 HTML）
2. 级联样式表（又称为 CSS）
3. 统一资源定位器（又称为 URL）
4. 超文本传输协议（又称为 HTTP）
5. JavaScript 编程语言（又称为 ECMAScript 262）
6. JavaScript 对象表示法（又称为 JSON）
7. 文档对象模型（又称为 DOM）
8. Web API 接口（HTML5 和朋友或浏览器 API）
9. Web 内容可访问性指南（又称为 WCAG）& 可访问的富互联网应用（又称为 ARIA）


有关所有网络相关规范的综合列表，请参阅 [platform.html5.org](https://platform.html5.org/)。

上述的九个技术，在下面给出了每个技术的定义和相关文本与规范的链接。

#### 超文本标签语言（又称为 HTML）

> 超文本标签语言，常常被称为 HTML，是用于编写网页的标准标签语言。Web 浏览器可以读取 HTML 文件并将它们渲染为可视或可听的网页。HTML 描述了网站的语义结构和演示提示，使其成为标记语言，而不是编程语言。

><cite>&#8212; [Wikipedia](https://en.wikipedia.org/wiki/HTML)</cite>

大部分相关的规范与文档：

* [所有的 W3C HTML 规范](http://www.w3.org/standards/techs/html#w3c_all)
* [目前标准下的 HTML 元素](https://html.spec.whatwg.org/multipage)
* [全局属性](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)
* [W3C 标准下的 HTML 5.2](http://w3c.github.io/html/)
* [HTML 属性参考手册](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)
* [HTML 元素参考手册](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
* [HTML 语法](https://html.spec.whatwg.org/multipage/syntax.html#syntax) from the Living Standard

#### 级联样式表（又称为 CSS）

> 级联样式表（CSS）是一个样式表语言，用于描述和格式化标签语言中的文档。尽管大部分被用于改变 HTML 和 XHTML 写成的网页和用户界面的样式，但该语言实际上可以被用于任何种类的 XML 文档，包括纯 XML，SVG 和 XUL。与 HTML 和 JavaScript 结合，CSS 是被大部分网络应用、移动应用使用来创建可视的互动网页、用户界面的重要技术。

><cite>&#8212; [Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)</cite>

大部分相关的规范与文档：

* [所有的 W3C 标准下 CSS 规范](http://www.w3.org/Style/CSS/current-work#roadmap)
* [级联样式表第2版第2次修订 (CSS 2.2) 规范](https://drafts.csswg.org/css2/)
* [CSS 参考手册](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
* [第三版选择器](http://www.w3.org/TR/css3-selectors/)

#### 超文本传输协议（又称为 HTTP）

> 超文本传输协议（HTTP）是一个对分布式协作超媒体信息系统的应用协议。HTTP 是万维网数据通信的基础。

><cite>&#8212; [Wikipedia](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)</cite>

大部分相关的规范：

* [超文本传输协议 -- HTTP/1.1](https://tools.ietf.org/html/rfc2616)
* [HTTP/2](http://httpwg.org/specs/rfc7540.html)

#### 统一资源定位器（又称为 URL）

> 统一资源定位器（URL）（又称为网页地址）是一个用于定位存在于计算机网络中特定资源的参考，也指提取该资源的技术。URL 是统一资源识别器（URI）的一种，尽管很多人将这两个术语互相代指对方。URL 同时也指定了获取特定资源的方法，而这对 URI 并不适用。URL 大部分被用于代指网页（http），但也被用于文件传输（ftp），电子邮件（mailto），数据库连接（JDBC）和许多其它的应用。

><cite>&#8212; [Wikipedia](https://en.wikipedia.org/wiki/Uniform_Resource_Locator)</cite>

大部分相关的规范：

* [统一资源定位器（URL）](http://www.w3.org/Addressing/URL/url-spec.txt)
* [URL 当前标准](https://url.spec.whatwg.org/)

#### 文档对象模型（又称为 DOM）

> 文档对象模型是一个跨平台语言独立的概念，用于表示并与 HTML，XHTML 和 XML 文档中的对象交互。每个文档中的节点都被以树状组成，成为 DOM 树。在 DOM 树中的对象可以通过方法来被修改和处理。DOM 的公有接口在它的程序接口（API）中已被声明规范。

><cite>&#8212; [Wikipedia](https://en.wikipedia.org/wiki/Document_Object_Model)</cite>

大部分相关规范和文档：

* [文档对象模型 (DOM) 第三版事件规范](https://www.w3.org/TR/DOM-Level-3-Events/)
* [DOM 当前规范](https://dom.spec.whatwg.org/)
* [W3C 规范下的 DOM4](https://www.w3.org/TR/2015/REC-dom-20151119/)

#### JavaScript 编程语言（又称为 ECMAScript 262）

> JavaScript 是一个高级动态无类型解释型编程语言。它在 ECMAScript 语言规范中被标准化。与 HTML 和 CSS 一起，它是产生互联网内容的三个必要技术之一；大部分主流的网站使用它，且现代浏览器可以无插件地使用它。JavaScript 是基于原型的，以函数为第一公民的语言，这使得它有多种编程范式，支持面向对象，命令式以及函数式编程风格。它拥有处理文本，数列，日期和正则表达式的 API，但不包含任何 I/O，如网络，存储以及图像处理功能，对嵌入的环境有依赖。

><cite>&#8212; [Wikipedia](https://en.wikipedia.org/wiki/JavaScript)</cite>

大部分相关规范和文档:

* [ECMAScript® 2017 语言规范](https://tc39.github.io/ecma262/)

#### Web APIs（又称为 HTML5 和朋友）

> 当使用 JavaScript 编写网页代码时，有很多可以使用的 API。以下是你在开发你的 Web 应用或网站时可能使用到的一系列接口（也就是对象的种类）。

><cite>&#8212; [Mozilla](https://developer.mozilla.org/en-US/docs/Web/API)</cite>

大部分相关文档：

* [Web API 接口](https://developer.mozilla.org/en-US/docs/Web/API)

#### JavaScript 对象表示法（又称为 JSON）

> 这是浏览器与服务器异步通信（AJAJ）时基本的数据格式，大量地替代了 XML。尽管原先是从 JavaScript 脚本语言中提炼出来的，但 JSON 是一个与语言无关的数据格式。用于解构和生成 JSON 数据的代码在很多语言中都已经有实现。JSON 格式最早由 Douglas Crockford 提出。目前它由 RFC 7159 和 ECMA-404 两个标准进行规范化。 ECMA 标准使用者较少，仅描述了允许的语法规则，而 RFC 还提供了一些语义和安全方面的考量。官方的 JSON 互联网媒体文件类型是 application/json。JSON 的后缀名为 .json。

><cite>&#8212; [Wikipedia](https://en.wikipedia.org/wiki/JSON)</cite>

大部分相关文档和规范：

* [JSON 入门介绍](http://json.org/)
* [JSON API](http://jsonapi.org/)
* [JSON 数据交换格式](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf)

#### Web 内容可访问性指南（又称为 WCAG）& 可访问的富互联网应用（又称为 ARIA）

> 可访问性是指产品、设备、服务或环境对于残障人士的设计。可访问性设计的理念保证了『直接访问』（即无需帮助）和『间接访问』意味着与个人辅助技术的兼容性（如计算机屏幕阅读助手）。

><cite>&#8212; [Wikipedia](https://en.wikipedia.org/wiki/Accessibility)</cite>

* [可访问的富文本互联网应用（WAI-ARIA）的当前状况](http://www.w3.org/standards/techs/aria#w3c_all)
* [网络可访问性倡议（WAI）](http://www.w3.org/WAI/)
* [当前网络内容可访问性（WCAG）内容的情况](http://www.w3.org/standards/techs/wcag#w3c_all)


