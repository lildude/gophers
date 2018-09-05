---
---
# Gophers

{% for image in site.static_files %}
  {% if image.path contains '.png' %}
    ![]({{ image.path }})
  {% endif %}
{% endfor %}


