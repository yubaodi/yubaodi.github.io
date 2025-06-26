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
I am currently pursuing a PhD at the [State Key Laboratory of Mesoscience and Engineering](https://www.mesolab.ac.cn), [Institute of Process Engineering](http://english.ipe.cas.cn), [University of Chinese Academy of Sciences](https://english.ucas.ac.cn), under the supervision of Associate Researcher [Meng Fanyong](https://people.ucas.edu.cn/~0037928).

My research focuses on interdisciplinary studies in multiphase flow measurement, fluid mechanics, computer vision, and artificial intelligence. Specifically, I am working on the detection, characterization, and generation of highly overlapping scenarios in multiphase flows.

# 🔥 News
- *2025.06*: &nbsp;🎉 I have officially started using and updating my academic homepage. 
- *2025.05*: &nbsp;🎉 One paper was accepted to Machine Learning: Engineering.

# 📖 Educations
- *2020.09 - 2026.06 (now)*, Integrated Master-PhD Program, University of Chinese Academy of Sciences (UCAS), Beijing. (GPA: **3.76**/4)
- *2016.09 - 2020.06*, Undergraduate, Beijing University of Chemical Technology (BUCT), Beijing. (GPA: **3.81**/4.33, rank: **6**/206)

# 📝 Publications 
\* Equal Contributions; # Corresponding Authors; cs: coming soon.
## 📄 Papers 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AIChE J. 2025</div><img src='images/3DBubbles An Experimental Dataset for Model Training and Benchmarking.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

3DBubbles: An Experimental Dataset for Model Training and Benchmarking(**cs**)

**Baodi Yu**, Qian Chen Yanwei Qin, Sunyang Wang, Xiaohui Su, Fanyong Meng*

[**Code**](https://github.com/AI4CT/3DBubbles)·[**Kaggle**](https://www.kaggle.com/datasets/ai4ctofipe/3dbubbles)·[**Zenodo**](https://doi.org/10.5281/zenodo.15636832)
- **Objective**: Addressed a critical bottleneck in fluid dynamics research: the lack of high-quality, large-scale experimental datasets of 3D bubble structures for training and benchmarking Artificial Intelligence (AI) models.
- **Methodology**: Developed a novel method for dataset construction by preparing static bubbly flow phantoms, digitizing over 10,000 real 3D bubble structures using an in-house X-ray CT system, and characterizing them with Spherical Harmonic (SH) analysis for efficient compression.
- **Contribution**: Constructed and open-sourced the "3DBubbles" dataset, providing the scientific community with physically plausible 3D ground-truth bubble geometries and their rendered 2D projections, which serve as valuable benchmark data for robust training and rigorous evaluation of AI models, particularly for 2D-to-3D reconstruction tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Mach. Learn.: Eng. 2025</div><img src='images/Exploring model generalizability from a novel perspective.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring model generalizability from a novel perspective](https://iopscience.iop.org/article/10.1088/3049-4761/addac6/pdf)

Sunyang Wang, **Baodi Yu**, Fanyong Meng*

- **Objective**: To address the dual challenges in dynamic CT for multiphase flows: severe limited-angle artifacts due to incomplete data acquisition and prohibitively long reconstruction times of traditional iterative algorithms.
- **Methodology**: Developed a deep-learning-enhanced reconstruction algorithm that integrates a rapid SIRT method with a U-Net model, efficiently removing artifacts and restoring structures in the image domain.
- **Contribution**: Reduced reconstruction time by nearly two orders of magnitude (e.g., from 4.8 hours to 3 minutes) while ensuring high-quality results, providing a key technology for high-spatiotemporal-resolution analysis of dynamic flow fields
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CT Theory and Applications 2025</div><img src='images/A Deep Learning Enhanced CT Reconstruction Algorithm for Multiphase Flow Measurement.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep-learning Enhanced CT Reconstruction Algorithm for Multiphase-flow Measurement](https://www.cttacn.org.cn/cn/article/doi/10.15953/j.ctta.2025.097)

Qian Chen, **Baodi Yu**, Yanwei Qin, Sunyang Wang, Xiaohui Su, Xin Jin, Fanyong Meng*

- **Objective**: To address the key challenge of lacking a unified mechanistic explanation for the generalizability of Machine Learning (ML) models by establishing a novel theoretical framework with causal explanatory power.
- **Methodology**: Introduced the "Compromise in Competition" (CIC) principle from mesoscience, identifying the interplay between "memorizing" and "forgetting" as the core competing mechanisms that govern a model's final behavior.
- **Contribution**: This framework provides a new causal interpretation for overfitting (as the result of memorizing excessively dominating forgetting) and reinterprets the mechanisms of techniques like regularization, offering a new perspective on AI interpretability.
</div>
</div>

## 📚 Patents

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Invention Patent</div><img src='images/一种气液两相流模拟用准动态模体.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multiphase flow quasi-dynamic phantom and CT device testing method for CT device testing](https://cprs.patentstar.com.cn/Search/Detail?ANE=5CBA9FGC6BDA9HBD9EEA2ABA9GDF6CAA9FECFFIA9EGG9EAE)

Qian Chen, **Baodi Yu**, Xiaohui Su, Yanwei Qin, Sunyang Wang, Fanyong Meng*. (CN202411542959.8, Substantive Examination)

- **Objective**: To solve the core difficulty in evaluating the performance of dynamic CT scanners for multiphase flow: the inability to obtain the 3D ground truth of a real, transient flow field for accurate performance calibration.
- **Methodology**: Invented a "quasi-dynamic phantom" featuring a solid "flow-field pillar" with fixed internal bubble structures. This pillar is moved at controlled speeds to simulate a repeatable and predictable dynamic flow field.
- **Contribution**: This method allows for the acquisition of both dynamic CT data and its corresponding, precisely assembled static ground-truth data. By comparing the two (e.g., via SSIM), the scanner's accuracy at various speeds can be quantitatively evaluated to determine its "maximum trustworthy test speed".
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Invention Patent</div><img src='images/流场测量数据压缩与存储方法及系统.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Flow field measurement data compression and storage method and system](https://cprs.patentstar.com.cn/Search/Detail?ANE=AIHA6AGA3ABA7DBA4ADA6DCA4EAA9CIF9EAAAIAA9HCC7FCA)

**Baodi Yu**, Fanyong Meng*. (CN202311045920.0, Substantive Examination)

- **Objective**: To address the massive data volume from high-resolution flow-field measurements (e.g., high-speed cameras) which creates immense storage and transmission pressure, and the inability of traditional pixel-based compression to preserve key physical structures.

- **Methodology**: Proposed a novel structure-based compression method that uses a deep neural network to automatically detect key structures (e.g., bubbles) in the flow field  and extracts their geometric and physical information into low-dimensional parameters for efficient binary storage.
- **Contribution**: This method achieves an extremely high compression ratio (approx. 290:1 in the example) , significantly saving storage space while preserving physically meaningful structural information and enabling subsequent flow-field reconstruction.
</div>
</div>

<!-- - [Multiphase flow quasi-dynamic phantom and CT device testing method for CT device testing](https://cprs.patentstar.com.cn/Search/Detail?ANE=5CBA9FGC6BDA9HBD9EEA2ABA9GDF6CAA9FECFFIA9EGG9EAE), Qian Chen, **Baodi Yu**, Xiaohui Su, Yanwei Qin, Sunyang Wang, Fanyong Meng*. (CN202411542959.8, Substantive Examination)
- [Flow field measurement data compression and storage method and system](https://cprs.patentstar.com.cn/Search/Detail?ANE=AIHA6AGA3ABA7DBA4ADA6DCA4EAA9CIF9EAAAIAA9HCC7FCA), **Baodi Yu**, Fanyong Meng*. (CN202311045920.0, Substantive Examination) -->

# 🤝 Competitions
- *2024.12* National Second Prize, First National Artificial Intelligence Application Innovation Competition in the Chemical Industry
- *2024.01* Provincial Third Prize, Beijing Science Communication Competition
- *2021.12* National First Prize (1st), "University of Chinese Academy of Sciences Cup" Innovation and Entrepreneurship Competition, Software and Internet Category
- *2019.08* National Third Prize, National College Student Design Competition
- *2019.04* Meritorious Winner, International Mathematical Modeling Contest: The Interdisciplinary Contest in Modeling (ICM).
- *2018.10* Provincial Second Prize, National Mathematical Modeling Contest.
- *2018.04* Meritorious Winner, International Mathematical Modeling Contest: The Interdisciplinary Contest in Modeling (ICM).
- *2017.10* Provincial Second Prize, National Mathematical Modeling Contest.

# 💎 Honors and Awards
- *2024.07* National Outstanding Communist Party Member
- *2022.07* Excellent Communist Party cadre in University of Chinese Academy of Sciences
- *2021.07* Outstanding Communist Party Member in University of Chinese Academy of Sciences
- *2021.06* Excellent Student Cadre in University of Chinese Academy of Sciences
- *2020.09* Recommended Scholarship for Graduate Admissions without Entrance Examination in University of Chinese Academy of Sciences
- *2019.04* First Prize Scholarship in Beijing University of Chemical Technology
- *2018.12* Excellent Student Cadre in Beijing University of Chemical Technology
- *2018.10* Shantou Zhejiang Runtu Co., Ltd. Scholarship
- *2017.12* Merit Student in Beijing University of Chemical Technology
- *2017.10* HuaLu Engineering & Technology Co., ltd. Scholarship
- *2017.04* Second Prize Scholarship in Beijing University of Chemical Technology

# 💼 Societies
- *2023.09 - 2026.06* Class Leader in University of Chinese Academy of Sciences
- *2020.12 - 2024.12* Member of General Party Branch Committee in University of Chinese Academy of Sciences
- *2020.09 - 2024.11* Secretary of Party Branch Committee in University of Chinese Academy of Sciences
- *2018.07 - 2020.06* Secretary of Party Branch Committee in Beijing University of Chemical Technology
- *2016.09 - 2020.06* Class Study Monitor in Beijing University of Chemical Technology


<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=1537a2&w=300&t=n&d=zskS-AMir7oZgEoMcIu0848Lt4qyqc-dQ9qsHYEAQDs&co=ffffff&ct=1537a2&cmo=e21e73'></script>

