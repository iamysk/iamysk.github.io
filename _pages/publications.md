---
permalink: /publications/
title: "Publications"
author_profile: true
---

{% if site.author.googlescholar %}
  <div style="display: flex; justify-content: space-between; align-items: center; padding: 0.85rem 1.25rem; background: #eff6ff; border: 1px solid #dbeafe; border-radius: 10px; margin-bottom: 1.75rem; color: #1e40af; font-size: 0.9rem; flex-wrap: wrap; gap: 0.75rem;">
    <span>For real-time citation metrics, h-index, and updates, visit my Google Scholar profile.</span>
    <a href="{{ site.author.googlescholar }}" target="_blank" rel="noopener noreferrer" class="pub-btn pub-btn--primary">
      <i class="ai ai-google-scholar"></i> Google Scholar
    </a>
  </div>
{% endif %}

<div class="research-summary-intro">
  <p class="hero-tagline">
    My research operates at the nexus of <strong>structural bioinformatics, machine learning, and multi-omics data integration</strong>. Below is an overview of my core research programs, key findings, and methodological innovations, followed by a complete chronological list of publications.
  </p>
</div>

## Research Themes & Key Findings

<div class="research-theme-grid">
  <!-- Theme 1: Dynamics & AlphaFold -->
  <div class="research-theme-card research-theme-card--dynamics">
    <div class="research-theme-card__header">
      <span class="research-theme-card__badge blue">
        <i class="fas fa-dna"></i> Structural Dynamics
      </span>
    </div>
    <h3 class="research-theme-card__title">Protein Conformational Ensembles & Dynamics</h3>
    <p class="research-theme-card__desc">
      Overcoming the single-state limitation of deep learning structure prediction to model protein flexibility, alternative states, and conformational ensembles.
    </p>
    <ul class="research-theme-card__findings">
      <li>
        <strong>Overcoming Single-State Prediction:</strong> Standard AlphaFold models predict a single rigid conformation. Developed <em>AFsample2</em> (<em>Communications Biology</em>, 2025) and <em>AFsample3</em> (<em>bioRxiv</em>, 2026), proving that targeted MSA subsampling and diffusion scaling enable AlphaFold to sample conformational ensembles matching experimental NMR/X-ray alternative states.
      </li>
      <li>
        <strong>State Selection & Ranking:</strong> Engineered automated clustering and scoring metrics to filter and select biologically relevant, high-confidence conformational states from generative candidate distributions.
      </li>
      <li>
        <strong>Structural Plasticity Review:</strong> Authored an authoritative review on computational methods for predicting structural variation and protein flexibility (<em>Current Opinion in Structural Biology</em>, 2025).
      </li>
    </ul>
    <div class="research-theme-card__pubs">
      <span class="label">Key Papers:</span>
      <span class="pub-tag">AFsample3 (2026)</span>
      <span class="pub-tag">AFsample2 (2025)</span>
      <span class="pub-tag">COSB Review (2025)</span>
    </div>
  </div>

  <!-- Theme 2: Drug Discovery & DTI -->
  <div class="research-theme-card research-theme-card--dti">
    <div class="research-theme-card__header">
      <span class="research-theme-card__badge green">
        <i class="fas fa-pills"></i> Drug Discovery
      </span>
    </div>
    <h3 class="research-theme-card__title">Drug-Target Interactions & AI-Driven Therapeutics</h3>
    <p class="research-theme-card__desc">
      Coupling protein language models and geometric deep learning with chemical representations to predict binding affinities and discover therapeutic leads.
    </p>
    <ul class="research-theme-card__findings">
      <li>
        <strong>Language Models for DTIs:</strong> Developed <em>TransDTI</em> (<em>ACS Omega</em>, 2022), pairing transformer protein language models with chemical SMILES embeddings to estimate continuous binding affinities and automate drug recommendation.
      </li>
      <li>
        <strong>Geometric Deep Learning:</strong> Formulated 3D geometric deep learning architectures coupled with mixture density networks to capture non-linear, spatial protein-ligand interactions without rigid docking constraints (<em>Journal of Biosciences</em>, 2024).
      </li>
      <li>
        <strong>High-Throughput Lead Prioritization:</strong> Engineered deep learning workflows utilizing SMILES representations to screen chemical libraries and prioritize high-affinity anticancer leads (<em>ACS Omega</em>, 2024).
      </li>
    </ul>
    <div class="research-theme-card__pubs">
      <span class="label">Key Papers:</span>
      <span class="pub-tag">TransDTI (2022)</span>
      <span class="pub-tag">Geometric DL (2024)</span>
      <span class="pub-tag">ACS Omega (2024)</span>
    </div>
  </div>

  <!-- Theme 3: Multi-Omics & Oncology -->
  <div class="research-theme-card research-theme-card--omics">
    <div class="research-theme-card__header">
      <span class="research-theme-card__badge purple">
        <i class="fas fa-chart-line"></i> Oncology Omics
      </span>
    </div>
    <h3 class="research-theme-card__title">Multi-Omics Fusion & Clinical Prognosis</h3>
    <p class="research-theme-card__desc">
      Integrating high-dimensional genomic, transcriptomic, and clinical datasets with deep neural networks for patient stratification and survival modeling.
    </p>
    <ul class="research-theme-card__findings">
      <li>
        <strong>Image-Based Survival Modeling:</strong> Formulated <em>SurvCNN</em> (<em>Cancers</em>, 2021), converting multi-omics profiles into structured 2D matrix representations to model discrete time-to-event cancer survival with convolutional networks.
      </li>
      <li>
        <strong>Synergistic Multimodal Fusion:</strong> Demonstrated that integrating CNVs, mRNA expression, and DNA methylation significantly outperforms single-omics baselines in patient survival stratification and drug-response forecasting (<em>BMC Genomics</em>, 2021; <em>GHCI</em>, 2019).
      </li>
      <li>
        <strong>Interpretable Sequence Regulation:</strong> Applied interpretable deep learning architectures to decode how proximal genomic elements and sequence motifs modulate DNA-protein interactions (<em>Journal of Molecular Biology</em>, 2023).
      </li>
    </ul>
    <div class="research-theme-card__pubs">
      <span class="label">Key Papers:</span>
      <span class="pub-tag">SurvCNN (2021)</span>
      <span class="pub-tag">BMC Genomics (2021)</span>
      <span class="pub-tag">JMB (2023)</span>
    </div>
  </div>

  <!-- Theme 4: Sequence Embeddings & Networks -->
  <div class="research-theme-card research-theme-card--annotation">
    <div class="research-theme-card__header">
      <span class="research-theme-card__badge amber">
        <i class="fas fa-network-wired"></i> Biomolecular Networks
      </span>
    </div>
    <h3 class="research-theme-card__title">Sequence Embeddings & Interaction Networks</h3>
    <p class="research-theme-card__desc">
      Inferring biochemical binding sites directly from sequence representations and mapping complex macromolecular interaction networks.
    </p>
    <ul class="research-theme-card__findings">
      <li>
        <strong>Sequence-Based Metal-Ion Binding:</strong> Created <em>M-Ionic</em> (<em>Bioinformatics</em>, 2024), leveraging pre-trained protein language model residue embeddings to identify transition metal-ion binding sites (Zn²⁺, Fe²⁺/³⁺, Cu²⁺, Mg²⁺, Ca²⁺) directly from sequence without solved 3D structures.
      </li>
      <li>
        <strong>Interactome Modeling Protocols:</strong> Authored comprehensive protocols and graph learning workflows for elucidating protein-protein interaction (PPI) networks (<em>Methods in Molecular Biology</em>, 2022).
      </li>
      <li>
        <strong>Genomic Discovery:</strong> Sequenced and functionally annotated the complete genome of <em>Franconibacter</em> sp. IITDAS19, characterizing biosurfactant biosynthesis pathways (<em>MRA</em>, 2022).
      </li>
    </ul>
    <div class="research-theme-card__pubs">
      <span class="label">Key Papers:</span>
      <span class="pub-tag">M-Ionic (2024)</span>
      <span class="pub-tag">PPI Networks (2022)</span>
      <span class="pub-tag">MRA (2022)</span>
    </div>
  </div>
</div>

<div class="publications-list-header">
  <h2>All Publications</h2>
  <span class="count-badge">14 Articles & Preprints</span>
</div>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
