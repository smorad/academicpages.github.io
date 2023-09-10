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
* PhD in Computer Science, University of Cambridge, 2024 (expected)
* MS in Aerospace Engineering, University of Arizona, 2019
* BS in Honors Computer Science, University of California at Santa Cruz, 2015

Work Experience
======
* RLlib 2022-2023: Software Engineer
* NASA Jet Propulsion Lab 2018-2019: Graduate Research Intern
* Meta 2015-2017: Production Engineer
  
Skills
======
* Languages
  * Python
  * C/C++
* Frameworks
  * Pytorch
  * Jax
  * Numpy
  * ROS
  * Gymnasium
  * TorchRL
  * RLlib
* Tools
  * GNU Coreutils
  * Linux



Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and Leadership
======
* ICLR reviewer (2024)
* NeurIPS reviewer (2023)
