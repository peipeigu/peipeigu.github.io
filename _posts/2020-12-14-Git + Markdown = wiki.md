---
layout: single
title:  "Git + Markdown = wiki"
date:   2020-12-14 13:31:17 +0800
---


写博客输出的文章，偏向创作；
写个人维基适合整理。很多入门级别、复用别人的操作，并不适合放在个人博客上。

**用gollum构建自己的知识管理wiki系统**

## Gollum

### Gollum 是什么？
Gollum简单来说就是一个基于git的Wiki系统。同时一个Gollum Wiki也是一个简易的git仓库：


### 如何安装 Gollum

gollum是基于ruby编写的；所以在安装gollum之前，需要先安装ruby环境；


另外，这样安装之后WIKI中对于Markdown文档不支持表格，需要运行一下如下语句:

	gem install gollum
	gem install github-markdown


## 运行

* 克隆GitHub到本地目录

git clone 下相应维基的git地址

**要运行，只需:**
1. 运行：`gollum /path/to/wiki`。
2. `http://localhost:4567`在浏览器中打开。

