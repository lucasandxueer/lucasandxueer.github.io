---
layout: page
title: Lucas
permalink: /lucas/
---
<ul>
{% for post in site.categories.lucas %}
	<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
