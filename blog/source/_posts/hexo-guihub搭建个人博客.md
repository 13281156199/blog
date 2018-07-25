---
title: hexo-guihub搭建个人博客
date: 2018-07-24 14:30:09
tags:
---
# hexo
## 特点：快速、简洁且高效的博客框架
## 环境:基于node(v8.11.3)
   1.环境及检测:
      win+r输入cmd回车
      cmd窗口输入node -v回车
      如果提示:node不是内部或者外部命令
      则需要安装node
    2.安装node环境
       [点我](https://nodejs.org/zh-cn/)下载8.11.3版本
       双击下载得到的mis文件，全程next安装
# 安装git(版本控制器)
  安装包在qq群文件
# 安装hexo
1.cmd命令: npm install hexo-cli -g
2.npm:基于node的包管理器，类似于ios的App store
    通过npm可以下载安装需要的插件或者框架
3.install:安装、导入
4.-g:表示全局安装(在任何的目录都可以使用)
# 初始化一个博客项目
  1.hexo init blog
  2.切换到项目目录
     cd blog
  3.安装项目依赖包
     npm install
  4.启动服务
     hexo s
资源网站：
hexo：http://www.hexo.io
小图标:https://www.easyicon.net
miho主题:https://github.com/WongMinHo/hexo-theme-miho