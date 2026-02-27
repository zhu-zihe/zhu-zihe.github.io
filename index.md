---
layout: default
title: 首页
---

# 👋 欢迎来到我的网站

这是我的GitHub Pages个人博客，使用Jekyll构建。

## 📝 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## 🎯 关于我

我是一名飞友，同时喜欢电脑

## 📫 联系方式

- GitHub: [zhu-zihe](https://github.com/zhu-zihe)
- 邮箱: 18963616169@163.com

---

*感谢访问！*
