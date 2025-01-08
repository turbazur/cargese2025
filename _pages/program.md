---
permalink: /program/
title: "Program"
author_profile: true
---

{% for collection in site.collections %}
{% if collection.label == "talks" %}
  {% for post in collection.docs %}
      {% include archive-single.html %}
  {% endfor %}
{% endif %}
{% endfor %}

