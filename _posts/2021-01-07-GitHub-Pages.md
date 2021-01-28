---
layout: single
title:  "github page"
date:   2020-12-14 13:31:17 +0800
---



直接从GitHub 仓库创建网站，GitHub Pages 是一项网站托管服务，允许你将 Jekyll 网站推送到 GitHub 仓库。

{{TOC}}

## 使用 Jekyll 创建站点

[Jekyll](https://jekyllrb.com/) 是一个静态网站生成器，一个用于将模版和内容合并到一起从而创建网站的命令行工具。

jekyll 将 Liquid 作为自身的模版语言，并且添加了许多**对象**（object）、标记（tag）和过滤器（filter）。这些新增内容包括代表内容页面的对象、用于在页面中引入内容片段的标记（tag），以及用于操作字符串和 URL 的过滤器。[^[资料来源](https://liquid.bootcss.com/basics/variations/)]

### 目录结构
使用基于 gem 的主题的 Jekyll 站点的目录结构

| 目录 | 描述 | 备注 |
|:--|:--|:--|
| `_config.yml` | 配置：设置配置选项 |  |
| `_drafts` | 草稿：未发布的文章，这些文件没有日期：`title.markup` |  |
| `_includes` | 包括： |  |
| `_layouts` | 布局：这里是包装文章的模板 |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |


### 配置

通过编辑根目录下的 \_config.yml 文件来配置 Jekyll，例如网站的主题和插件。

全局配置

* [官网全局配置选项说明文档][1]

## 参考资料

* [关于自定义域名和 GitHub 页面 - GitHub Docs][2]

[1]:	https://jekyllrb.com/docs/configuration/options/
[2]:	https://docs.github.com/cn/github/working-with-github-pages/about-custom-domains-and-github-pages