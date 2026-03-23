---
layout: default
title: 心得感想
---

# 心得感想 1✍️

{% for post in site.categories.thoughts %}
  - {{ post.date | date: "%Y-%m-%d" }}  
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}
