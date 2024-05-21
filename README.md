# 从此刻开始改变

> 1.看react/vue源码；2.理解学习八股文知识；

| Ref | 知识名称 | 是否完成 | 备注 |
| :----: | :----: | :----: | :----: |
| 1 | 介绍下BFC | ✅2024/5/12 | 块级上下文容器，可以规避 float 后高度计算偏差问题，以及外边距折叠问题 |
| 2 | display属性有哪些值 | ✅2024/5/12 | none、inline、block、table系列、flex系列、grid系列 |
| 3 | flex布局的理解 | ✅2024/5/13 | CSS3规范新出的一种布局，同时设置display:flex创建一个弹性布局盒子。可以通过align(content，items)设置y轴的布局，通过justify(content，items)配置x轴的布局 |
| + | 流式布局的理解 | ✅2024/5/14 |
| 4 | ES6的常用语法 | ✅2024/5/14 |
| 5 | for...in 和 for...of的区别 | ✅2024/5/15 | for...in 只能遍历对象和数组、for...of 可以遍历对象、数组、字符串等所有拥有 @@iterator 可迭代协议的遍历器内容 |
| 6 | 改变this指向的方法有哪些 | ✅2024/5/15 | apply、call、bind、箭头函数、addEventListen、对象函数属性调用、闭包存储this |
| 7 | 如何实现一个call方法？说思路 | ✅2024/5/16 | 通过对象方法调用的方式改变this指向并返回结果，参考 [call 手写](https://blog.csdn.net/zsm4623/article/details/137903281)
| + | 函数调用有几种会改变 this 指向 | ✅2024/5/16 | 普通函数调用指向 window，对象方法调用指向当前的对象，构造函数方式调用指向实例对象，事件绑定方式调用指向当前的dom，定时器内部调用指向window，自执行函数调用指向window |
| + | Generator 理解 | ✅2024/5/17 |
| 8 | 数组的reduce方法有用过吗？具体的用途？ | ✅2024/5/17 | 遍历数组，可以对数组的元素进行累加，返回最终的一个值 |
| 9 | 用过git吗？常用指令？ | ✅2024/5/17 | clone(下载仓库)、pull(拉取最新代码)、commit(提交代码：-a 提交到暂存区、-m 暂存区提交到本地仓库)、push(本地仓库提交到远程git仓库)、reset(回退版本和commit提交)、log(查看提交历史)、status(查看修改状态)、merge(合并代码分支)、checkout(切换分支、-b 创建并切换到新分支)、switch(新版本创建分支、-c 创建并切换到新分支)、branch(创建分支、-d 删除分支)、remote(操作远程git仓库) |
| 10 | webpack的rule，loader的执行流是怎么样的？ | ✅2024/5/20 | rule 是 webpack 中配置文件的处理规则，在每个规则中对匹配的文件指定具体的 loader 包处理代码转换 |
| 11 | 有做过工程化的事情吗？说一下你对工程化的了解，对webpack的了解 | ✅2024/5/20 | 1、工程化指的是将项目中各个环节规范化，以至于提升开发效率和代码质量。可以说工程化现在在我们项目中无处不在。我们使用react/vue进行代码组件化、模块化的开发，使用webpack进行代码构建打包和 CICD 自动化部署。2、webpack 给我们提供了代码打包功能，通过rule规则对项目代码和静态资源进行内容转换和资源合并，它也属于项目工程化。比如提供了本地服务器，可以再本地启动react/vue等项目，支持开发react代码时可以实时编译看效果。还支持ES6的代码转换，让开发者可以进行模块化开发。 |
| 12 | 有自己写过loader、plugin吗？具体讲一下 | ✅2024/5/21 | 没有在项目上开发过，但自己平时有了解 [loader 开发](https://github.com/joeyguo/blog/issues/4)和 [plugin 开发](https://github.com/lcxfs1991/blog/issues/1) |
| 13 | CI/CD了解吗？ | ✅2024/5/21 | 持续集成/持续交付(自动化流程和工具)指的是自动化部署，像Jenkins、Docker、github、gitlab都支持配置CICD自动化部署。我自己用过Jenkins和gitlab自动化部署，配置过[gitlab的CICD](https://docs.gitlab.com/ee/ci/)部署文件。 |
| 14 | 设计模式了解吗？讲一下了解的、用过的 | - |
| 15 | 有做过性能优化吗？页面非常卡顿，卡顿不是因为数据很多，而是因为有很多计算，导致掉帧了，如何找出卡顿的原因？如何去debug找出来？如果有几百个函数需要执行，怎么去处理？ | - |
| 16 | 讲讲js数据类型 | - |
| 17 | 如何判断出一个元素是数组还是对象 | - |
| 18 | 讲讲重排重绘？ | - |
| 19 | 微任务、宏任务描述一下 | - |
| 20 | 介绍下最近的一个项目 | - |
| 21 | 研究vue2/vue3的原理 | - |
| 22 | es6的class和es5的function的关系？ | - |
| 23 | new一个对象的时候会做些什么？ | - |
| 24 | 节流函数的实现 | - |
| 25 | 跨域问题 | - |
| 26 | webpack的module、bundle、chunk分别指的是什么？ | - |
| 27 | 手写防抖、节流 | - |
| 28 | on、once、off、emit区别 | - |
| 29 | 实际开发遇到的重难点。 | - |
| 30 | 前端对算法要求不是太高，leetcode的easy全刷完，middle刷几个高频题就行 | - |
| 31 | react、vue 有哪些性能优化方式 | - |
| 32 | 介绍一下你在上家公司的主要工作 | - |
| 33 | 在这个项目中做的性能优化的事情有哪些？ | - |
| 34 | webworker中为什么能提升js执行的性能？ | - |
| 35 | 你是怎么使用webworker的？ | - |
| 36 | 浏览器内存你在实战中处理过吗？ | - |
| 37 | 浏览器的垃圾回收机制是什么样的？ | - |
| 38 | 微前端的理解 | - |
| 39 | webpack打包流程是什么？ | - |
| 40 | 小程序跟H5的区别是什么？ | - |
| 41 | 手写Promise的方法理解以及手写Promise.all | - |
| 42 | 前端监控如何设计 | - |
| 43 | 密码校验，要求包含大小写字母，数字，长度为6，至少满足三个条件 | - |
| 44 | 布局适配问题，响应式，rem，em，flex等 | - |
| 45 | 低代码如何设计的 | - |
| 46 | react路由原理 | - |
| 47 | react生命周期 | - |
| 48 | 什么是回调地狱，如何解决 | - |
| 49 | js文件相互引用有什么问题？如何解决 | - |
| 50 | 一个很大的json文件，前端读取如何优化 | - |
| 51 | jwt和session有什么区别 | - |
| 52 | qiankun的js沙箱和css沙箱原理是啥 | - |
| 53 | 你觉得这个低代码平台跟别的比有什么优势或者有什么亮点吗？ | - |
| 54 | SDK详解 | - |
| 55 | 脚手架搭建 | - |
| 56 | 前端请求如何避免明文传输 | - |
| 57 | 大文件上传 | - |
| 58 | 缓存优化 | - |
| 59 | 滑动 text-area标签用什么属性 | - |
| 60 | 闭包 | - |
| 61 | 高阶组件 | - |
| 62 | 项目的打包产物，是否还需要对 promise, async/await 这些语法进行 polyfill，2024 年了，我们的 babel 还有必要把 es6 语法转为 es5 吗？ | - |
| 63 | 组件库，基本上大家都在用，那么组件库是如何实现按需加载的？或者你的项目中，组件库是否是正常按需加载的吗？组件库的组件，应该提供哪些打包产物呢？你的项目中又是什么样的产物呢？对于样式文件，有哪些处理方案呢？各自的优劣如何？ | - |
| 64 | react 中的多次渲染如何优化，为什么需要全局状态管理，context 如何避免不必要的渲染，对于 redux 有多少了解，它的中间件思想可以拿出来用到项目中吗？ | - |
| 65 | 建议候选者，对自己的项目一定要进行深挖，涉及到的相关知识点，务必要吃透。比如写了在用 redux，那么势必就需要对其原理有比较多的了解。 | - |
| 66 | js原型链 | - |
| 67 | aysnc 和 derfer的区别 | - |
| 68 | http1.1/http2/http3 的区别，keep-alive的作用 | - |
| 69 | TCP三次握手以及TCP队头阻塞问题，如何解决 | - |
| 70 | 说下你理解的hook | - |
| 71 | 从全链路角度分析性能优化 | - |
| 72 | http 队头阻塞问题，如何解决 | - |
| 73 | 前端脚手架的意义 | - |
| 74 | vue react 区别，如何理解虚拟dom | - |
| 75 | 原型链以及继承 call/apply/bind | - |
| 76 | 事件循环，流程控制方面的 | - |
| 77 | promise 的方法理解 | - |

