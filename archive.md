---
layout: page
title: Archive
---

# Blog Posts

{% for post in site.posts %}
  [ {{ post.title }} ]({{ post.url }}) *{{ post.date | date_to_string }}* <br> {{ post.excerpt }} 
  ---
{% endfor %}
