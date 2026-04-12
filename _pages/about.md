---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I’m Runjiu Chen, an ScM student in Epidemiology (Genetic track) at the Johns Hopkins Bloomberg School of Public Health. My research sits at the intersection of genetic epidemiology, machine learning, and computational genomics, with a focus on building interpretable models for complex biological and clinical data.

I have worked on spatiotemporal modeling of brain transcriptomic heterogeneity in development and Alzheimer’s disease, including the design of a two-stage framework that integrates spatiotemporal weighting and multi-step decision-tree modeling. I also study single-cell dynamics, applying RNA velocity and multi-omics integration to reconstruct lineage trajectories and infer cell fate transitions. In parallel, I develop clinical risk prediction models (e.g., depression risk in type 2 diabetes) using a combination of structural equation modeling and machine learning.

Previously, I received a B.S. in Statistics from Hunan University and completed a statistics program at UC Berkeley. I’m broadly interested in principled methods that translate high-dimensional omics and neuro/clinical signals into actionable insights—especially when interpretability and robustness matter.

<span class='anchor' id='publications'></span>
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Briefings in Bioinformatics 2024</div><img src='images/sample.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[STW-MD: a novel spatio-temporal weighting and multi-step decision tree method for considering spatial heterogeneity in brain gene expression data](https://academic.oup.com/bib/article/25/2/bbae051/7611940)

Shanjun Mao , Xiao Huang , Runjiu Chen , Chenyang Zhang , Yizhu Diao , Zongjin Li , Qingzhe Wang , Shan Tang , Shuixia Guo

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Spatiotemporal ML for Brain Transcriptomics 
</div>
</div>

- [Cell Lineage Tracing: methods, applications, and challenges](https://github.com), Shanjun Mao, Chenyang Zhang, Runjiu Chen, Shan Tang, Xiaodan Fan, Jie Hu **Quantitative Biology 2025**

<span class='anchor' id='research-experience'></span>
# 🔬 Research Experience

**Deep Tensor Factorization for Differential Epigenomic Pattern Detection** (Jan 2026 – Now)  
*Supervised by Weiqiang Zhou, Bloomberg School of Public Health, JHU, Baltimore, MD, USA*  
Reproduced and extended HiPlex analysis pipelines for combinatorial chromatin profiling data. Implemented differential epigenomic pattern detection methods, including deep tensor factorization and dPCA, to identify region-level epigenomic changes between control and treatment conditions.

**Shared Genetic Architecture and Causal Inference in T2D and CAD/MI** (Sep 2025 – Now)  
*Supervised by Debashree Ray, Bloomberg School of Public Health, JHU, Baltimore, MD, USA*  
Investigating shared genetic architecture and potential causal directions between type 2 diabetes and CAD/MI using publicly available GWAS summary statistics. Performed analyses including LDSC, Mendelian randomization, and follow-up colocalization to evaluate genetic correlation, shared liability, and putative causal effects.

**Machine Learning for Omics: Single-Cell, Multi-Omics, and Clinical Prediction** (May 2022 – May 2025)  
*Supervised by Shanjun Mao, School of Finance and Statistics, HNU, Hunan, China*  
- **Spatiotemporal ML for Brain Transcriptomics (STW-MD, *Briefings in Bioinformatics*)** – Developed a two-stage machine learning framework for modeling spatiotemporal heterogeneity in brain gene expression across development and Alzheimer’s disease (AD). Implemented spatiotemporal weighting to capture dependencies across developmental stages and brain regions, and integrated multi-step decision-tree modeling to improve gene-class identification and characterize associations with developmental trajectories and AD progression. Analyzed 18,431 genes across 19 brain regions; implemented a weighted Limma model to identify stage-specific biomarkers. The proposed approach enhanced sensitivity to region-specific signals and improved interpretability in heterogeneous brain transcriptomic profiles.  
- **Single-cell Lineage Inference (RNA velocity, *Quantitative Biology*)** – Applied RNA velocity to infer directional dynamics of single-cell transcriptomes and reconstruct cellular lineage trajectories and fate decisions. Conducted high-dimensional preprocessing, parameter tuning, and multi-omics integration to refine the biological resolution of cell state transitions. *Impact:* Improved lineage resolution and biological interpretability, supporting more reliable identification of cell fate transitions.  
- **Depression Risk Prediction in T2DM (SEM + ML)** – Built a depression risk prediction pipeline for T2DM patients using SEM-derived latent constructs and machine learning classifiers (e.g., logistic regression, random forest). Improved risk stratification performance and supported earlier identification of high-risk patients with T2DM-related depression via LASSO feature selection and multi-class evaluation.

**Advancements in Brain-Computer Interface Technologies: Bridging Human Cognition and Artificial Intelligence** (Jan 2024 – Jul 2024)  
*Supervised by Lexin Li, School of Public Health, UC Berkeley, Berkeley, CA, USA*  
Applied advanced deep learning techniques for EEG-to-text decoding and sentiment classification. Key methods include pre-trained large language models (e.g., BART) for open-vocabulary decoding and zero-shot sentiment classification, enabling emotion and text generation directly from EEG signals.

<span class='anchor' id='honors-and-awards'></span>
# 🎖 Honors and Awards
- *2024.10* Undergraduate Overseas (or International) Special Scholarship, (Only 15 Person in HNU Per Year) 
- *2021.09* MI Social Endowment Scholarship, (Only 50 Person in HNU Per Year)

<span class='anchor' id='education'></span>
# 📖 Educations
- *2019.06 - 2022.04 (now)*, Johns Hopkins Univeristy, Bloomberg School of Public Health, Epidemiology
- *2021.09 - 2025.06*, Hunan University, School of Finance and Statistics, Statistics
- *2024.01 - 2024.08*, University of California, Berkeley, School of Finance and Statistics, Statistics

<span class='anchor' id='skills'></span>
# 💬 Skills
- *Computing*, Pytorch, Python, R , C++, Java, PowerBI, Stata, MS Office, Matlab

<span class='anchor' id='internships'></span>
# 💻 Internships
- *2026.02 - 2026.05*, Sandalwood advisors, China.