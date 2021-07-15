# 环境安装

## 1. Node.js安装

### 1.1 官网下载msi文件

### 1.2 无脑点击下一步

### 1.3 安装node.js 淘宝镜像cnpm

//:   -g就是全局安装  
npm install cnpm -g
有时进度条安装不动 npm install -g cnpm --registry=https://registry.npm.taobao.org

//: 或使用下面语句<br/>npm install --registry==https://registry.npm.taobao.org

### 1.4 使用代理registry

npm config set registry https://registry.npm.taobao.org

1.3或1.4选择其一。

## 2. 安装vue-cli

cnpm install vue-cli -g