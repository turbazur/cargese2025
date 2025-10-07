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

---

<div>
<embed src="{{ site.baseurl }}/files/schedule_v0.pdf" width="450" height="400" type='application/pdf'> 
</div>

---

[**List of Projects**](/cargese2025/projects)

---
