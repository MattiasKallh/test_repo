---
layout: default
title: Documentation
---

# Documentation

Below are the available documentation versions:

{% assign folders = site.static_files | map: 'path' | uniq %}
{% for file in site.static_files %}
  {% if file.path contains 'docs/' and file.path != 'docs/index.md' %}
    - [{{ file.path | split: '/' | last }}]({{ file.path | relative_url }})
  {% endif %}
{% endfor %}
