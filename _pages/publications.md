---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

The focuses of her research to identify the best practices for managing big data within a community, while implementing a comprehensive plan for growth in a traffic region.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://ieeexplore.ieee.org/abstract/document/8766698/}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
