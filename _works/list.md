---
date: 2018-03-22 22:02:46 +1300
work-date: 2012-03-22 00:00:00 +1300

title: List of works
layout: page
# permalink: /works/index.html
---


{% for item in site.works %}
  <h2 class= "green f3 fw6">{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ item.url }}">{{ item.title }}</a><br />
    {{ item.medium }}</p>
{% endfor %}
