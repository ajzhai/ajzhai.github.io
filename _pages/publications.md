---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %}
  
{% endif %} -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}

A full list of my publications and conference presentations can be found on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>