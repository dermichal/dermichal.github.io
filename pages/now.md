---
layout: page
title: now
permalink: /now
---

One of the scarcest things we have in life is our time. To really understand what I mean by that please dive into this excelent read by [Tim Urban][waitbutwhy].

This is a selection of carefully selected things I am conciously assigning my precious time to. This section is organized in titles I have earned or am earning at the moment vs. the ones that [expired]({% link pages/then.md %}).

# What I am doing right now:


{% for post in site.categories.now %}
 <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}



[waitbutwhy]: https://waitbutwhy.com/2015/12/the-tail-end.html
