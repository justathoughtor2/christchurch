---
layout: home
permalink: /
title: "Latest Posts"
image:
  feature: pages/children-moment-1600x800.jpg
  teaser: pages/children-moment-400x250.jpg
---

<div class="tiles">
{% for post in site.posts limit:8 %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
