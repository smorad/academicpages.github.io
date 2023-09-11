---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* PhD in Computer Science - _University of Cambridge_ - Expected 2024
* MS in Aerospace Engineering - _University of Arizona_ 
* BS in Honors Computer Science -  _University of California, Santa Cruz_

## Work Experience
* RLlib - _Software Engineer_
* NASA Jet Propulsion Lab - _Graduate Research Intern_
* Meta - _Production Engineer_
  
## Skills

### Languages
  * Python
  * C, C++

### Frameworks
  * Pytorch, Jax, Numpy
  * Gymnasium, TorchRL, RLlib
  * ROS, ROS2

### Tools
  * Linux, Bash, GNU Coreutils, Git
  * SolidWorks



## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Talks
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
## Teaching
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Service and Leadership
* ICLR reviewer (2024)
* NeurIPS reviewer (2023)
