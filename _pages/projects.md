---
title: "Projects"
permalink: /projects/
layout: single
author_profile: false
---

Here are selected projects that reflect my work in marketing analytics, data analysis, and storytelling.

{% for project in site.projects %}
### [{{ project.title }}]({{ project.url | relative_url }})

{{ project.excerpt }}

**Tools:** {{ project.tools | join: ", " }}

---
{% endfor %}
