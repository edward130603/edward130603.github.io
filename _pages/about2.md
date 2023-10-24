---
permalink: /about-me/
title: "About"
excerpt: "About me"
author_profile: true
---

{% include base_path %}

Edward Zhao, Ph.D. is a statistician with over 10 years of experience answering genomics, epidemiology, and other life science questions using statistical and machine learning approaches. Dr. Zhao is currently interested in developing statistical analysis methods for spatial transcriptomics and proteomics technologies. He has work experience in academia, pharma, biotech, and government. Dr. Zhao's areas of expertise include spatial statistics, GLMs, mixed models, clustering analysis, supervised learning, and Bayesian statistics.

Education
------
* B.A. in Biochemistry and Mathematical Biology, University of Pennsylvania
* M.S. in Chemistry, University of Pennsylvania
* Ph.D. in Biostatistics, University of Washington - Seattle

Select Publications
------
  <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>