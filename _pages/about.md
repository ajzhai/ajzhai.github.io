---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**About me**

I am a second-year Ph.D. student in the computer science department at the University of Illinois Urbana-Champaign (UIUC), advised by [Prof. Shenlong Wang](https://shenlong.web.illinois.edu/). Before coming to UIUC, I received my B.S. in computer science from Caltech.

My research focuses on computer vision and robotics, but I have broad interests in other areas of artificial intelligence as well. Currently, I work on 3D modeling and embodied vision.

My middle name, Jianqiao, is my Chinese given name (翟健乔). However, I usually go by Albert.


**Publications**
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}
