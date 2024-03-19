---
时间: 2023-12-03
作者: 张轩
标题: Vue3.0(正式版) + TS 仿知乎专栏企业级项目 深度剖析Vue3新特性
图片: data:image/jpeg;base64,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
链接: http://docs.vikingship.xyz/
评价: ★★★★★
文件地址: https://pan.quark.cn/list#/list/all/0cd0276c0722460397ae9b0120712284-00%E6%B1%9F%E9%B9%8F%E5%88%A9/d1c90b69abbf4b16a906693cdb2ea993-00%E6%B1%9F*101%E5%89%8D%E7%AB%AF*101%E8%A7%86%E9%A2%91/721555bc753c41ddb26c0bb42e009ec5-Vue3.0(%E6%AD%A3%E5%BC%8F%E7%89%88)%20+%20TS%20%E4%BB%BF%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F%E4%BC%81%E4%B8%9A%E7%BA%A7%E9%A1%B9%E7%9B%AE%20%E6%B7%B1%E5%BA%A6%E5%89%96%E6%9E%90Vue3%E6%96%B0%E7%89%B9%E6%80%A7
tags:
---



#  [视频地址](https://pan.quark.cn/list#/list/all/0cd0276c0722460397ae9b0120712284-00%E6%B1%9F%E9%B9%8F%E5%88%A9/d1c90b69abbf4b16a906693cdb2ea993-00%E6%B1%9F*101%E5%89%8D%E7%AB%AF*101%E8%A7%86%E9%A2%91/721555bc753c41ddb26c0bb42e009ec5-Vue3.0(%E6%AD%A3%E5%BC%8F%E7%89%88)%20+%20TS%20%E4%BB%BF%E7%9F%A5%E4%B9%8E%E4%B8%93%E6%A0%8F%E4%BC%81%E4%B8%9A%E7%BA%A7%E9%A1%B9%E7%9B%AE%20%E6%B7%B1%E5%BA%A6%E5%89%96%E6%9E%90Vue3%E6%96%B0%E7%89%B9%E6%80%A7)

