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

[1] [Validating hidden Markov models for seabird behavioural inference](https://doi.org/10.1002/ece3.11116)

   **Akeresola, R. A.**, Butler, A., Jones, E. L., King, R., Elvira, V., Black, J., & Robertson, G. (2024). Validating hidden Markov models for seabird behavioural inference. <i>Ecology and Evolution</i>, 14, e11116. 
   
   [BibTeX](http://aotara.github.io/files/hmm.txt) | [Code](https://github.com/aotara/Validating-HMMs-project)
   

[2] [Analysis of the spatial patterns of malnutrition among women in Nigeria with a Bayesian structured additive model](http://aotara.github.io/files/Publication1.pdf) 

  **Akeresola, R.A.**, Gayawan, E. (2020). Analysis of the spatial patterns of malnutrition among women in Nigeria with a Bayesian structured additive model.  <i>GeoJournal</i>. 85. 
  
   [BibTeX](http://aotara.github.io/files/malnutrition.txt)

  ### <span style="color:rgb(199, 21, 133)">Theses:</span>
  
  
  [1] **Akeresola, R. A.** (2025). Modelling animal movement for behavioural inference. <i>PhD Thesis</i>, University of Edinburgh. 
       [Thesis](http://aotara.github.io/files/finalphdthesis.pdf) | [Slides](http://aotara.github.io/files/vivaslide.pdf) 

  [2] **Akeresola, R. A.** (2020). Bayesian Spatio-temporal analysis of greenhouse gas emissions in Africa. <i>MSc Thesis</i>, AIMS-Rwanda.
  
  [Thesis](http://aotara.github.io/files/MScthesis.pdf)


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
