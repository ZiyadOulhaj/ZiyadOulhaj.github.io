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
* Ph.D in Applied Mathematics, Nantes Université - École Centrale de Nantes, 2023 - present
* Engineering Degree (M.S.) in Applied Mathematics, École Centrale de Nantes, 2020 - 2023
* Classes Préparatoires (Undergraduate) in Mathematics and Physics, Lycée Technique Mohammédia, 2018 - 2020

Work experience
======
* April - September 2023: Research and Development Intern (Fujitsu Ltd.)
  * Topological Data Analysis Methods for Protein Dynamics


* April - August 2022: Research Intern (INRAE - AgroParisTech)
  * Risk Analysis of Late Spring Frost in the Context of Climate Change


Publications and Preprints
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
