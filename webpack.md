# webpack

## 什么是webpack？
webpack 是一个 JavaScript 应用程序的静态模块打包器(module bundler)。当 webpack 处理应用程序时，它会递归地构建一个依赖关系图(dependency graph)（在webpack中一切皆模块），用于映射到项目需要的每个模块，其中包含应用程序需要的每个模块，然后将所有这些模块打包成一个或多个 bundle（浏览器可识别的一个或多个文件）。

## webpack和其他前端自动化构建工具的区别？
* gulp：前端自动化构建工具，以任务的形式进行构建，css的编译，js编译，启动服务，手动配置，对文件进行操作
* grunt：类似于gulp也是自动化的构建工具，减轻手动构建效率低下的问题
* webpack：以模块为入口，使用loader，plugins对文件进行编译，在webpack中一切皆模块

## webpack的核心概念
* 模块解析规范，在webpack中模块是按照node.js commonJs规范定义，也可以自己配置（resolve）
* 入口（entry）
* 出口（output）
* 解析规则（loader）
* 插件（plugins）
* devServer
