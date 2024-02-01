---
title: "News"
layout: textlay
excerpt: "Zhang Lab - News"
sitemap: false
permalink: /allnews/
---

## News

<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.date }}</b>

{{ article.headline }}
{% endfor %}
</div>
