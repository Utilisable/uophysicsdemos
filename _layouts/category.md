---
layout: default
---
{% for demo in site.demos %}
  - [{{ demo.title }}]({{ demo.url | relative_url }})
    - {{ demo.category }}
{% endfor %}
{{ page.url }}