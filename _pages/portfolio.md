---
title: Portfolio
layout: archive
permalink: /portfolio/
collection: portfolio
entries_layout: grid
author_profile: true
---

{% for portfolio in site.portfolio %}
  <h2>
    <a href="{{ portfolio.url }}">
      {{ portfolio.title }}
    </a>
  </h2>
{% endfor %}