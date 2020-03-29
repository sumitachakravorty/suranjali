---
layout: post
title: Student Performances
---

{% for file in site.static_files %}
  {% if file.path contains 'img/student-performances' %}
    {% if file.extname == ".jpg" %}
![image]({{ site.baseurl }}{{ file.path }})
    {% endif %}
  {% endif %}
{% endfor %}