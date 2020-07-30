---
layout: page
title: someday
permalink: /someday/
---

# Someday...

{% for post in site.categories.someday %}
 <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
