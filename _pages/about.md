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

我是24届的在读博士生，就读于哈尔滨工业大学，机器人技术与系统国家重点实验室，导师为[丁亮](https://homepage.hit.edu.cn/liangding?lang=zh)教授。

主要研究方向为机器人强化学习，在足式机器人的机械设计与强化学习运动控制方面具有丰富的研究和工程经验。参与多项机器人领域工作，并担任 RA-L, T-ASE, IROS 等期刊会议审稿人。

# 📥 简历下载
[![下载个人简历](https://img.shields.io/badge/📄_下载个人简历-0056D2?style=for-the-badge&logo=adobeacrobatreader)]({{ site.url }}/assets/resume_zzl.pdf)

# 📖 教育经历
<span class='anchor' id='educations'></span>
- *2024.09 - 至今*, 哈尔滨工业大学, 航空宇航科学与技术, 学术型博士
- *2022.09 - 2024.06*, 哈尔滨工业大学, 航空宇航科学与技术, 学术型硕士, **获提前毕业资格，全学院仅20人**
- *2018.09 - 2022.06*, 哈尔滨工业大学, 机械设计制造及其自动化, 本科, **免试保送研究生**

# 📝 学术论文
<span class='anchor' id='publications'></span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2024, IROS 2025</div><img src='images/IERL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Imitation-Enhanced Reinforcement Learning With Privileged Smooth Transition for Hexapod Locomotion](https://ieeexplore.ieee.org/abstract/document/10752370)

**Zhelin Zhang**, Tie Liu, Liang Ding, Haoyu Wang, Peng Xu, Huaiguang Yang, Haibo Gao, Zongquan Deng, Joni Pajarinen

[**Video Material**](https://www.youtube.com/watch?v=8hiOxqW0Vog)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIE 2026</div><img src='images/LAA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Legs-as-Arms:A Multitask Reinforcement Learning Framework for Simultaneous Loco-Manipulation in Hexapod Robots](https://zzlin1.github.io/Legs_as_Arms.github.io/)

**Zhelin Zhang**, Liang Ding, Peng Xu*, Tie Liu, Ao Zhang, Huaiguang Yang, Haibo Gao, Zongquan Deng

[**Paper**](https://doi.org/10.1109/TIE.2026.3663691) 
[**Video Material**](https://youtu.be/la_98ikyGlQ)
[**Project Page**](https://zzlin1.github.io/Legs_as_Arms.github.io/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2025</div><img src='images/WBCL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Whole-Body Constrained Learning for Legged Locomotion via Hierarchical Optimization](https://www.arxiv.org/pdf/2506.05115)

Haoyu Wang, Ruyi Zhou, Liang Ding, Tie Liu, **Zhelin Zhang**, Peng Xu, Haibo Gao and Zongquan Deng

[**Project Page**](https://qrpucp.github.io/whole_body_constrained_learning/) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/PegasusFlow.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PegasusFlow: Parallel Rolling-Denoising Score Sampling for Robot Diffusion Planner Flow Matching](https://masteryip.github.io/pegasusflow.github.io/)

Lei Ye, Haibo Gao, Peng Xu, **Zhelin Zhang**, Junqi Shan, Ao Zhang, Wei Zhang, Ruyi Zhou, Zongquan Deng, Liang Ding

[**Paper**](https://arxiv.org/abs/2509.08435) 
[**Video Material**](https://www.youtube.com/watch?v=XMT02bo-Adc) 
[**Project Page**](https://masteryip.github.io/pegasusflow.github.io/)

</div>
</div>



- [A high mobility heavy duty hexapod robot for challenging field terrains, design, modeling, and experimental validation], Liang Ding, Yang Su, Peng Xu, Tie Liu, Haibo Gao, Huaiguang Yang, Ruyi Zhou, **Zhelin Zhang**, Haoyu Wang, Junqi Shan, Chongfu Xu and Zongquan Deng. **The International Journal of Robotics Research. (IJRR) (under review)**

# 🛠️ 项目经历
<span class='anchor' id='projects'></span>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">HIT</div><img src='images/hit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**哈尔滨工业大学“电动蜘蛛”**

负责实验室多台六足机器人（20kg、40kg和80kg量级）的高动态鲁棒强化学习运动控制，具备丰富的强化学习训练、RL运控算法以及Sim2Real经验。相关成果被哈尔滨工业大学各平台官方视频号发布宣传。

[**Bilibili**](https://www.bilibili.com/video/BV1obKVzaE6i/?spm_id_from=333.337.search-card.all.click&vd_source=5b426103b2291b2845953e669234f59b)
[**抖音**](https://www.douyin.com/video/7519426876566195506)
[**小红书**](http://xhslink.com/o/8NnW7omq6yw )

</div>
</div>


# 🎖️ 竞赛奖项
<span class='anchor' id='awards'></span>

- *2020.11*, 第十三届“高教杯”全国大学生先进成图大赛, 团体一等奖
- *2020.11*, 第十三届“高教杯”全国大学生先进成图大赛, 机械制图一等奖
- *2020.11*, 第十三届“高教杯”全国大学生先进成图大赛, 三维建模二等奖
- *2020.12*, 全国产品信息建模大赛, 二等奖
- *2022.06*, 哈尔滨工业大学优秀毕业生
- *2023.08*, “申昊杯”第五届中国研究生机器人创新设计大赛, 全国三等奖
- *2023.10*, “申昊杯”第六届中国研究生机器人创新设计大赛, 全国三等奖
