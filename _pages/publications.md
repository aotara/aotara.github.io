---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## Journal Articles

{% for post in site.publications reversed %}

- **{{ post.title }}**  
  {{ post.authors }} ({{ post.year }}). *{{ post.venue }}*.  
  {% if post.arxiv %}[arXiv] | {% endif %}
  {% if post.bibtex %}[BibTeX] | {% endif %}
  {% if post.doi %}[DOI] | {% endif %}
  {% if post.code %}[Code]{% endif %}

{% endfor %}
