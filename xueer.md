---
layout: page
title: Xueer
permalink: /xueer/
---
<ul>
{% for post in site.categories.xueer %}
	<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
