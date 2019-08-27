---
title: scratch
author: Colton Grainger
date: 2019-08-27
revised:
---

## further reading

{% for post in site.posts %}
`{{ post.date | date: "%Y-%m-%d" }}` [{{ post.title }}]({{ post.url }})
{% endfor %}
