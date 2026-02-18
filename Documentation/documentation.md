---
layout: default
title: Documentation
nav_order: 2
has_children: true
---


# Documentation

Welcome to the documentation section.

<!-- Below are the available documentation repositories:

{% assign doc_dirs = "" | split: "" %}

{% for f in site.static_files %}
  {% if f.path contains '/docs/' %}
    {% assign parts = f.path | split: '/' %}
    {% if parts.size > 2 %}
      {% assign dir = parts[2] %}
      {% unless dir == 'docs.md' %}
        {% unless doc_dirs contains dir %}
          {% assign doc_dirs = doc_dirs | push: dir %}
        {% endunless %}
      {% endunless %}
    {% endif %}
  {% endif %}
{% endfor %}

{% for d in doc_dirs %}
- [{{ d }}]({{ '/docs/' | append: d | relative_url }})
{% endfor %} -->
