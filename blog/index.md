---
title: Blog
layout: default
permalink: /blog/
---

# Blog

{% for post in site.blog %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}
