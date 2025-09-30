---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Undergraduate Courses
======
__Supply Chain Fundamentals__, University of Houston, 2025
-Introductory course to supply chain topics, including planning, manufacturing, logistics, etc.
-evaluation: 4.59/5

