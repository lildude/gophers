---
---
{% for image in site.static_files %}
  {% if image.path contains '.png' %}
    <img src="{{ image.path }}" alt="">
  {% endif %}
{% endfor %}


