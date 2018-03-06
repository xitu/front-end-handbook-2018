# 应用程序框架（桌面，手机，平板电脑等）工具

##### 前端应用程序框架： [^1]

* [AngularJS](https://github.com/angular/angular.js) (i.e Angular 1.x.x) + [Batarang](https://github.com/angular/angularjs-batarang)
* [Angular](https://github.com/angular/angular) (i.e. Angular 2.0.0 +) + [angular-cli](https://github.com/angular/angular-cli) 
* [Aurelia](http://aurelia.io/) + [Aurelia CLI](https://github.com/aurelia/cli)
* [Ember](http://emberjs.com/) + [embercli](https://ember-cli.com/) + [Ember Inspector](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi?hl=en)
* [Polymer](https://www.polymer-project.org/1.0/)
* [React](http://facebook.github.io/react/) + [create-react-app](https://github.com/facebookincubator/create-react-app) + [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
* [Vue.js](http://vuejs.org/) + [vue-cli](https://github.com/vuejs/vue-cli) & [Vue.js devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=en)
* [Riot](http://riotjs.com/)

##### 原生混合移动 WebView（即，浏览器引擎驱动）框架：

这些解决方案通常使用 [Cordova](https://cordova.apache.org/)、 [crosswalk](https://crosswalk-project.org/)，或自定义的 WebView 作为原生 API 的桥梁。

* [ionic](http://ionicframework.com/)
* [onsen.io](http://onsen.io/)

##### 原生混合移动开发 Webview （即浏览器引擎驱动）环境/平台/工具：

这些解决方案通常使用 [Cordova](https://cordova.apache.org/)、[crosswalk](https://crosswalk-project.org/)或自定义的 WebView 作为原生 API 的桥梁。

* [Adobe PhoneGap](http://phonegap.com/) [$]
* [cocoon.io](https://cocoon.io) [免费 $]
* [ionic hub](http://ionic.io/) [免费 $]
* [kony](http://www.kony.com/products/mobility-platform) [$]
* [Monaca](https://monaca.io/) [$]

##### 原生桌面 WebView（即浏览器引擎驱动）应用程序框架：

* [Electron](http://electron.atom.io/)
* [NW.js](https://github.com/nwjs/nw.js)

##### 原生移动应用程序框架（又名  JavaScript 原生应用）

这些解决方案在运行时使用 JS 引擎来解释 JS，并将其与原生 API 相桥接。没有使用浏览器引擎或 WebView。UI 由原生 UI 组件构建而成。

* [Flutter](https://flutter.io/)
* [NativeScript](https://www.nativescript.org/)
* [React Native](https://facebook.github.io/react-native/)
* [tabris.js](https://tabrisjs.com/) [免费 $]
* [trigger.io](https://trigger.io/how-it-works/) [$]
* [weex](https://weex.apache.org/)

##### 参考和演示应用程序:

* [todomvc.com](http://todomvc.com/)
* [RealWorld example apps](https://github.com/gothinkster/realworld) [代码]
* [Frontend Guidelines Questionnaire](https://github.com/bradfrost/frontend-guidelines-questionnaire)
* [Frontend Guidelines](https://github.com/bendc/frontend-guidelines)

##### 性能:

* [js-framework-benchmark](https://github.com/krausest/js-framework-benchmark)
* [Front-End Performance Checklist 2018](https://www.dropbox.com/s/8h9lo8ee65oo9y1/front-end-performance-checklist-2018.pdf?dl=0)

***

###### 建议:

[^1] 如果您对前端/JavaScript 应用程序开发不熟悉，我会从 [Vue.js](http://vuejs.org/) 开始。然后我会一步步转移到 [React](http://facebook.github.io/react/) 。然后我会看 [Angular 2+](https://angular.io/)、[Ember](http://emberjs.com/)、或者 [Aurelia](http://aurelia.io/)。

如果您正在构建只有少量数据交互的简单网站（即大多数情况下是静态内容网站），则应避免使用前端框架。像 [Gulp 和 jQuery](https://github.com/vigetlabs/blendid) 这样的工具可以完成很多工作，同时避免了学习和使用应用程序框架工具所带来的不必要的复杂性。

想要比 React 更小的框架，请考虑 [Preact](https://preactjs.com/)。Preact 试图用尽可能少的代码重新创建 React（或与 Mithril 类似的库）的核心提案，并为 ES2015 提供一流的支持。目前该库大约 3kb（缩小和压缩之后）。













































