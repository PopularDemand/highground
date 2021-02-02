---
permalink: /designs/aesthetic
layout: page
external_id: aesthetic_designs
---

{% for c in site.data.functional_designs.collections %}
{{ c.title }}<br>
{{ c.description }}<br>

{% for i in c.images %}
{{ i.description }}<br>
{% endfor %}
{%endfor %}