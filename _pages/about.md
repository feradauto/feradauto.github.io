---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Senior Machine Learning Engineer at Kavak.com.
I have completed my master's degree in Data Science at ETH Zurich. 
I obtained my Bachelor's degree in Telematics Engineering from Instituto Politecnico Nacional (IPN), Mexico. 

I am interested in building safe and trustworthy AI systems with a special interest in natural language processing applications. 

I also worked as a Data Scientist at OPI Analytics in Mexico City.

Publications
======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Projects
======
{% for post in site.portfolio reversed%}
  {% include archive-single.html %}
{% endfor %}
