---
layout: default
title: Releases
---

# Release Notes

{% assign sorted = site.static_files | sort: 'path' %}
{% for release in site.pages %}
  {% if release.path contains 'releases/' %}
    - [{{ release.title | default: release.path }}]({{ release.url }})
  {% endif %}
{% endfor %}
