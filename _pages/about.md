---
title: "News"
layout: textlay
excerpt: "Optima Group at Leiden University."
sitemap: false
permalink: /about.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
