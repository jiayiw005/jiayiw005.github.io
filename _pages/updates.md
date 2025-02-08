---
title: "Updates"
layout: textlay
sitemap: false
permalink: /updates.html
---

## Updates

<div class="jumbotron">
{% for article in site.data.news limit:5 %}
<b>{{ article.date }}</b>

{{ article.headline }}
{% endfor %}

</div>
