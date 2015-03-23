---
layout: default
title: The No-Olympics Songbook
---

Suggestions for new lyrics and new songs are 
[very welcome](http://github.com/mccalluc/nolympics)!

{% for post in site.posts %}

## [{{ post.title }}](/nolympics{{ post.url }})
{{ post.excerpt }} ...

{% endfor %}
