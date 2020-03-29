---
layout: post
title: 2012 Student Performances
---

{% for file in site.static_files %}
  {% if file.path contains 'img/2012' %}
    {% if file.extname == ".jpg" %}
![image]({{ site.baseurl }}{{ file.path }})
    {% endif %}
  {% endif %}
{% endfor %}