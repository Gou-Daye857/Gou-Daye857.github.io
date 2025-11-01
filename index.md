---
layout: default
title: 首页
---

<h1>欢迎来到我的博客</h1>
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> （{{ post.date | date: "%Y-%m-%d" }}）</li>
  {% endfor %}
</ul>
