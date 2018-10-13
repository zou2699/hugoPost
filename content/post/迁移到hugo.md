---
title: "迁移到hugo"
date: 2018-10-13T17:54:00+08:00
draft: flase
categories:
- hugo
tags:
- hugo
- hexo
- 图床
thumbnailImagePosition: left
thumbnailImage: //ws1.sinaimg.cn/large/b77abccagy1fw6rhvm1b4j22801h9hdv.jpg
coverImage: //ws1.sinaimg.cn/large/b77abccagy1fw6rhvm1b4j22801h9hdv.jpg
metaAlignment: center
---

blog的一些说明
<!--more-->
<!--toc-->
# 为什么选择hugo来搭建私人博客
最近在学习golang，也打算记录下自己工作和生活中的一些事情。之前使用过hexo以及自己使用django写的blog网站，hexo主要是更新博客比较麻烦，需要安装hexo的基础环境，比较麻烦。django写的需要使用vps，持久性得不到保障，以及之后迁移也麻烦。  
反正就是因为麻烦选择了hugo，也是因为麻烦从python转到了golang。

## hugo的优势
[hugo](https://github.com/gohugoio/hugo)是golang编写的，以可执行文件的形式可以轻松在mac、linux以及win上直接运行，十分方便。其它基本和hexo一样，使用markdown语法，直接生成html，轻松部署到github page。

## hugo主题
hugo的主题也是比较多的，很多hexo有的，hugo上也有。可以前往[主题官网](https://themes.gohugo.io/)进行预览，然后选择一个自己喜欢的。  
选择了几款主题进行了尝试，最终选择了这款主题（Tranquilpeak），在使用过程中，也发现了一些新功能，十分符合我的口味。

## 图床

选择了markdown，就要面临着图床以及markdown编辑器的问题。因为之前以及使用过一段时间的编辑器，vscodo以及macdown，之后也会继续使用这2款。

还有就是图床问题，对我来说，图床一定要稳定以及快速，不然就有可能造成图片丢失或者网站访问缓慢。经过比较选择新浪图床和七牛，七牛的还在审核。。。mac上可以使用picgo这款软件，免费且开源。

