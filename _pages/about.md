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
我目前在[中国科学院大学](https://www.ucas.edu.cn/)，[过程工程研究所](http://www.ipe.cas.cn/)，[介科学与工程全国重点实验室](https://www.mesolab.ac.cn/)攻读博士学位，导师是副研究员[孟凡勇](https://people.ucas.edu.cn/~0037928)。

主要研究方向为化学工程、人工智能、计算机视觉等多学科交叉研究。具体来说，我正在解决多相流场景中高度重叠目标的检测、表征和生成问题。

# 🔥 News
- *2025.08*: &nbsp;🎉 一篇论文被《AIChE Journal》接收。
- *2025.06*: &nbsp;🎉 正式开始使用并更新我的学术主页。
- *2025.05*: &nbsp;🎉 一篇论文被《Machine Learning: Engineering》接收。
- *2025.04*: &nbsp;🎉 一篇论文被《CT理论与应用研究》接收。

# 📖 Educations
- *2020.09 - 2026.06 (now)*, 硕博连读, 中国科学院大学， 北京. (GPA: **3.76**/4)
- *2016.09 - 2020.06*, 工学学士, 北京化工大学, 北京. (GPA: **3.81**/4.33, rank: **6**/206)

# 📝 Publications 
\# 共同作者; * 通讯作者.
## 📄 Papers 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AIChE J. 2025</div><img src='images/3DBubbles An Experimental Dataset for Model Training and Benchmarking.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[3DBubbles: An Experimental Dataset for Model Training and Benchmarking](https://aiche.onlinelibrary.wiley.com/doi/full/10.1002/aic.70029)

**于宝地**, 陈浅, 秦艳玮, 王孙洋, 苏晓辉, 孟凡勇*

[📄**Code**](https://github.com/AI4CT/3DBubbles)&nbsp;·&nbsp;[💿**Kaggle**](https://www.kaggle.com/datasets/ai4ctofipe/3dbubbles)&nbsp;·&nbsp;[💿**Zenodo**](https://doi.org/10.5281/zenodo.15636832)
- **背景**: 气泡流在多个行业中发挥着重要作用，而人工智能（AI）在该领域的应用有望推动流体动力学研究的进步。然而，缺乏针对人工智能（AI）模型训练和基准测试的高质量实验数据集，已成为关键挑战。
- **目标**: 针对多相流研究中的实验数据瓶颈，提出并开源用于AI模型训练和基准测试的大规模、高质量三维气泡结构实验数据集。
- **方法**: 为解决这一问题，本文提出了一种构建气泡结构数据集的实验方法。该方法首先通过制作静态气泡流模体，利用自研的X射线CT系统对三维气泡结构进行数字化处理。随后，通过球面谐波（SH）分析与渲染算法，对3D结构参数及对应的2D图像标签进行特征提取。
- **结论**: 构建并开源了“3DBubbles”数据集，提供了具有物理真实性的三维气泡几何真值及其渲染后的二维投影图像，为AI模型（尤其是二维到三维重构任务）的训练和基准测试提供了基准数据。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Mach. Learn.: Eng. 2025</div><img src='images/Exploring model generalizability from a novel perspective.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring model generalizability from a novel perspective](https://iopscience.iop.org/article/10.1088/3049-4761/addac6/pdf)

王孙洋, **于宝地**, 孟凡勇*

- **目标**: 针对机器学习（ML）模型泛化性缺乏统一机理解释这一核心挑战，旨在建立一个全新的、具有因果解释能力的理论框架。
- **方法**: 创新性地引入了过程工程领域的介科学（mesoscience）“竞争中的妥协”原理，将模型的“记忆”与“遗忘”提炼为一对相互竞争并决定模型最终行为的核心主导机制。
- **结论**: 该框架为过拟合现象提供了全新的因果解释（即“记忆”对“遗忘”的过度主导），并从机理上重新诠释了正则化等技术，为提升人工智能的可解释性提供了新视角。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CT Theory and Applications 2025</div><img src='images/A Deep Learning Enhanced CT Reconstruction Algorithm for Multiphase Flow Measurement.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep-learning Enhanced CT Reconstruction Algorithm for Multiphase-flow Measurement](https://www.cttacn.org.cn/cn/article/doi/10.15953/j.ctta.2025.097)

陈浅, **于宝地**, 秦艳玮, 王孙洋, 苏晓辉, 金鑫, 孟凡勇*

- **目标**: 旨在解决动态CT在测量多相流时，因数据采集不完备而产生的严重有限角伪影，以及传统迭代算法重建耗时过长的双重难题。
- **方法**: 开发了一种深度学习强化的重建算法，该算法将快速的同步迭代重建技术（SIRT）与U-Net深度学习网络相结合，在图像域高效地完成伪影消除与结构重建任务。
- **结论**: 在保证重建质量的同时，将重建时间缩短了近两个数量级（例如从4.8小时降至3分钟），为实现多相流动态过程的高时空分辨率测量提供了解决方案。
</div>
</div>

## 📚 Patents

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Invention Patent</div><img src='images/一种气液两相流模拟用准动态模体.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multiphase flow quasi-dynamic phantom and CT device testing method for CT device testing](https://cprs.patentstar.com.cn/Search/Detail?ANE=5CBA9FGC6BDA9HBD9EEA2ABA9GDF6CAA9FECFFIA9EGG9EAE)

陈浅, **于宝地**, 苏晓辉, 秦艳玮, 王孙洋, 孟凡勇*. (CN202411542959.8, Substantive Examination)

- **目标**: 针对评估动态CT设备测量多相流性能时的核心难题，即真实流场瞬息万变，无法获得其三维结构“真值”以进行精确的性能标定，设计一个定量评估动态CT的准动态模体。
- **方法**: 准动态模体核心是一个内部包含固定气泡结构的实心“流场柱”，通过控制该柱体以不同速度运动，来模拟可重复、可预测的动态流场。
- **结论**: 该方法能够获取动态测量的CT数据和可精确拼接的静态“真值”数据 ，通过对比两者（如计算SSIM），可定量评估CT设备在不同速度下的测量精度，并确定其“最大可信测试速度”。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Invention Patent</div><img src='images/流场测量数据压缩与存储方法及系统.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Flow field measurement data compression and storage method and system](https://cprs.patentstar.com.cn/Search/Detail?ANE=AIHA6AGA3ABA7DBA4ADA6DCA4EAA9CIF9EAAAIAA9HCC7FCA)

**于宝地**, 孟凡勇*. (CN202311045920.0, Substantive Examination)

- **目标**: 针对高分辨率流场测量（如高速摄影）产生海量数据、存储和传输压力巨大的问题，以及传统基于像素的压缩方法无法保留关键物理结构的缺陷。
- **方法**: 提出了一种基于结构特征的创新压缩方法，利用深度神经网络自动检测流场中的关键结构（如气泡），并将其几何与物理信息提取为低维参数，最终以二进制格式高效存储。
- **结论**: 该方法实现了极高的压缩比（示例中约290:1），显著节省存储空间，同时保留了具有物理意义的核心结构信息，并支持后续的流场重构。
</div>
</div>

<!-- - [Multiphase flow quasi-dynamic phantom and CT device testing method for CT device testing](https://cprs.patentstar.com.cn/Search/Detail?ANE=5CBA9FGC6BDA9HBD9EEA2ABA9GDF6CAA9FECFFIA9EGG9EAE), Qian Chen, **Baodi Yu**, Xiaohui Su, Yanwei Qin, Sunyang Wang, Fanyong Meng*. (CN202411542959.8, Substantive Examination)
- [Flow field measurement data compression and storage method and system](https://cprs.patentstar.com.cn/Search/Detail?ANE=AIHA6AGA3ABA7DBA4ADA6DCA4EAA9CIF9EAAAIAA9HCC7FCA), **Baodi Yu**, Fanyong Meng*. (CN202311045920.0, Substantive Examination) -->

# 🤝 Competitions
- *2025.11* 2025年度介科学与工程全国重点实验室研究生探索与创新奖三等奖
- *2024.12* 全国首届化工行业人工智能应用创新大赛二等奖（华为云承办）
- *2024.01* 第五届北京科学传播大赛科普讲解赛道成人组三等奖
- *2023.06* 中国科学院科普讲解大赛暨全国科普讲解大赛选拔赛优秀奖
- *2021.12* “国科大杯”创新创业大赛总决赛三等奖、分项赛一等奖
- *2019.08* 全国大学生化工设计竞赛全国三等奖、华北赛区二等奖
- *2019.05* 北京市⼤学⽣化⼯原理竞赛个人一等奖
- *2019.04* 美国大学生数学建模竞赛（ICM）国际一等奖（Meritorious Winner）
- *2018.10* 全国大学生数学建模竞赛北京市二等奖
- *2018.04* 美国大学生数学建模竞赛（ICM）国际一等奖（Meritorious Winner）
- *2017.10* 全国大学生数学建模竞赛北京市二等奖

# 💎 Honors and Awards
- *2024.07* 中央和国家机关“四好”党员
- *2022.07* 中国科学院过程工程研究所优秀党务工作者
- *2021.07* 中国科学院大学优秀共产党员
- *2021.06* 中国科学院大学优秀学生干部、三好学生
- *2020.09* 中国科学院大学推免奖学金
- *2020.06* 北京化工大学一等人民奖学金
- *2019.10* 北京化工大学伊比西高额奖学金（10000元）
- *2019.05* 北京化工大学一等人民奖学金
- *2018.12* 北京化工大学优秀学生干部
- *2018.10* 北京化工大学闰土奖学金
- *2017.12* 北京化工大学三好学生
- *2017.10* 北京化工大学华陆科技奖学金
- *2017.04* 北京化工大学二等人民奖学金

# 💼 Societies
- *2023.09 - 2026.06* 中国科学院过程工程研究所介科学研究部心理委员
- *2023.09 - 2026.06* 中国科学院过程工程研究所2023级春博班班长
- *2021.12 - 2024.12* 中国科学院过程工程研究所研究生党总支宣传委员
- *2021.08 - 2024.11* 中国科学院过程工程研究所多相研究生第二党支部书记
- *2020.09 - 2021.07* 中国科学院大学化工学院20202102党支部书记
- *2018.07 - 2020.06* 北京化工大学化学工程学院本科生第二党支部书记
- *2016.09 - 2020.06* 北京化工大学学习委员


<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=1537a2&w=300&t=n&d=zskS-AMir7oZgEoMcIu0848Lt4qyqc-dQ9qsHYEAQDs&co=ffffff&ct=1537a2&cmo=e21e73'></script>

