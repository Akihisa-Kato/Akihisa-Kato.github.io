---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Publication
======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Work in Progress
======

<!--
{% for post in site.work-in-progress reversed %}
  {% include archive-single.html %}
{% endfor %}
-->

* Optimal Tax Progressivity with Endogenous Marriage and Divorce
* Goldrush (with Jose Victor Rios-Rull)