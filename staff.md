---
title: Staff
---

# Staff


{% for author in site.authors %}
- ## [{{ author.name }}]({{ author.url }})
  ### {{ author.position }}
  {{ author.content | markdwonify }}
{% endfor%}