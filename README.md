#前端记录

 > 本文主要简单记录一些个人学习过程中的一些觉得不错的内容跟工具，大部分是前端开发的相关内容。

 > 受限于个人知识、喜好、懒惰，很多内容都没涉及到。



####您可以通过以下方式联系到我：
 - 邮箱 menghui9898@gmail.com
 - 博客 [ferecord.com](http://www.ferecord.com/ "前端记录 ")
 - Twitter [@Tumars](https://twitter.com/Tumars)

 **若转载本文请注明来源**

---

## 目录
 - [前端综合资源](#resource)
 - [前端博客](#blog)
 - 前端框架
 	- [react](#react)
 - [CSS 相关](#css)
 - 构建工具
 	- [gulp](#gulp)
 	- [webpack](#webpack)
 - 代码编辑器
 	- [sublime text](#sublime)
 - [小结](#summary)


---

<h3 id="resource">前端综合资源</h3>

 > 与本篇文章类似的一些前端资源导航

 名称 | 备注/说明 
 ----- | ----- 
[前端瑞士军刀](https://github.com/nieweidong/fetool) | 相当全面的一篇资源总结，不止包括前端
[QQ前端群交流群规](https://github.com/jsfront/src/blob/master/qq.md) | 看了让你跪的前端交流群群规，下方有大量资源 



<h3 id="blog">前端博客</h3>

  > 一些不错的团队或个人博客，部分是英文博客，建议全部加进 RSS 订阅里。

  > 这篇[《front-end-collect》](https://github.com/foru17/front-end-collect)总结的更全面，包括了各种前端组织、博客、微博、期刊、书籍等。

  > 我这里只写一些个人订阅的常看的博客。

 名称 | 备注/说明 
 ----- | ----- 
[CSS-Tricks](https://css-tricks.com/) | 大名鼎鼎，更新量很大，每日必看
[codrops](http://tympanus.net/codrops/) | 设计的很漂亮的高质量前端博客
[smashingmagazine](https://www.smashingmagazine.com/) | 涉及到很多设计内容的前端博客
[腾讯 AlloyTeam](http://www.alloyteam.com/) | 腾讯前端团队
[百度 FEX](http://fex.baidu.com/) | 百度前端团队
[淘宝 FED](http://taobaofed.org/) | 淘宝前端团队
[奇舞团](http://www.75team.com/) | 360 前端团队
[前端乱炖](http://www.html-js.com/) | 前端社区太多，乱炖还算做的不错的
[前端外刊评论 - 知乎专栏](https://zhuanlan.zhihu.com/FrontendMagazine) | 知乎作为一个初期几乎全是程序员的网站，也是有相当多的前端开发
[WEB前端开发](http://www.css88.com/) | 很多人都知道的 css88，收集了很多类库的中文文档
[W3Cplus](http://www.w3cplus.com/) | 大漠(《图解 CSS3》作者)在国内的影响力杠杠的 Sass 专家级
[阮一峰](http://www.ruanyifeng.com/blog/) | 其文章简洁易懂深入浅出，关注多年，著作[《ECMAScript 6标准入门》](http://es6.ruanyifeng.com/)
[张鑫旭](http://www.zhangxinxu.com/wordpress/) | 成名多年的、高产的前端大湿
[轩枫阁](http://www.xuanfengge.com/) | 设计跟内容做的很好的博客，博主是个2014级的毕业生（感觉比 13 年毕业的我厉害好多）（手动泪目）




###前端框架

<h4 id="react">react</h4>

  > Facebook 旗下 js 框架， learn one，write anywhere

 名称 | 备注/说明 
 ----- | ----- 
[react官方文档](https://facebook.github.io/react/docs/) | 官方文档，看看 api 挺好，这里有其中文网[汉化文档](http://reactjs.cn/react/docs/getting-started.html)
[Redux](http://redux.js.org/) | 跟 react 配合的最好的状态容器，解决了 react 的 props 不能跨 components 传递的问题，这里有其[汉化版文档](https://camsong.github.io/redux-in-chinese/index.html)
[React-Native学习指南](https://github.com/ele828/react-native-guide) | 新玩意层出不穷... 对于能持续学习的童鞋，这是个美好的时代
[React 编程规范](https://github.com/dwqs/react-style-guide) | React 编程的各种基本规则
[react redux react-router antd](https://github.com/yinzSE/webpack-react-redux-express-boilerplate) | 一个使用了redux、react-router、express 的模板，很不错，功能全面，可以学习下




<h3 id="css">CSS 相关</h3>

  > CSS 的发展相对遍地开花的 JavaScript 慢了很多，前几年只能从 bootstrap ，purecss 等类库上做文章，之后less、sass等预处理器，PostCSS 及基于它的插件，CSS 模块化，让 CSS 开发繁荣了起来

 名称 | 备注/说明 
 ----- | ----- 
PostCSS | 大名鼎鼎的 [Autoprefixer](https://github.com/postcss/autoprefixer)、[styleLint](https://github.com/stylelint/stylelint) 等就是其插件，推荐大漠的文章[《PostCSS深入学习》](http://www.w3cplus.com/PostCSS/postcss-deep-dive-what-you-need-to-know.html)
CSS Modules | css 模块化，前端组件模块化的最后一道坎，可以看CSS trick里的系列文章 [css-modules](https://css-tricks.com/css-modules-part-1-need/)，知乎专栏的[《CSS Modules 详解及 React 中实践》](https://zhuanlan.zhihu.com/p/20495964)也可参考一下
CSSX | 类似于 JSX ，一种写在 JavaScript 里的 css 语法，可以看[《Finally, CSS In JavaScript! Meet CSSX》](https://www.smashingmagazine.com/2016/04/finally-css-javascript-meet-cssx/)这篇文章了解下
 | 
[anicollection](http://anicollection.github.io/#/) | CSS3 动画库，收集了常用的 CSS3 进入、退出、闪动等动画
[CSS3 loading](http://www.yunrui.co/26261.html) | 文章收集了很多 css loading 动画，这里还有个 [css & svg loading](https://codegeekz.com/best-css-svg-loaders-and-spinners/) 收集也很全面
[css3gen](http://css3gen.com/) | 一个 css3 工具，调整一些细致的 css3 动画、3D效果、滤镜、阴影时可以使用这个
[字蛛 font-spider](http://font-spider.org/) | 腾讯出品的中文字体压缩器，把需要的文字从字体文件里挑出来，大幅压缩字体文件




###构建工具

<h4 id="gulp">gulp</h4>

 > 最流行的前端自动化工具，在 npm 上有非常多插件，几乎解决所有前端常见自动化问题

 名称 | 备注/说明 
 ----- | ----- 
[Gulp for Beginners](https://css-tricks.com/gulp-for-beginners/) | gulp 基础入门，介绍了 gulp 的功能跟使用，介绍的几个插件都很有用
[前端构建工具gulpjs的使用介绍及技巧](http://www.dtao.org/archives/18) | 讲的很详细 
[gulp 官网](http://www.gulpjs.com.cn/) | gulp 的官网




<h4 id="webpack">webpack</h4>

 > 打包工具，react 开发下的构建神器，与 gulp 等自动化构建工具有功能上的重合，配合 gulp-webpack 插件可与 gulp 一块使用

 名称 | 备注/说明 
 ----- | ----- 
[Webpack vs Require.js vs Browserify](http://hackhat.com/p/110/module-loader-webpack-vs-requirejs-vs-browserify/) | 一篇文章告诉你为什么 webpack 比 require、browserify 好
[webpack-howto](https://github.com/petehunt/webpack-howto) | webpack 的入门文档，简单易懂，讲了些基本功能
[webpack入门指迷](https://segmentfault.com/a/1190000002551952) | segmentfault 上的一篇文章，讲了几个常用插件，建议去每个插件的 github 页面看文档，更详细页更正确
[webpack官方文档](http://webpack.github.io/docs/) | 非常详细，不过 plugin 或 loader 的问题还是建议去他们的 github 页面看
[基于webpack搭建前端工程解决方案探索](https://segmentfault.com/a/1190000003499526) | 基于 webpack 的环境搭建、目录结构、资源管理等
[webpack使用优化](http://www.alloyteam.com/2016/01/webpack-use-optimization/) | 腾讯前端团队的博客文章
[webpack-demos 阮一峰](https://github.com/ruanyf/webpack-demos) | 大神阮一峰的 webpack 配置及使用 demo，涉及了开发过程中常用的 plugin、loader、chunk 等的使用与配置
[react-hot-loader](http://gaearon.github.io/react-hot-loader/getstarted/) | 开发 react 一定要装的一个 loader，类似  gulp 里常用的的 browserSync，实现代码热替换，配合其他 loader 功能更强



###代码编辑器

<h4 id="sublime">sublime</h4>

 > 前端用的最多的代码编辑器（除了 webstrom 外）

 名称 | 备注/说明 
 ----- | ----- 
[Sublime Text下载、使用教程、插件推荐说明、全套快捷键](http://www.ferecord.com/sublimetext3.html) | 我自己的博客文章，当时总结的很详细
[package control](https://packagecontrol.io/) | sublime 的插件网站，所有的插件、主题等都在上面了，善用插件会让编辑器变得强大无比，节省生命，增加开发愉悦感
[emmet 快捷键文档](http://docs.emmet.io/cheat-sheet/) | emmet 的快捷键文档，极大提升敲代码速度 
[Sublime Text 3 搭建 React.js 开发环境](https://segmentfault.com/a/1190000003698071) | 开发 react 项目时必装的几个ST插件



<h3 id="summary">小结</h3>

####背景

网上的前端导航类的总结非常多，文头提到的 [前端瑞士军刀](https://github.com/nieweidong/fetool) 就是此类文章中集大成者。
我的Evernote、浏览器书签里收藏了很多前端相关的文章跟知识点，一直想梳理下做个总结，就把部分内容总结到这篇文章上，希望以此为契机逐步完善。


####目标

很多基础的或者其他资源里内容我都没写，比如 grunt、angular.js、less/sass、Bootstrap 等等。
主要是因为希望这个资源总结能做的比较精简（其实已经写了内容里也有些是想删掉的）。
另外一些知识比如 node.js、git 等了解不是很深入，也还没写，以后会添加进来。
还有一些因为懒惰没写，也会在以后逐步添加完善。


####待添加内容
- [ ] node.js
- [ ] git
- [ ] 框架 —— vue.js
- [ ] js相关
- [ ] 软件推荐
	- [ ] windows
	- [ ] app
	- [ ] chrome 插件
