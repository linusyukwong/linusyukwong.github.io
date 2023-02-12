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
* B.Eng. in Computer Engineering, Chinese University of Hong Kong, 2015
* M.Phil. in Electronic and Computer Engineering, Hong Kong University of Science and Technology, 2021

Work experience
======
* Summer 2015: Research Assistant
  * Carnegie Mellon University
  * Duties included: Tagging issues
  * Supervisor: Professor Pulkit Grover
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
