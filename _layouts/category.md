---
layout: default
---
{% for demo in site.demos %}
  - [{{ demo.title }}]({{ demo.url | relative_url }})
    - {{ demo.name }}
{% endfor %}
{{ page }}