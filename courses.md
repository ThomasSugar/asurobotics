---
title: Robotics Courses
description: Explore the range of topics under the Robotics Umbrella
permalink: /courses/
image:
  feature: "Mind-Drones.00_00_57_12.Still001.jpg"
---


| Course Number | Title | Level | Faculty | School | Description |
|--|--|--|--|--|--|--|
{% for course in site.data.courses %}| {{course.Course-Number}}| {% if course.link %}<a href="{{course.link}}" target="_blank">{{course.Title}}</a>{% else %}{{course.Title}}{%endif%} | {{course.Level}} | {{course.Faculty}} | {{course.School}} | {{course.Keywords}} |
{% endfor %}
