---
layout: page
title: Projects
permalink: /projects/
category: "projects"
tagline: "Tinker"
---

{% for project in site.projects %}
  {% include project.html project=project %}
{% endfor %}
