---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.co.uk/citations?user=E1KepzMAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

You can also find my articles on [my Google Scholar profile](https://scholar.google.co.uk/citations?user=E1KepzMAAAAJ&hl=en)

### <span style="color:rgb(199, 21, 133)">Journal Articles:</span>

Analysis of the spatial patterns of malnutrition among women in Nigeria with a Bayesian structured additive model[Download](http://aotara.github.io/files/Publication1.pdf)

Recommended citation: **Akeresola, R.A.**, Gayawan, E. (2020). "Analysis of the spatial patterns of malnutrition among women in Nigeria with a Bayesian structured additive model"  <i>GeoJournal</i>. 85.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
