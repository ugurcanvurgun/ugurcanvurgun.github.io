---
title: News
layout: single
author_profile: true
permalink: /news/
---

{% for post in site.categories.news %}
## {{ post.date | date: "%B %Y" }}
{{ post.content }}
{% endfor %}
