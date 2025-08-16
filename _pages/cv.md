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
* Ph.D in Mathematics, Georgia Institute of Technology, 2030 (expected)
* B.S. in Mathematics (with honors), University of Chicago, 2025.  

Work experience
======
* Summer 2025 - Quantitative Research Intern (Octus)
  * Worked on linear-programming-based trade suggestion optimizer for managing CLO portfolios. 
  * Developed and tested incremental trading functionality, designed an LP problem generation algorithm.

* Fall 2020 - Spring 2023: Private Math Tutor
  * Tutored middle/high school students in K-12 math. 
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
