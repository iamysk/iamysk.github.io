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

* **Ph.D. in Computational Biology & Bioinformatics**, Indian Institute of Technology Delhi (IIT Delhi), 2023
* **B.Tech. in Biotechnology**, G. B. Pant University of Agriculture and Technology (GBPUAT), 2018

## Work Experience

* **Senior Machine Learning Scientist**, Elucidata (Present)
* **Postdoctoral Fellow (Wenner-Gren Fellow)**, Linköping University, Sweden (2024–2026)
  * Supervisor: Prof. Björn Wallner
  * Research on protein ensemble modelling and conformational variation (AFsample2, AFsample3)
* **Doctoral Researcher**, Indian Institute of Technology Delhi (IIT Delhi) (2018–2023)
  * Supervisor: Prof. Durai Sundar
  * Multi-omics data integration, prognosis modelling, and drug-target interaction (DTI) systems

## Skills

* **Machine Learning & Deep Learning:** PyTorch, Transformers, Geometric Deep Learning, CNNs, Ensemble Methods
* **Structural Bioinformatics & Biology:** AlphaFold2/3, Protein Ensemble Modelling, Structural Variation, Molecular Docking
* **Computational Omics & Genomics:** Multi-Omics Integration, Survival Analysis, RNA-seq, Cancer Genomics (LUAD, BRCA)
* **Programming & Tools:** Python, R, Bash, High-Performance Computing (HPC), Git, Docker

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
## Talks

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}</ul>
