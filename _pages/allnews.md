---
title: "News"
layout: textlay
excerpt: "PurS3 Lab at Purdue University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
