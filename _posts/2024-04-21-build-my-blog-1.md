---
title: Jekyll博客快速入门指南
description: 使用Jekyll创建和发布博客的简易教程
author: Jyf0214
date: 2024-04-21 12:10:00 +0800
categories: [Tutorial, Jekyll]
tags: [Jekyll, 博客, 入门]
pin: true
math: true
mermaid: true
---

Jekyll博客快速入门指南

Jekyll是一款静态站点生成器，它可以帮助我们轻松创建一个功能齐全的博客。这篇教程将带你从零开始，逐步了解如何使用Jekyll搭建一个简单的博客站点。


---

1. 安装Jekyll

首先确保你已经安装了Ruby和RubyGems。然后在终端中运行以下命令来安装Jekyll和bundler：

```bash
gem install jekyll bundler
```

2. 创建新项目

使用以下命令生成一个新的Jekyll站点：

```bash
jekyll new myblog
cd myblog
bundle install
```

此时，myblog文件夹中已经包含了一个基本的博客项目结构。

3. 启动本地服务器

通过以下命令启动本地服务器：

```bash
bundle exec jekyll serve
```

服务器将在 http://localhost:4000 上运行，打开浏览器访问该地址即可预览你的博客。

4. 添加内容

要创建一个新的博客帖子，可以在 _posts 文件夹中添加Markdown文件，格式如下：

```bash
---
title: 文章标题
date: 2024-04-21 12:00:00 +0800
categories: [分类]
tags: [标签]
author: 作者
pin: true
math: true
mermaid: true
---

```

5. 自定义配置

在 _config.yml 文件中可以调整博客的配置，例如站点标题、描述、主题等。可以参考官方文档来了解更多配置项：

```bash
title: My Awesome Blog
description: A blog powered by Jekyll
theme: minima
```

6. 发布到GitHub Pages

创建一个新的GitHub仓库，并将项目上传。然后在仓库设置中启用GitHub Pages，你的博客就可以在线访问了。


---

