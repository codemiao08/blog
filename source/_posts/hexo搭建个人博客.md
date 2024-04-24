---
title: Hexo搭建个人博客
date: 2024-04-06 16:49:16
tags: 前端
cover: https://img0.baidu.com/it/u=1678745880,3961252043&fm=253&fmt=auto&app=138&f=JPEG?w=431&h=226
coverHeight: 514
coverWidth: 896
---
## Hexo搭建个人博客

### 前言
什么是hexo？
> Hexo 是一个快速、简洁且高效的博客框架。Hexo 使用 Markdown（或其他标记语言）解析文章，在几秒内，即可利用靓丽的主题生成静态网页。

### 安装
Hexo是基于nodejs开发的，所以安装前需要确保已安装有[node.js](https://nodejs.org)
安装后，便可以开始安装Hexo了。
#### 安装Hexo
安装Hexo需要使用npm，只需打开终端输入一下命令即可：
```bash
npm install -g hexo
```

### 开始搭建
在安装完Hexo后，可以新建一个文件夹来存储我们的网站，然后打开终端，输入：
```bash
hexo init myblog
cd myblog
npm install
```
之后，我们可以看到指定目录的内容如下：
```bash
.
├── _config.yml
├── package.json
├── scaffolds
├── source
|   ├── _drafts
|   └── _posts
└── themes
```
这说明我们已经初始化好项目了。
接着，尝试在终端输入：
```
hexo server
```
来启动我们的项目，然后打开http://localhost:4000/ 便可以看到初始化的效果：
![Hexo](https://pic3.zhimg.com/v2-c693e9c19beaab2350bebd5be2552362_r.jpg)
我们的博客就基本完成了。