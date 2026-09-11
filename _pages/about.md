---
permalink: /
title: "About me"
excerpt: "Kun Zhao — LLM & NLP and Medical AI"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. candidate in **Electrical and Computer Engineering** at the **University of Pittsburgh**, advised by [Prof. Liang Zhan](https://www.engineering.pitt.edu/people/faculty/liang-zhan/). I also collaborate closely with [Prof. Chenghua Lin](https://chenghua-lin.github.io/) at the University of Manchester.

My research develops reliable AI along two parallel directions: **LLM & NLP** methods for evaluating open-ended text generation and improving post-training, and **Medical AI** methods for evidence-grounded multimodal generation and interpretable imaging–genomics modeling. These directions address different tasks and failure modes while contributing to a broader goal of making model outputs more dependable and easier to evaluate.

<p>
  <a class="btn btn--primary" href="/kz.github.io/publications/">Publications</a>
  <a class="btn btn--inverse" href="/kz.github.io/cv/">CV</a>
  <a class="btn btn--inverse" href="https://scholar.google.com/citations?user=XnMDaUcAAAAJ&hl=en">Google Scholar</a>
</p>

## Research

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:1rem;margin:1rem 0 1.25rem;">
  <div style="border:1px solid #d9e2ec;border-radius:8px;padding:1rem 1.1rem;background:#f8fafc;">
    <h3 style="margin-top:0;">LLM &amp; NLP</h3>
    <p><strong>Reliable evaluation of open-ended generation.</strong><br>Modeling multiple valid responses in latent space (CMN), combining specialized small models with LLMs (SLIDE and DRE), and incorporating explicit semantic structure through AMR.</p>
    <p><strong>Post-training and multimodal reasoning.</strong><br>Designing structured feedback and fine-grained credit assignment for outputs with different semantic roles (HERO), and studying visual-conditioned scientific figure understanding (FigEx2).</p>
  </div>
  <div style="border:1px solid #d9e2ec;border-radius:8px;padding:1rem 1.1rem;background:#f8fafc;">
    <h3 style="margin-top:0;">Medical AI</h3>
    <p><strong>Radiology generation and evaluation.</strong><br>Developing lay radiology report generation and semantics-based evaluation (X-ray Made Simple), evidence-grounded RL post-training (HERO), and controlled studies of vision encoders and language backbones.</p>
    <p><strong>Imaging–genomics and brain networks.</strong><br>Integrating parcellated 3D MRI regions with SNP profiles for interpretable NC/SMC/MCI/AD classification (R-GenIMA), and modeling structural–effective brain-network dynamics (STE-ODE).</p>
  </div>
</div>

> **Bridge project.** HERO studies a general credit-assignment problem in RL post-training through a radiology application, linking my methodological interest in reliable learning signals with my work in medical multimodal AI.

## Recent updates

- **[2026]** **“FigEx2: Visual-Conditioned Panel Detection and Captioning for Scientific Compound Figures”** was accepted to the **EMNLP 2026 Main Conference**.
- **[2026]** **“DRE: An Effective Dual-Refined Method for Integrating Small and Large Language Models in Open-Domain Dialogue Evaluation”** was published in *Neural Networks* (109574).
- **[2026]** **“Interpretable Multimodal Learning for Integrating Neuroimaging and Genetic Data in Alzheimer's Disease”** was published in *Frontiers in Radiology*.
- **[2026]** **“X-ray Made Simple: Lay Radiology Report Generation and Robust Evaluation”** appeared in **ACL 2026 Findings**.
- **[2025]** **“Emphasising Structured Information: Integrating Abstract Meaning Representation into LLMs for Enhanced Open-Domain Dialogue Evaluation”** appeared in **EMNLP 2025 Findings**.
- **[2025]** **“Overview of the BioLaySumm 2025 Shared Task on Lay Summarization of Biomedical Research Articles and Radiology Reports”** appeared at the **BioNLP Workshop, ACL 2025**.

## Selected publications

### LLM & NLP

- **[EMNLP 2026 Main]** [FigEx2: Visual-Conditioned Panel Detection and Captioning for Scientific Compound Figures](https://arxiv.org/abs/2601.08026).<br>
  Jifeng Song, Arun Das, Pan Wang, Hui Ji, **Kun Zhao**, Yufei Huang.
- **[Neural Networks 2026 · 2025 JIF: 6.3]** [DRE: An Effective Dual-Refined Method for Integrating Small and Large Language Models in Open-Domain Dialogue Evaluation](https://arxiv.org/abs/2506.04516).<br>
  **Kun Zhao**, Bohao Yang, Chen Tang, Siyuan Dai, Haoteng Tang, Chenghua Lin, Liang Zhan. *(First author)*
- **[EMNLP 2025 Findings]** [Emphasising Structured Information: Integrating Abstract Meaning Representation into LLMs for Enhanced Open-Domain Dialogue Evaluation](https://aclanthology.org/2025.findings-emnlp.1096/).<br>
  Bohao Yang*, **Kun Zhao***, Dong Liu, Chen Tang, Liang Zhan, Chenghua Lin. *(Co-first author)*
- **[ACL 2024 Findings]** [SLIDE: A Framework Integrating Small and Large Language Models for Open-Domain Dialogues Evaluation](https://aclanthology.org/2024.findings-acl.911/).<br>
  **Kun Zhao**, Bohao Yang, Chen Tang, Chenghua Lin, Liang Zhan. *(First author)*
- **[ACL 2023 Main — Oral]** [Evaluating Open-Domain Dialogues in Latent Space with Next Sentence Prediction and Mutual Information](https://aclanthology.org/2023.acl-long.33/).<br>
  **Kun Zhao**, Bohao Yang, Chenghua Lin, Wenge Rong, Aline Villavicencio, Xiaohui Cui. *(First author)*

### Medical AI

- **[Under review, AAAI 2027]** [HERO: Hierarchical Evidential Reasoning Optimization for Radiology Report Generation via Reason-then-Summarize](https://arxiv.org/abs/2601.03321).<br>
  **Kun Zhao**, Guodong Liu, Hui Ji, Siyuan Dai, Pan Wang, Jifeng Song, Chenghua Lin, Liang Zhan, Haoteng Tang. *(First author)*
- **[ACL 2026 Findings]** [X-ray Made Simple: Lay Radiology Report Generation and Robust Evaluation](https://aclanthology.org/2026.findings-acl.1726/).<br>
  **Kun Zhao**, Chenghao Xiao, Sixing Yan, Haoteng Tang, William K. Cheung, Noura Al Moubayed, Liang Zhan, Chenghua Lin. *(First author)*
- **[Frontiers in Radiology 2026 · 2025 JIF: 4.0]** [Interpretable Multimodal Learning for Integrating Neuroimaging and Genetic Data in Alzheimer's Disease](https://www.frontiersin.org/journals/radiology/articles/10.3389/fradi.2026.1912277/full).<br>
  **Kun Zhao**, Siyuan Dai, Yingying Zhang, Guodong Liu, Pengfei Gu, Chenghua Lin, Paul M. Thompson, Alex Leow, Heng Huang, Lifang He, Liang Zhan, Haoteng Tang. *(First author)*
- **[IEEE ICDM Workshops 2025]** [Who Matters More in Radiology Report Generation: Vision Encoders or Language Models?](https://doi.org/10.1109/ICDMW69685.2025.00239).<br>
  **Kun Zhao**, Yang Du, Rhianna Zhang, Liang Zhan, Dongkuan Xu, Pengfei Gu, Haoteng Tang. *(First author)*
- **[MICCAI 2024]** [Interpretable Spatio-Temporal Embedding for Brain Structural-Effective Network with Ordinary Differential Equation](https://papers.miccai.org/miccai-2024/420-Paper0919.html).<br>
  Haoteng Tang, Guodong Liu, Siyuan Dai, Kai Ye, **Kun Zhao**, Wenlu Wang, Carl Yang, Lifang He, Alex Leow, Paul M. Thompson.

*An asterisk denotes equal contribution. See the [Publications](/kz.github.io/publications/) page for the complete list.*

## Academic service

- **Reviewer:** ACL Rolling Review (ARR), NeurIPS, and AAAI.
- **Organizer:** [BioLaySumm Shared Task](https://biolaysumm.org/), BioNLP Workshop at ACL 2025.

<br>
<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=hegehongcha.kz.github.io" alt="visitor count">
</div>
