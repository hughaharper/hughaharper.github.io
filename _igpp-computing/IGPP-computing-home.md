---
layout: single
title: Short Course -- Computing at IGPP
permalink: /igpp-computing
---

<ul>
   {% for item in site.data.courses.igpp-computing %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>