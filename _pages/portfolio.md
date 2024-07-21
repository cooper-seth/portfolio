---
title: Portfolio
layout: archive
permalink: /portfolio/
author_profile: true
---

{% for portfolio in site.portfolio %}
<div class = "portfolio">
  <h3><a href = "{{ porfolio.url }}">{{portfolio.title}}</a></h3>
</div>
{% endfor %}