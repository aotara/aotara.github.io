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

Journal Article
======

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
