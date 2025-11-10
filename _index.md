---
layout: default
title: 首页
---

# 欢迎来到我的博客

这里是我用 Obsidian 记录的知识笔记。

## 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
