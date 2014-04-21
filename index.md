---
layout: page
title: My Blog
---
<ul class="pots">
	{% for post in site.posts %}
		<li>{{ post.date | date_to_string }} <a href = "{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>