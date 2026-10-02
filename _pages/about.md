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

👋 Hi! I am **Enyi Wang** (<span style="font-family:'KaiTi','STKaiti','Kaiti SC','DFKai-SB','AR PL UKai CN',serif; font-weight:bold; font-size:1.15em;">王恩驿</span> in Chinese). I am currently an **MRes (Master of Research)** student at **Imperial College London**, affiliated with the **[Hamlyn Centre](https://www.imperial.ac.uk/hamlyn-centre/)** and **[I-X](https://ix.imperial.ac.uk/)**. I am supervised by **[Prof. Dandan Zhang](https://profiles.imperial.ac.uk/d.zhang17)** at the **[Multi-Scale Embodied Intelligence Lab](https://www.intelligentrobotics-acrossscales.com/)**.  

Before that, I received my **B.Eng. degree** from **Fuzhou University** (**211 Project, China**) in 2024, where I conducted research on continuum surgical robots supervised by **[Prof. Zhen Deng](https://scholar.google.com/citations?user=rbUYdmoAAAAJ&hl=zh-CN&oi=ao)**


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


## 🔬 Research Interests
Currently I am interested in **robotic manipulation**, **tactile sensing**, **imitation learning**, and **vision-language-action (VLA)** systems, aiming to advance **robot learning** through multi-modal perception and generalizable policy learning. My goal is to develop intelligent embodied agents that can perceive, reason, and act effectively like humans in the future.

# 📢 News
- *2026.02*: &nbsp;🎉🎉 Our paper *“ADM-DP: Adaptive Dynamic Modality Diffusion Policy through Vision-Tactile-Graph Fusion for Multi-Agent Manipulation”* was **accepted to ICRA 2026**!
- *2025.10*: &nbsp;🎉🎉 My MRes thesis "Multimodal Representation Learning for Multi-Robot Collaborative Manipulation" received **Distinction** at Imperial College London!
- *2025.06*: &nbsp;🎉🎉 Our Paper *“Estimating Continuum Robot Shape under External Loading using Spatiotemporal Neural Networks”* was **accepted to IROS 2025** (from my final year project during undergraduate)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image' style="box-shadow:none !important; -webkit-box-shadow:none !important; background:transparent;">
<div style="box-shadow:none !important; -webkit-box-shadow:none !important; background:transparent;">
<img src='images/TacDyn-WAM.png' alt="TacDyn-WAM model framework" width="100%" style="box-shadow:none !important; -webkit-box-shadow:none !important; border:none;">
</div></div>
<div class='paper-box-text' markdown="1">

[TacDyn-WAM: Learning Implicit Tactile Dynamics in a Heterogeneous Visuo-Tactile World Action Model](https://arxiv.org/abs/2610.00638)

**Enyi Wang**, Mingxin Wang, Quan Shi, Hetian Guo, Hongyu Wang, Xi Wang, Bin Qian, Yupeng Zheng, Wenxuan Song, Houde Liu, Yong Xu, Cheng Chi, Wenchao Ding, Yilun Chen, Yan Wang

[**Under Review**]
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="box-shadow:none !important; -webkit-box-shadow:none !important; background:transparent;">
<div style="box-shadow:none !important; -webkit-box-shadow:none !important; background:transparent;">
<img src='images/ST-WAM.png' alt="ST-WAM model architecture and current-anchored intent retrieval" width="100%" style="box-shadow:none !important; -webkit-box-shadow:none !important; border:none;">
</div></div>
<div class='paper-box-text' markdown="1">

[ST-WAM: Semantic-Temporal World Action Model for Robust Manipulation under Visual Distribution Shifts](https://arxiv.org/abs/2607.28993)

[**arXiv 2026**]
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="box-shadow:none !important; -webkit-box-shadow:none !important; background:transparent;">
<div style="box-shadow:none !important; -webkit-box-shadow:none !important; background:transparent;">
<img src='images/ADM-DP.png' alt="paper-image" width="100%" style="box-shadow:none !important; -webkit-box-shadow:none !important; border:none;">
</div></div>
<div class='paper-box-text' markdown="1">

[ADM-DP: Adaptive Dynamic Modality Diffusion Policy through Vision-Tactile-Graph Fusion for Multi-Agent Manipulation](https://arxiv.org/abs/2602.21622)

**Enyi Wang**, Wen Fan, Dandan Zhang

[**ICRA 2026**]
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="box-shadow:none !important; -webkit-box-shadow:none !important; background:transparent;">
<div style="box-shadow:none !important; -webkit-box-shadow:none !important; background:transparent;">
<img src='images/IROS_2025.png' alt="sym" width="100%" style="box-shadow:none !important; -webkit-box-shadow:none !important; border:none;">
</div></div>
<div class='paper-box-text' markdown="1">

[Estimating Continuum Robot Shape under External Loading using Spatiotemporal Neural Networks](https://arxiv.org/abs/2510.22339)

**Enyi Wang**, Zhen Deng*, Chuanchuan Pan, Bingwei He, Jianwei Zhang

[**IROS 2025**]
</div>
</div>

# 🎖 Honors and Awards
- *2023.07* Excellent trainee, Summer Camp of the Chinese University of Hong Kong, Shenzhen
- *2022-2023* 💰 Leader of a National-level Student Research Training Program (SRTP) team, funded with **¥20,000 RMB**.
- *2022.09 - 2023.09* Deputy Lead of Choir, Chorus of Fuzhou University
- *2023.03* H Award, MCM/ICM
- *2022 & 2024* Comprehensive Award Scholarship, Fuzhou University

# 📖 Educations
<div class="edu-item" style="display:flex; align-items:center; gap:16px; margin:18px 0;">
  <div style="width:240px; display:flex; align-items:center; justify-content:flex-start; margin-right:8px;">
    <img src='images/ic_logo.png' alt="Imperial College London" style="width:240px; max-width:100%; height:auto; margin-left:6px;">
  </div>
  <div>
    <div style="font-weight:600; font-size:1.05em;">Imperial College London (UK)</div>
    <div>MRes (Master of Research), 2024 - Currently</div>
    <div style="color:#666;">Supervisor: Prof. Dandan Zhang</div>
  </div>
  
</div>

<div class="edu-item" style="display:flex; align-items:center; gap:16px; margin:18px 0;">
  <div style="width:240px; display:flex; align-items:center; justify-content:center; margin-right:8px;">
    <img src='images/fzu_logo.png' alt="Fuzhou University" style="width:220px; max-width:100%; height:auto;">
  </div>
  <div>
    <div style="font-weight:600; font-size:1.05em;">Fuzhou University (China)</div>
    <div>B.Eng., 2020 - 2024</div>
    <div style="color:#666;">GPA：3.73/4.0</div>
    <div style="color:#666;">Supervisor: Prof. Zhen Deng</div>
  </div>
</div>

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
 - *2023.03 - 2023.06*, Shanghai Jiao Tong University × Drivedream Technology (industry–academia collaboration), Shanghai, China.<br>
   Collaborated to develop an industrial six-axis robotic-arm milling (CNC) system.
