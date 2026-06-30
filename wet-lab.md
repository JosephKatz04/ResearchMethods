---
layout: default
title: Wet Lab
permalink: /wet-lab/
---

# Wet Lab

{% assign wet_lab_methods = site.methods | where: "category", "wet-lab" | sort: "title" %}

{% if wet_lab_methods.size > 0 %}
{% for method in wet_lab_methods %}
- [{{ method.title }}]({{ method.url | relative_url }}){% if method.summary %}: {{ method.summary }}{% endif %}
{% endfor %}
{% else %}
No wet lab methods have been added yet.
{% endif %}

