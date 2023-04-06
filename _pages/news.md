---
title: News
layout: single
author_profile: true
permalink: /news/
---

{% raw %}
{% for post in site.categories.news %}
## {{ post.date | date: "%B %Y" }}
{{ post.content }}
{% endfor %}
{% endraw %}
