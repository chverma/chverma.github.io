---
layout: page
title: Bloc
permalink: /blog-ca/
image: 11.jpg
image_footer: Imagen by <a href="https://pixabay.com/users/Wokandapix-614097/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2355684">Wokandapix</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2355684">Pixabay</a>
lang: ca
ref: blog
---
{% for post in site.posts %}
  * <span>{{ post.date | date_to_string }}</span> <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
{% endfor %}
