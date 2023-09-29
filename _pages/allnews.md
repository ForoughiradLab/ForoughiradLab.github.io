---
title: "News"
layout: textlay
excerpt: "Foroughirad Lab at Texas A&M University Galveston"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p><b>{{ article.date }}</b> <br>
{{ article.headline }}</p>
{% endfor %}
