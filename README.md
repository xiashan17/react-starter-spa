

resource  https://github.com/xiashan17/react-starter-spa

# React single page application

标签： react项目文件架构

---

本例为兴趣小组开源项目，功能持续升级，部分功能不完善，仅做参考

----------


#nvironment

node和npm说明

node -v 4.4.6

npm -v 2.15.5


----------

#Getting Started

npm install

npm run server #开启热更新服务器，访问:http://内网ip:30001/index.html

npm run test   #打包操作输出到dist下的store文件夹

----------


#introduct

nodejs后台     (express+jade+less)

html单页面前台（react + react-router + redux）

前端构建工具  （webpack）

----------


#dependencies introduct

后台

body-parser：express 重要中间件，用来解析http请求返回

cookie-parser: express 重要中间件，用户处理cookie

debug:控制台打印日志中间件

express:基于nodejs的遵循RESTful的mvc框架

jade:nodejs的后端页面模板

less-middleware:node后台支持less的中间件（用webstorm生成的，因前台编译形css试用sass,这个中间件可以不用试用）
morgan:日志输出文件的中间件

serve-favicon：动态创建网站favicon图标的中间件


前台

babel-core: 已经开始用ES6、ES7的不陌生了，JavaScript 语法的编译器 资源库

babel-loader：JavaScript ES6、ES7 的webpack文件装载器

babel-preset-es2015: ES6 语法库

babel-preset-stage-0: ES7 语法库

css-loader:css文件 的webpack文件装载器

exports-loader:在 AMD/CMD 中，我们需要对不符合规范的模块（比如一些直接返回全局变量的插件）进行 shim 处理，这时候我们需要使用

exports-loader 来帮忙加载文件

autoprefixer-loader:给css添加前缀的webpack文件装载器 (渐进增强，优雅降级使用)

file-loader：文件加载器，通常用于字体，图片等文件加载

imports-loader:对于不支持CommonJS规范的模块 将变量注入到模块中

jsx-loader：react的jsx文件装载器

less-loader：less文件装载器

sass-loader:sass文件装载器


fetch:下一代的ajax引擎

fetch-jsonp：扩展fetch支持jsonp

less:less资源库

node-sass:终于轮到他，本项目编译css暂时试用sass,以后会迁移到less.原因less可以用js加载调试，另外一个原因居然是sass是用ruby写的，这个中间件sass可以用node解析了，泪奔

path:相对路径，绝对路径，配置文件路径，本模块路径，再也不糊涂了(这个可以说是前后台通用的)

react: react 资源库

react-dom：react dom操作库

react-hot-loader :react热插拔库，即改即更新页面，不用f5了

react-router：react的前端路由，SPA必用

redux: redux 资源库

react-redux：react和redux集成库

redux-thunk: redux 异步处理dispatch的库

webpack:构建工具webpak

webpack-dev-server：实时构建热更新服务工具库

html-webpack-plugin 更新资源文件打上cdn后缀之后同步到html引用中的webpack插件，太棒了

----------
##Learn More

  * [Getting Started with React.js](http://facebook.github.io/react/)
  * [Getting Started with GraphQL and Relay](https://quip.com/oLxzA1gTsJsE)
  * [React.js Questions on StackOverflow](http://stackoverflow.com/questions/tagged/reactjs)
  * [React.js Discussion Board](https://discuss.reactjs.org/)
  * [Flux Architecture for Building User Interfaces](http://facebook.github.io/flux/)
  * [Enzyme — JavaScript Testing utilities for React](http://airbnb.io/enzyme/)
  * [Flow — A static type checker for JavaScript](http://flowtype.org/)
  * [The Future of React](https://github.com/reactjs/react-future)
  * [Learn ES6](https://babeljs.io/docs/learn-es6/), [ES6 Features](https://github.com/lukehoban/es6features#readme)
  * [Learn article]https://demo.reactstarterkit.com/


