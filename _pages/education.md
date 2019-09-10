---
layout: page
title: Education
permalink: /education/
image: education.jpg
image_footer: Image by <a href="https://pixabay.com/users/jarmoluk-143740/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=436498">Michal Jarmoluk</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=436498">Pixabay</a>
---
{% for el in site.collections %}
{{el.label}}
{% endfor %}
{% for staff_member in site.staff_members %}
  {{staff_member.name}}
{% endfor %}
