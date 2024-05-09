---
layout: page
title: Blog posts
permalink: /posts/
---

{% for post in site.posts %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