- **项目演示站点：[http://zhihu.vikingship.xyz/](http://zhihu.vikingship.xyz/)**
- 在线后端API 查询和使用站点：[http://api.vikingship.xyz/](http://api.vikingship.xyz/)
- 项目在线文档：[http://docs.vikingship.xyz/](http://docs.vikingship.xyz/)
- 完成的组件库展示：[http://showcase.vikingship.xyz/](http://showcase.vikingship.xyz/)
- 流程图和原型图
- 购买后直接可以接入使用的真实后端API

# 项目目录

- ##### 第1章 课程介绍 试看2 节 | 18分钟
    
    本章节介绍整个课程的内容，让大家了解课程的核心和安排。
    - 1-1 课程介绍（导学 ） (13:24)试看
    - 1-2 代码库和在线文档使用注意事项（必看） (03:53)
    
- ##### 第2章 你好 Typescript： 进入类型的世界20 节 | 131分钟
    
    本章主要帮助大家理解 TypeScript 可以解决的问题和所带来的优势，带领大家学习 TS 中的各种基础类型，然后进阶到复杂类型，包括：Array, Tuple, interface, function, Class, Enum, Generices等，迅速帮助大家理解 TS 的基础使用方式和语法。
    - 2-1 什么是 Typescript (05:54)
    - _图文：_2-2 安装 Typescript 文档
    - 2-3 为什么要学习 typescript (06:04)
    - 2-4 安装 typescript (05:59)
    - 2-5 原始数据类型和 Any 类型 (06:04)
    - 2-6 数组和元组 (06:52)
    - 2-7 Interface- 接口 初探 (05:40)
    - 2-8 函数 (06:52)
    - 2-9 类型推论 联合类型和 类型断言 (07:43)
    - 2-10 枚举（Enum） (07:11)
    - 2-11 泛型（Generics） 第一部分 (07:28)
    - 2-12 泛型（Generics） 第二部分 - 约束泛型 (06:07)
    - 2-13 泛型第三部分 - 泛型在类和接口中的使用 (08:47)
    - 2-14 类型别名，字面量 和 交叉类型 (07:12)
    - 2-15 声明文件 第一部分 (13:22)
    - 2-16 声明文件 第二部分 (10:31)
    - 2-17 内置类型 (08:33)
    - 2-18 配置文件 (10:31)
    - _作业：_2-19 【讨论题】对 Typescript 初步学习后的印象和困惑
    - _作业：_2-20 为 clipboard.js 开源库添加简化版的定义文件
    
- ##### 第3章 初识 Vue3.0： 新特性详解27 节 | 189分钟
    
    首先浏览 vue3 新带来的变化，然后从为什么会有 vue3 引出话题， 带领大家学习 compostion API，自定义Hooks，Teleport，Suspense 和 全局 API 修改等一系列 vue3 的重大更新。
    - 3-1 vue3 新特性巡礼 (04:45)
    - 3-2 为什么会有 vue3 (07:09)
    - 3-3 使用 vue-cli 配置 vue3 开发环境 (08:42)
    - 3-4 使用 vite 创建项目 (06:36)
    - 3-5 代码结构分析以及推荐插件安装 (11:11)
    - 3-6 使用 eslint 规范代码 (11:20)
    - 3-7 vue3 - ref 的妙用 (08:20)试看
    - 3-8 更近一步 - reactive (10:14)
    - 3-9 vue3 响应式对象的新花样 (06:51)
    - 3-10 老瓶新酒 - 生命周期 (07:00)
    - 3-11 侦测变化 - watch (07:16)
    - 3-12 vue3 模块化妙用- 鼠标追踪器 (09:04)
    - 3-13 模块化难度上升 - useURLLoader (09:40)
    - 3-14 模块化结合typescript - 泛型改造 (08:28)
    - _图文：_3-15 新版 axios 出现 “unknown” 错误的解决方案
    - 3-16 Typescript 对 vue3 的加持 (05:48)
    - 3-17 Teleport - 瞬间移动 第一部分 (05:47)
    - 3-18 Teleport - 瞬间移动 第二部分 (09:16)
    - 3-19 Suspense - 异步请求好帮手第一部分 (05:10)
    - 3-20 Suspense - 异步请求好帮手第二部分 (06:31)
    - 3-21 Provide - Inject (11:31)
    - 3-22 全局 API 修改 (07:13)
    - 3-23 setup 语法糖 基础 (07:33)
    - 3-24 setup 语法糖 进阶- (12:51)
    - _作业：_3-25 【谈一谈】经过新特性的学习
    - _作业：_3-26 【讨论题】你对 vue3 的 composition API
    - _作业：_3-27 【学习任务】写一个 hooks 函数，来监听键盘的按键
    
- ##### 第4章 项目起航 - 准备工作和第一个页面12 节 | 96分钟
    
    本章从项目的需求开始分析，然后确定项目的整体结构和代码规范，并且为项目选择 Bootstrap 作为样式库，编写 ColumnList 和 GlobalHeader 完成简单的练手以后，开始挑战第一个比较复杂的 Dropdown 下拉菜单组件，最后还抽象抽象出第一个 hooks 函数。...
    - 4-1 项目起航 需求分析 (10:42)
    - 4-2 文件结构和代码规范 (09:20)
    - 4-3 样式解决方案简介和分析 (07:37)
    - 4-4 设计图拆分和组件属性分析 (05:31)
    - 4-5 ColumnList 组件编码 (10:58)
    - 4-6 ColumnList 组件使用 Bootstrap 美化 (09:56)
    - 4-7 GlobalHeader 组件编码 (08:29)
    - 4-8 Dropdown 组件基本功能编码 (08:41)
    - 4-9 Dropdown 组件添加 DropdownItem (08:16)
    - 4-10 Dropdown 组件点击外部区域自动隐藏 (08:35)
    - 4-11 useClickOutside 第一个自定义函数 (07:27)
    - _作业：_4-12 【讨论题】谈谈你在工作中常用的样式解决方案？
    
- ##### 第5章 表单的世界 - 完成自定义 Form 组件13 节 | 81分钟
    
    本章来到表单的世界，从头到尾非常完整的完成了一个带验证表单组件的全流程开发过程，在整个过程中，我们还学习到了 v-model，$attrs, slot，组件父子通讯 和 mitt 的各种知识点。
    - 5-1 web 世界的经典元素 - 表单 (04:56)
    - 5-2 ValidateInput 第一部分 — 简单的实现 (08:28)试看
    - 5-3 ValidateInput 第二部分 —抽象验证规则 (12:38)
    - 5-4 ValidateInput 第三部分 — 支持 v-model (11:57)
    - 5-5 ValidateInput 编码第四部分 — 使用 $attrs 支持默认属性 (07:35)
    - _作业：_5-6 【讨论题】谈谈扩展 ValidateInput 的验证功能
    - 5-7 ValidateForm 组件需求分析 (04:21)
    - 5-8 ValidateForm 编码第一部分 - 使用插槽 slot (09:17)
    - 5-9 ValidateForm 编码第二部分 - 尝试父子通讯 (08:09)
    - 5-10 ValidateForm 编码第三部分 - 寻找外援 mitt (05:49)
    - _图文：_5-11 使用新版 mitt 时报出类型错误的解决方案
    - 5-12 ValidateForm 编码第四部分 - 大功告成 (07:27)
    - _作业：_5-13 学习任务：扩展ValidateForm的功能，完成清空功能
    
- ##### 第6章 请你吃全家桶 - 初步使用 vue-router 和 vuex15 节 | 103分钟
    
    本章从 SPA 的概念引出，完成了 vue-router 的安装，然后学习它的基本使用，获取信息，动态跳转，前置守卫和元信息等各种知识点，然后又介绍了状态管理工具的具体定义，从而引出 vuex 的安装 和 它的 state，mutation，getter 等多个基本知识点。...
    - 6-1 什么是 SPA（Single Page Application） 应用？ (06:54)
    - 6-2 添加路由页面基础结构 (06:30)
    - _图文：_6-3 添加路由页面基础结构代码地址
    - 6-4 vue-router 安装和使用 (05:24)
    - 6-5 vue-router 配置路由 (07:14)
    - 6-6 vue-router 添加路由 (11:39)
    - 6-7 添加 columnDetail页面 (08:02)
    - 6-8 状态管理工具是什么 (06:55)
    - _图文：_6-9 ColumnDetail 代码提交详情
    - 6-10 Vuex 简介和安装 (08:17)
    - 6-11 Vuex 整合当前应用 (12:26)
    - 6-12 使用 Vuex getters (05:52)
    - 6-13 添加新建文章页面 (10:03)
    - 6-14 Vue router 添加路由守卫 - 前置守卫 (07:56)
    - 6-15 Vue router 添加路由守卫 - 使用元信息完成权限管理 (05:39)
    
- ##### 第7章 前后端结合 - 项目整合后端接口12 节 | 88分钟
    
    本章从 前后端分离和 RESTful 概念入手，介绍了为学生提供的 swagger 调试工具如何使用，然后引入 axios，通过 vuex action 的添加，实现 async 改造 和 axios 拦截器的基本用法，最后还抽象出一个 Loader 组件的编码和实现过程。
    - 7-1 前后端分离开发是什么 (07:29)
    - 7-2 RESTful API 设计理念 (10:01)
    - 7-3 使用 swagger在线文档查看接口详情 (10:43)
    - 7-4 axios 的基本用法和独家后端API 使用（必看） (09:00)
    - _图文：_7-5 后端Icode终极使用方案
    - 7-6 使用vuex action 发送异步请求 (11:17)
    - 7-7 使用vuex action 发送异步请求第二部分 (08:23)
    - _图文：_7-8 CreatePost 页面 ColumnId 类型报错的解决方案
    - 7-9 使用 async 和 await 改造异步请求 (08:22)
    - 7-10 使用axios拦截器添加loading效果 (07:19)
    - 7-11 Loader 组件编码第一部分 - 基本实现 (08:42)
    - 7-12 Loader 组件编码第二部分 - 使用 Teleport 进行改造 (06:38)
    
- ##### 第8章 通行凭证 - 权限管理12 节 | 100分钟
    
    本章从 获取 token 为起点，讲述了 JWT 通用身份验证工具的原理和实现，然后完成了 axios 设置通用header 和 持久化登录的处理方法，之后还添加了全局通用错误处理，最后抽象出一个通用组件 Message 的编码和实现过程。
    - 8-1 登录第一部分 获取token (08:09)
    - 8-2 jwt 的运行机制 (09:00)
    - 8-3 登录第二部分 axios 设置通用 header (10:08)
    - 8-4 登录第三部分 持久化登录状态 (07:47)
    - 8-5 通用错误处理 (07:00)
    - 8-6 创建 Message 组件 (10:02)
    - 8-7 Message 组件改进为函数调用形式 (11:05)
    - 8-8 了解 Vnode 以及 vue 的简单工作原理 (10:17)
    - 8-9 创建 Vnode 以及使用 render function (10:23)
    - 8-10 使用 h 函数改造 message 组件 (06:54)
    - 8-11 作业：注册页面的编写 (09:06)
    - _作业：_8-12 【学习任务】完成注册页面的功能
    
- ##### 第9章 道高一尺 - 上传组件10 节 | 95分钟
    
    本章实现了 Upload 组件从分析，编码的全过程，在这个过程中，我们将会学到：上传文件的原理，使用 axios 完成文件上传的方法，循序渐进的完成一个复杂组件的开发流程。
    - 9-1 上传组件需求分析 (06:38)
    - 9-2 上传文件的两种实现方式 (10:32)
    - 9-3 (打点 时间) Uploader 组件第一部分 (12:50)
    - 9-4 Uploader 组件第二部分 (10:12)
    - 9-5 Uploader 组件第三部分：自定义模版 (08:17)
    - 9-6 改进路由验证系统 (09:26)
    - 9-7 创建文章页面实现 Uploader 自定义样式 (11:15)
    - 9-8 大功告成 创建文章最后流程 (15:49)
    - 9-9 作业 完成文章详情页 (09:42)
    - _作业：_9-10 【学习任务】完成文章详情页的编码
    
- ##### 第10章 最终的功能 - 编辑和删除文章10 节 | 112分钟
    
    通过完成文章的编辑和删除功能，引出了之前组件留下的几个 bug，通过解决bug 带给大家持续优化的思路和方案，最后完成了一个通用 Modal 组件的编码过程。
    - 10-1 添加编辑和删除区域 (09:18)
    - 10-2 修改文章编码 第一部分 - 改进 Uploader 组件 (09:48)
    - 10-3 修改文章编码 第二部分 - 改进 ValidateInput 组件 (08:49)
    - 10-4 修改文章编码 第三部分 - 完成编辑功能 (10:52)
    - 10-5 Modal组件编码 (10:56)
    - 10-6 完成删除文章功能 (08:00)
    - 10-7 集成 Easymde 编辑器 第一部分：简介，初步安装和使用 (11:43)
    - 10-8 集成 Easymde 编辑器 第二部分：初步组件化- (19:34)
    - 10-9 集成 Easymde 编辑器 第三部分：暴露方法 (08:50)
    - 10-10 集成 Easymde 编辑器 第四部分：结合页面完成功能 (13:32)
    
- ##### 第11章 持续优化11 节 | 83分钟
    
    通过分析发现应用中可以优化的两个部分，提出并编码 数组改成对象 的store 优化方案以及防止重复请求的解决方案。最后还抽象除了 useLoadMore 的逻辑实现，最终完成了一个复杂的自定义 Hooks。
    - 11-1 可以优化的两个点 (07:50)
    - 11-2 完成帮助函数 (09:58)
    - 11-3 将 store 中的数组转换成对象 (08:25)
    - 11-4 防止重复请求逻辑分析 (05:30)
    - 11-5 缓存优化 第一部分 (09:33)
    - 11-6 缓存优化 第二部分 (06:46)
    - 11-7 useLoadMore 实现分析 (06:22)
    - 11-8 useLoadMore 编码 (07:22)
    - 11-9 useLoadMore 在首页实践 (10:35)
    - 11-10 useLoadMore 支持数据缓存 解决方案分析 (04:57)
    - 11-11 实现分页缓存逻辑 (05:30)
    
- ##### 第12章 项目构建和部署10 节 | 70分钟
    
    从生产环境的概念以及生产环境和开发环境的异同的概念开始，接着实践了应用构建，构建代码上线，和构建代码持续集成的一系列概念。
    - 12-1 生产环境和开发环境的异同 (06:23)
    - 12-2 为生产环境生成代码 (07:48)
    - 12-3 使用 vite 构建代码 (10:45)
    - 12-4 vite 对阵 vue-cli：为什么快？ (07:06)
    - 12-5 服务器的概念 (06:06)
    - 12-6 nginx 概念简介 (07:25)
    - 12-7 使用 gitee pages 进行部署 (04:38)
    - 12-8 nginx安装和配置访问静态文件 (05:35)
    - 12-9 nginx 配置代理服务 (07:07)
    - 12-10 上传代码到云主机 (06:22)
    
- ##### 第13章 2023年更新-学习新的状态管理工具 Pinia 并且重构整个应用18 节 | 174分钟
    
    Vue3 的生态系统发展迅速，2023年特别更新新的官方状态管理工具 Pinia 的内容，从基础的概念 State/Getter/Action 入手，然后深入核心和难点，使用 Pinia 重构整个项目的状态管理，最终达到对于 Pinia 的完美掌握。
    - 13-1 Pinia 简介 (07:05)
    - 13-2 安装 Pinia 以及第一个概念State (10:57)
    - 13-3 Pinia State 第二部分 (12:27)
    - 13-4 Pinia Getter概念学习 (10:40)
    - 13-5 Pinia Actions 概念学习 (10:17)
    - 13-6 Pinia Setup方式创建 Store (07:27)
    - 13-7 Store 重新设计 (06:18)
    - 13-8 Pinia 改造第一部分-修改 Global Store (09:46)
    - 13-9 Pinia 改造第二部分 - UserStore (09:56)
    - 13-10 UserStore 添加到应用：第一部分 (08:57)
    - 13-11 UserStore 添加到应用：第二部分 (10:39)
    - 13-12 Pinia 改造第三部分 - Column Store 的设计与编码 (15:31)
    - 13-13 ColumnStore 编码第二部分：在应用中使用 (11:25)
    - 13-14 重构 useLoadMore (11:05)
    - 13-15 Pinia 改造第四部分 - 分析 PostStore 的结构 (06:32)
    - 13-16 完成 PostStore 编码 (12:07)
    - 13-17 分析 PostStore 在应用中的功能点 (05:37)
    - 13-18 Pinia 总结 (06:17)
    
- ##### 第14章 课程总结1 节 | 6分钟
    本章节带领大家回顾课程的内容。
    - 14-1 课程总结 (05:57)
# [#](http://docs.vikingship.xyz/#%E7%9F%A5%E8%AF%86%E7%82%B9)知识点

### [#](http://docs.vikingship.xyz/#typescript)Typescript

- 简单类型
- 复杂类型
- 接口-Interface
- 类 - Class
- 泛型 - Generics
- 声明文件

### [#](http://docs.vikingship.xyz/#vue3)Vue3

- Ref 和 Reactive
- watch 和 computed
- 生命周期
- 自定义函数 Hooks
- Teleport 和 Suspense
- 全局 API 修改
- 复杂组件设计和实现

### [#](http://docs.vikingship.xyz/#vue-router)Vue Router

- 基本用法
- 动态路由匹配
- 导航守卫
- 路由元信息

### [#](http://docs.vikingship.xyz/#vuex)Vuex

- 基本概念
- State
- Getter
- Mutation
- Action
- 中大型Store 结构设计与实现

### [#](http://docs.vikingship.xyz/#%E5%89%8D%E5%90%8E%E7%AB%AF%E7%BB%93%E5%90%88)前后端结合

- Axios 基础和用法
- swagger 在线调试异步请求
- JSON web token 实现权限验证
- axios 拦截器实现全局处理
- 前端缓存设计与实现
- 文件上传原理和组件实现

### [#](http://docs.vikingship.xyz/#%E9%A1%B9%E7%9B%AE%E9%83%A8%E7%BD%B2)项目部署

- 生产环境概念
- 构建代码
- 部署到云主机
- 使用脚本自动部署

### [#](http://docs.vikingship.xyz/#%E6%9B%B4%E5%A4%9A%E5%86%85%E5%AE%B9)更多内容

- Bootstrap 基础和用法
- Vue cli 用法
- Restful API 设计理念






# TypeScript  Array
TypeScript 与 JavaScript 一样，允许您使用值数组。

数组类型可以用两种方式之一编写。在第一个中，您使用元素的类型，后跟 `[]` 来表示该元素类型的数组：
`let list: number[] = [1, 2, 3];`

第二种方法使用通用数组类型 `Array<elemType>` ：

`let list: Array<number> = [1, 2, 3];`

# TypeScript 接口

如果某个东西长得像鸭子，像鸭子一样游泳，像鸭子一样嘎嘎叫，那它就可以被看成是一只鸭子。

```js

// 我们定义了一个接口 Person
interface Person {
  name: string;
  age: number;
}
// 接着定义了一个变量 viking，它的类型是 Person。这样，我们就约束了 viking 的形状必须和接口 Person 一致。
let viking: Person ={
  name: 'viking',
  age: 20
}

//有时我们希望不要完全匹配一个形状，那么可以用可选属性：
interface Person {
    name: string;
    age?: number;
}
let viking: Person = {
    name: 'Viking'
}

//接下来还有只读属性，有时候我们希望对象中的一些字段只能在创建的时候被赋值，那么可以用 readonly 定义只读属性

interface Person {
  readonly id: number;
  name: string;
  age?: number;
}
viking.id = 9527
```


