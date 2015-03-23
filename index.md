---
layout: default
title: The No-Olympics Songbook
---

# The No-Olympics Songbook!

Suggestions for new lyrics and new songs are very welcome!
Make a fork at http://github.com/mccalluc/nolympics

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
