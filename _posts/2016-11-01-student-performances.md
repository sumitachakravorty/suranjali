---
layout: post
title: Student Program 2016
---

{% for file in site.static_files %}
  {% if file.path contains 'img/student-program-2016' %}
    {% if file.extname == ".jpg" %}
![image]({{ site.baseurl }}{{ file.path }})
    {% endif %}
  {% endif %}
{% endfor %}