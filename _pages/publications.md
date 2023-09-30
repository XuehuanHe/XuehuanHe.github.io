---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{if author.googlescholar }
  Most of my articles are accessible or access on request on <u><a href="{{author.researchgate}}">my researchgate profile</a>.</u>
{endif}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
