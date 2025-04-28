---
layout: category
title: "파이썬"
permalink: /categories/python/
taxonomy: categories
category: python
---

{% for post in site.categories.python %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
