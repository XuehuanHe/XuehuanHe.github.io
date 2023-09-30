---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

The full-text of my articles are accessible or can be accessed on request on <u><a href="{{https://www.researchgate.net/profile/Xuehuan-He-2}}">my researchgate profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
