---
layout: post
title: "GitHubPages+Jekyll-搭建 Blog"
subtitle: '使用 Jekyll 搭建静态网站，并在 GitHubPages 发布'
author: "Lingtima"
header-style: text
hidden: false
tags:
  - Jekyll
  - GitHubPages
---
# GitHub Pages

GitHub Pages 是一项静态站点托管服务，它直接从 GitHub 上的仓库获取 HTML、CSS 和 JavaScript 文件，（可选）通过构建过程运行文件，然后发布网站。 您可以在 [GitHub Pages 示例集合](https://github.com/collections/github-pages-examples)中查看 GitHub Pages 站点的示例。

# Jekyll

Jekyll 是一个静态站点生成器，内置 GitHub Pages 支持和简化的构建过程。 Jekyll 使用 Markdown 和 HTML 文件，并根据您选择的布局创建完整静态网站。 Jekyll 支持 Markdown 和 Lick，这是一种可在网站上加载动态内容的模板语言。 更多信息请参阅 [Jekyll](https://jekyllrb.com/)。

# 创建 GitHub 仓库

在 GitHub 上创建一个公开仓库，仓库名为 `用户名.github.io`

# 安装与配置 Jekyll

安装 Jekyll 需要 Ruby、gem 依次安装即可


安装与配置请参照  Jekyll 文档 [Jekyll 国内][1]

# 浏览博客

在项目目录输入命令

```shell
jekyll server
```

在浏览器中输入 `127.0.0.1:4000` 即可访问博客

之后将项目推送到您的 GitHub 仓库中即可。

# 参考

* [关于 GitHub Pages 和 Jekyll](https://help.github.com/cn/github/working-with-github-pages/about-github-pages-and-jekyll)



[1]:http://jekyllcn.com/


