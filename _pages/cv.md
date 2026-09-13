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
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024 (expected)
* B.Eng., Shanghai Jiao Tong University, 2024

Research Experience
======
* February 2025 – Present: Research Intern at MINIMAX
* June 2024 – September 2024: Research Intern at Tencent WXG
  * Advisor: Zifei Shan
* June 2023 – December 2023: Research Intern at Shanghai AI Lab
  * Advisor: Prof. Yu Cheng

Skills
======
* Natural Language Processing
* Machine Learning
* Large Language Models
* Reinforcement Learning
* Vision-Language Models

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
