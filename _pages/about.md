---
permalink: /about/
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about.html
---

{% include base_path %}

Edward Zhao, Ph.D. is a statistician with over 10 years of experience answering genomics, epidemiology, and other life science questions using statistical approaches. Dr. Zhao is currently a biostatistician at NanoString Technologies, where he is developing statistical analysis methods and pipelines for spatial transcriptomics and proteomics technologies. He has previously worked in academia, pharma, biotech, and government. Dr. Zhao's areas of expertise include spatial statistics, GLMs, mixed models, clustering analysis, supervised learning, and Bayesian statistics.

Education
======
* B.A. in Biochemistry and Mathematical Biology, University of Pennsylvania, 2017
* M.S. in Chemistry, University of Pennsylvania, 2017
* Ph.D. in Biostatistics, University of Washington - Seattle, 2022

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>