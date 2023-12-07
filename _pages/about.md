---
permalink: /
title: "Biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi everyone, welcome to visit my web! I am an undergraduate graduate student at the University of California, San Diego in Computer Science and Engineering Department. I am currently a research assisstant at [System ENergy Efficiency Lab](http://varys.ucsd.edu/), where I fortunately have been working with Prof. Tajana Rosing. My research interests are efficient and theoretically founded machine learning algorithms applicable in practical settings. If you have any questions or needs, please reach out to me!

Research Interest
======
- Machine learning theory, Kernel method, neural tangent kernel.
- Efficient neuromorphic computing methods: Vector Symbolic Architecture/Hyperdimensional Computing.
- Novel learning paradigms: Online, Few-shot, Federated, Continual, Unsupervised, Multimodal Learning.


Updates
======
- (12/5/2023) This site is created for my PhD application!


Publications
======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
