---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently pursuing a master's degree in Data Science at ETH Zurich. 
I obtained my Bachelor's degree in Telematics Engineering from Instituto Politecnico Nacional (IPN), Mexico. 

I am interested in building safe and trustworthy AI systems with special interest in natural language procesing applications. I’ve also worked as a data scientist at OPI Analytics in Mexico City.


Publications
======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Projects
======
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
