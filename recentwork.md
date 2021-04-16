---
layout: page
title: Recent work
---

Recent work:

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
