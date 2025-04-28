---
layout: category
title: "일상"
permalink: /categories/일상/
taxonomy: categories
category: 일상
---

### 일상 카테고리 포스트

<ul>
{% assign posts = site.categories['일상'] %}
{% for post in posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
