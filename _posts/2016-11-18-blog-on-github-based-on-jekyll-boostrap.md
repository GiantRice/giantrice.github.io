---
layout: post
title: "blog on github based on jekyll boostrap"
description: ""
category: 
tags: []
---
{% include JB/setup %}

本文介绍github上搭建blog。

---
# github 博客搭建

[Jekyll QuickStart](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)上有3分钟内搭建
github博客的教程。

1. 创建新的仓库（即博客）。
2. 安装Jekyll-Bootstrap
	从github上复制Jekyll-Bootstrap仓库到本地，再上传到博客仓库中。
3. 访问自己的博客：http://USERNAME.github.com

---
# 本地运行 Jekyll

为了方便预览博客，可以在本地安装Jekyll。
Jekyll的中文官网有介绍[安装Jekyll的教程](http://jekyllcn.com/docs/installation/)
本地环境是windows，虽然Jekyll官方并不支持windows，但是可以通过一系列的组间安装，来搭建jekyll。
所幸JuLian Thilo有一篇[Run Jekyll on Windows](http://jekyll-windows.juthilo.com/)，另外本文主要参考了[在 Windows 上安装 Jekyll](http://cn.yizeng.me/2013/05/10/setup-jekyll-on-windows/)。

1. 安装Ruby
2. 安装DevKit，需要注意版本的一致性。
3. 安装Jekyll
4. 安装Pygments，语法高亮
5. 运行Jekyll


## 相关问题
1. windows下还是有一些问题的，主要是在Jekyll的某些版本下，watch功能无法实现。


## To be continued







---

# 参考文档
1. [Jekyll QuickStart](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)
2. [Jekyll 中文官网](http://jekyllcn.com/)
