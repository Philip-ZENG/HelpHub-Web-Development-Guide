# Chapter 3：了解Vue.js, Vuetify 完成第一个网页设计



## 第一步：了解构建用户界面的JavaScript框架Vue

### 初步介绍

我们的公司网页是使用Vue框架搭建的的，你可以将Vue理解成一个JavaScript的库，它提供了网页搭建所需的一些工具，通过Vue，你可以便捷地实现网页的搭建。

在着手搭建网页界面之前，你需要先了解Vue的使用规则和其提供的工具功能。

我们推荐你先阅读Vue.js的官方文档：https://vuejs.org/v2/guide/ 

### 学习重点

在阅读文档的过程中，你可能会遇到很多新的概念，这可能会让你陷入“我完全看不懂它在说什么”的境地。请别担心，我们在初次了解Vue的时候也经历了这样一个阶段。

在初次学习文档时，请先完成Essential（基础）和Components In Depths（深入了解组件）部分。以上知识已经基本足以支撑单页面的UI设计了。其中Vue的组件（Components）的是其非常核心的功能，在学习Vue时可以重点关注。

### 辅助资料

作为文档的辅助学习的资料，我们推荐你观看以下视频课程：https://learning.dcloud.io/#/

该视频课程是依据Vue.js的官方文档进行讲解的，并且配有相应的代码例子作为解释，配合文档进行学习，效果不错。

以下两个课程可以作为Vue学习的参考：

Vue.js Fundamentals：https://vueschool.io/courses/vuejs-fundamentals

Vue.js Components Fundamentals：

https://vueschool.io/courses/vuejs-components-fundamentals?friend=vuejs







## 第二步：了解Vue的组件库Vuetify

### 初步介绍

Vuetify为我们提供了很多现成的使用Vue框架搭建的网页设计组件，在Vuetify上寻找合适的模板，然后对代码进行修改是初次进行网设计时不错的选择。

Vuetify网页链接：https://vuetifyjs.com/en/

### 使用建议

在这里，我们推荐几个比较基础且方便使用的组件：

- Cards（卡片）
- Grid system（网格系统）
  - 关于Grid的使用，我们推荐以下教程网页，完成该教程后，你将对Grid组件的使用有一个基本的了解
    https://codepip.com/games/grid-garden/

对于网页排版的一些基础知识也将有助于你的网页设计，一下两个是常用的排版方式：

- Flex（弹性布局）

  - 关于Flex的使用，我们推荐以下教程网页，完成该教程后，你将对Flex布局的使用有一个基本的了解。

    https://flexboxfroggy.com/

- Spacing（间距）





## 第三步：尝试设计网页并通过Node.js查看其运行的效果

### 初步介绍

Node.js是一个在本地模拟网页运行的“虚拟服务器”。通过Node.js提供的npm功能，你可以将本地的网页设计文件进行编译，并且在浏览器中查看其呈现效果。

你可以在Node.js的官网下载Node.js：https://nodejs.org/en/

### 使用方式

下载完成后，在你网页设计文件的根目录下，打开Terminal，并且输入以下指令，即可开始网页的模拟运行：

```shell
// Project setup
npm install
// Compiles and hot-reloads for development
npm run serve
```

完成编译后Node.js会为你提供一个网页链接，将该链接复制到你的浏览器中，即可看到网页运行的结果。

在开发模式下，你对网页文件的修改会即时更新到网页模拟运行的界面，你可以即时查看修改的结果。

### 备注

产品网页设计的可视化方案一般由HelpHub宣传部提供，网页的代码实现由技术部完成。
