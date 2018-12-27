---
title: Hexo 博客搭建挂载github page
date: '2018-12-18 15:19'
tags: null
---

#### 1. 安装nodejs
```
http://nodejs.cn/
```

#### 2. 安装hexo
```
npm install -g hexo-cli
```
#### 3.初始化项目
```
hexo i projectname
```

```
cd projectname
```
#### 4.生成静态页面(generetor)
```
hexo g
```
#### 5.在github上创建一个新项目

#### 6.点击Settings 创建一个page任意选择一个主题

#### 7.修改hexo站点的配置文件_config.yml
```
  deploy:
    type: git
    repository: git@github.com:JimmyMin/JimmyMin.github.io.git
    branch: master
```
#### 8.安装hexo部署git插件
```
npm install hexo-deployer-git --save
```
#### 9.安装hexo部署git插件
```
hexo d
```
