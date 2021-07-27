---
layout: single
title: Short Course -- Computing at IGPP
permalink: /igpp-computing/
lesson_order: 0
---
There used to be a course called Intro to Computing at IGPP that geophysics students could take during their first year. The goals of the course were to teach incoming students, from a variety of backgrounds, some basic but essential computing skills for classes and research at IGPP. This "boot camp" is a condensed version of that former course. Because of these time constraints, we obviously won't get to go into as much depth as the old course, and we won't have the slick final project (you can find Peter's old course notes [here](https://igpppublic.ucsd.edu/~shearer/COMP233/main.pdf)). But hopefully this introduction will expose you to some situations that you'll see again, and when you learn it a second time, it won't be so bewildering.

While intended for incoming IGPP students, hopefully some of this material is general enough for any students in science looking to improve their computing skills or update their tools. These notes will stay up, so you can come back and read them any time or download them for yourself. As always, please feel free to reach out by email with any questions or comments.

<ul>
   {% for item in site.data.courses.igpp-computing %}
      {% if item.url != page.url %}
         <li><a href="{{ item.url }}">{{ item.title }}</a></li>
      {% endif %}
   {% endfor %}
</ul>