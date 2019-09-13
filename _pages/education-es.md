---
layout: page
title: Educación
permalink: /educacion/
ref: education
lang: es
---
<div class="container">
	<div class="row">
  {% assign posts=site.education_levels_entries | where:"lang", page.lang %}
  {% if posts.size > 0 %}
    {% for post in posts %}
			{% include article-content.html %}
		{% endfor %}
	{% endif %}
	</div>
</div>
