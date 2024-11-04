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
* B.S. in Computer Science, University of Waterloo, (expected) 2025

Work Experience
======
* **Google DeepMind**: Research Intern (Summer 2024)
  * Evolutionary algorithms; foundational research team

* **Cohere**: Machine Learning Intern (Fall 2022)
  * Distributed training of large language models

* **Wish**: Software Engineering Intern (Winter 2022)
  * Writing product recommendation algorithms

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
