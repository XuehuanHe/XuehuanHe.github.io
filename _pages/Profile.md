---
layout: archive
title: "Profile"
permalink: /Profile/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Mechanical Engineering, University of Iowa, 2022
* M.S. in Mechanical Engineering, University of Minnesota, Duluth, 2018
* B.S. in Mechanical Design, Manufacturing and Automation, University of Chang’an, China, 2015

Honors and Awards
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
