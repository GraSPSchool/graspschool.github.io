---
title: Minicourses
---
<h1>Minicourses</h1>

{% for minicourse in site.minicourses %}
    <h2><a href="{{ minicourse.url }}">{{ minicourse.title }}</a></h2>
    <p><b>Lecturer:</b> {{ minicourse.lecturer }}</p>
    <p><b>Schedule:</b> {{ minicourse.schedule }}</p>
{% endfor %}
