---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.E. in Chemical Engineering, Chemistry, and Mathematics, Vanderbilt University, 2017
* M.S. in Chemical Engineering Practice, Massachusetts Institute of Technology, 2019
* Ph.D. in Chemical Engineering, Massachusetts Institute of Technology, 2022. Thesis: [Integrated, single-cell analysis of transcriptional phenotype and clonotypic identity](https://dspace.mit.edu/handle/1721.1/147228)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
