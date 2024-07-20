---
layout: page
permalink: /projects/
title: Projects
author_profile: false
---


<div id="archives">
{% for category in site.categories %}
  <div class="archive-group">
{% for post in site.categories.Project %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
  </div>
{% endfor %}
</div>