---
title: "Projects"
permalink: /projects/
layout: single
author_profile: false
---

Here are selected projects that reflect my work in marketing analytics, data analysis, and storytelling.

{% for p in site.projects %}
### [{{ p.title }}]({{ p.url | relative_url }})
{{ p.excerpt }}

**Tools:** {{ p.tools | join: ", " }}

---
{% endfor %}
