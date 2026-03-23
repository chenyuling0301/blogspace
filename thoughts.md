---
layout: default
title: 心得感想1
---

# 心得感想 ✍️

{% for post in site.posts %}
  - {{ post.date | date: "%Y-%m-%d" }}  
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}
