---
title: News
linktitle: News
layout: default
weight: 2
feedlink: /feed/news.xml
---

{% for post in site.categories.news %}
<div class="news">
<h2 class="news-title">{{ post.date | date: "%Y-%m-%d" }} {{ post.title }}</h2>
{{ post.content }}
</div>
{% endfor %}
