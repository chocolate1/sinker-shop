# sinker-shop
锤子商城
vue-cli起步使用vuex建造锤子商城

萌新起步请看：
我们需要用到npm打包工具，所以咱们需要先安装node，不懂为啥要先安装node的话，请百度呢，兄弟。
我们可以用：npm -v来查看我们安装的版本就可以确认是否安装成功。
首先我们用脚手架（不知道脚手架是个啥鬼的请自行百度）vue-cli起步，
我们先建一个文件夹命名为sinkerShop打开命令行终端，（你可以用vscode的ctrl+`进入终端，也可以直接用window+r进入cmd命令行）进入到这个文件的路径下，码上几个字母：
npm install -g vue-cli 
咱们就全局安装了vue-cli，然后呢，我们可以查看下是否安装成功，我们可以使用这几个字母（命令）：
vue -V 
使用这个我们可以查看到vue的版本，然后我们可以进行下一步,直接进行建议一个基于webpack的新项目，使用这几个字母：
vue init webpack 项目名
我这里用的是 vue init webpack chuizi
然后你可以看到的是 这一大堆的东西，是关于你的文件的设置问题：（萌新们看着办，确定的话直接回车就好了呢）
? Project name chuizi
? Project description A Vue.js project
? Author
? Vue build standalone
? Install vue-router? Yes
? Use ESLint to lint your code? No
? Set up unit tests No
? Setup e2e tests with Nightwatch? No
? Should we run `npm install` for you after the project has been created? (recommended) npm install
成功的话，我们可以跳到我们创建的项目路径跑一下我们的项目了哦。
like this:
cd chuizi
（在这里我们要用的是vuex，所以用的是以下命令)
npm install vuex --save
在我们的package.json中我们看到"dependencies"中我们可以看到"vuex": "^3.0.1"说明我们安装了呢。
npm run dev
到现在为止，我们可以打开浏览器输入"localhost:8080"进行查看了，至此我们的项目就搭建完毕了哦。

我的项目目录中src中的文件夹来给大家介绍下呢：
assets:主要放的是样式文件和图片
  css
  img
components:主要是放我们的组件
lib:主要是放数据（自己模拟）
router:主要是放路由的配置文件
store:主要放vuex的相关文件
views:所有的单页面
App.js
main.js





