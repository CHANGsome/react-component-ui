# react-component-ui

## 项目初始化：

npm init -y

## 安装依赖：

webpack：npm i webpack@4.29.6 webpack-cli@3.2.3 --dev
ts： npm i typescript --dev  
解析 ts 文件：npm i awesome-typescript-loader --dev

## 项目构建命令：

npx webpack

## webpack-dev-server

安装：npm i webpack-dev-server --dev
运行：npx webpack-dev-server

webpack-dev-server 是干什么的：

- 将 index.tsx 文件翻译成 index.js，以字符串的形式放在内存中
- webpack-dev-server 生成的 index.js 不存在本地 dist 目录中，而在服务器内存中，所以改动在本地不会看到，但是重新
  请求本地服务器（localhost:8080 ）的时候可以看到改动

## 写 html

安装 html 插件：npm i html-webpack-plugin --dev
