---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div style="display: flex; justify-content: space-between; align-items: center; padding: 0.85rem 1.25rem; background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; margin-bottom: 2rem; flex-wrap: wrap; gap: 0.75rem;">
  <div>
    <strong style="color: #0f172a;">Curriculum Vitae</strong>
    <p style="margin: 0; font-size: 0.85rem; color: #64748b;">Comprehensive overview of academic training, industry research, publications, and talks.</p>
  </div>
  <a href="mailto:yogesh.kalakoti@liu.se?subject=Requesting%20Full%20CV" class="pub-btn pub-btn--primary">
    <i class="fas fa-envelope"></i> Request Full PDF CV
  </a>
</div>

## Education

<div class="news-timeline">
  <div class="news-item">
    <span class="news-date">2018 – 2023</span>
    <div class="news-content">
      <strong>Ph.D. in Computational Biology & Bioinformatics</strong><br />
      <em>Indian Institute of Technology Delhi (IIT Delhi), India</em><br />
      <span style="font-size: 0.85rem; color: #64748b;">Advisor: Prof. Durai Sundar · Multi-omics data integration for cancer survival prediction & drug discovery</span>
    </div>
  </div>
  <div class="news-item">
    <span class="news-date">2014 – 2018</span>
    <div class="news-content">
      <strong>B.Tech. in Biotechnology</strong><br />
      <em>G. B. Pant University of Agriculture and Technology (GBPUAT), India</em><br />
      <span style="font-size: 0.85rem; color: #64748b;">Advisor: Prof. Sanjeev Agarwal · Antimicrobial profiling of plant secondary metabolites</span>
    </div>
  </div>
</div>

## Professional Experience

<div class="news-timeline">
  <div class="news-item">
    <span class="news-date">Present</span>
    <div class="news-content">
      <strong>Senior Machine Learning Scientist</strong><br />
      <em>Elucidata</em><br />
      <span style="font-size: 0.85rem; color: #64748b;">AI/ML models for computational biology, functional genomics, and biomedical data analysis</span>
    </div>
  </div>
  <div class="news-item">
    <span class="news-date">2024 – 2026</span>
    <div class="news-content">
      <strong>Postdoctoral Fellow (Wenner-Gren Foundation)</strong><br />
      <em>Bioinformatics Division, Linköping University, Sweden</em><br />
      <span style="font-size: 0.85rem; color: #64748b;">Advisor: Prof. Björn Wallner · Developed AFsample2 & AFsample3 for protein ensemble generative modeling</span>
    </div>
  </div>
  <div class="news-item">
    <span class="news-date">2018 – 2023</span>
    <div class="news-content">
      <strong>Doctoral Researcher & Teaching Fellow</strong><br />
      <em>Indian Institute of Technology Delhi (IIT Delhi)</em><br />
      <span style="font-size: 0.85rem; color: #64748b;">Developed TransDTI (transformer-based DTI workflow) and SurvCNN for time-to-event oncology modeling</span>
    </div>
  </div>
</div>

## Technical Expertise

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1rem; margin-bottom: 2rem;">
  <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem;">
    <strong style="color: #0f172a; font-size: 0.95rem; display: block; margin-bottom: 0.5rem;"><i class="fas fa-brain" style="color: #2563eb; margin-right: 0.4rem;"></i> Machine Learning & AI</strong>
    <p style="margin: 0; font-size: 0.85rem; color: #475569; line-height: 1.5;">PyTorch, Transformers, Geometric Deep Learning, Graph Neural Networks, CNNs, Ensemble Learning</p>
  </div>
  <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem;">
    <strong style="color: #0f172a; font-size: 0.95rem; display: block; margin-bottom: 0.5rem;"><i class="fas fa-dna" style="color: #2563eb; margin-right: 0.4rem;"></i> Structural Biology</strong>
    <p style="margin: 0; font-size: 0.85rem; color: #475569; line-height: 1.5;">AlphaFold2/3, Protein Ensemble Modeling, Structural Variation, Conformational Sampling, Molecular Docking</p>
  </div>
  <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem;">
    <strong style="color: #0f172a; font-size: 0.95rem; display: block; margin-bottom: 0.5rem;"><i class="fas fa-chart-line" style="color: #2563eb; margin-right: 0.4rem;"></i> Multi-Omics & Oncology</strong>
    <p style="margin: 0; font-size: 0.85rem; color: #475569; line-height: 1.5;">Multi-Omics Integration, Survival Analysis (Discrete Time-to-Event), RNA-seq, Cancer Genomics (LUAD, BRCA)</p>
  </div>
  <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 10px; padding: 1rem;">
    <strong style="color: #0f172a; font-size: 0.95rem; display: block; margin-bottom: 0.5rem;"><i class="fas fa-terminal" style="color: #2563eb; margin-right: 0.4rem;"></i> Tools & Infrastructure</strong>
    <p style="margin: 0; font-size: 0.85rem; color: #475569; line-height: 1.5;">Python, R, Bash, High-Performance Computing (HPC/SLURM), Git, Docker, Nextflow</p>
  </div>
</div>

## Selected Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
  
## Selected Talks & Presentations

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
