---
layout: default
title: Blog
---
# Blog
{% for post in site.posts %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt }}</p>
{% endfor %}
