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
I'm a second-year M.sc. student at [SUSTech](https://www.sustech.edu.cn/en/), advised by [Prof. Hong Zhang](https://scholar.google.com/citations?user=J7UkpAIAAAAJ&hl=zh-CN&oi=ao).

I am a robotics perception researcher, dedicated to enabling robots to better perceive 3D environments, thereby improving their performance in downstream tasks such as scene understanding, navigation, and grasping. To achieve this goal, I am currently focused on: (a) SLAM; (b) differentiable dense map representations.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2025</div><img src='images/factor_graph.pdf' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Optimizing NeRF-based SLAM with Trajectory Smoothness Constraints](https://arxiv.org/pdf/2410.08780)

**Yicheng He**, Guangcheng Chen, Hong Zhang

- Identified the lack of trajectory smoothness in NeRF-SLAM due to missing explicit constraints.
- Proposed a B-spline trajectory representation and jointly optimized it with NeRF to achieve smooth camera motion.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/factor_graph.pdf' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pisr: Polarimetric neural implicit surface reconstruction for textureless and specular objects](https://arxiv.org/pdf/2409.14331))

Guangcheng Chen, **Yicheng He**, Li He & Hong Zhang

- Identified radiance-color ambiguity in NeRF methods, leading to poor reconstruction of textureless or reflective objects.
- Integrated polarization cues and a normal-based loss to enhance NeRF optimization and reconstruction quality.
</div>
</div>

# 🎖 Honors and Awards
- *2022.09* National Third Prize in the RoboMaster National University Students' Robotics Competition.
- *2021.09* National First Prize in the National University Students' Big Data Analysis and Mining Competition.

# 📖 Educations
- *2023.09 - 2026.06 (Expected)*, M.Sc., Southern University of Science and Technology. 
- *2019.09 - 2023.06*, B.Eng., Guangdong University of Technology. 

# 💻 Internships
- *2025.05 - 2025.08*, [Astribot](https://www.astribot.com/en), Shenzhen, China.
