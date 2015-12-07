---
layout: home
permalink: /
title: "Christ on the Mountain Top"
excerpt: "Friends. Purpose. Life."
image:
  feature: pages/children-moment-1600x800.jpg
  teaser: pages/children-moment-400x250.jpg
---

<div class="tiles">
{% for post in site.posts limit:8 %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
