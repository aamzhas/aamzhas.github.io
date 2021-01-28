---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% if author.github %}
  You can also find some of my projects on <u><a href="{{author.github}}">my Github</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
