---
layout: page
title: Blog
permalink: /blog/
---

This is where all my blogs are! These include conversations that i have had across personal and professional settings that i found interesting to share, and/or things that i am currently learning.

{% for post in site.posts %}

## [{{ post.title }}]({{ post.url | relative_url }})

{{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

---

{% endfor %}