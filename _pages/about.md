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
I'm a second-year M.Sc. student at [SUSTech](https://www.sustech.edu.cn/en/), advised by [Prof. Hong Zhang](https://scholar.google.com/citations?user=J7UkpAIAAAAJ&hl=zh-CN&oi=ao).

I am a robotics perception researcher, dedicated to enabling robots to better perceive 3D environments, thereby improving their performance in downstream tasks such as scene understanding, navigation, and grasping. To achieve this goal, I am currently focused on: (a) SLAM; (b) differentiable dense map representations.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2025</div><img src='images/ts-slam.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Optimizing NeRF-based SLAM with Trajectory Smoothness Constraints](https://arxiv.org/pdf/2410.08780)

**Yicheng He**, Guangcheng Chen, Hong Zhang

- Identified the lack of trajectory smoothness in NeRF-SLAM due to missing explicit constraints.
- Proposed a B-spline trajectory representation and jointly optimized it with NeRF to achieve smooth camera motion.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/pisa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pisr: Polarimetric neural implicit surface reconstruction for textureless and specular objects](https://arxiv.org/pdf/2409.14331)

Guangcheng Chen, **Yicheng He**, Li He, Hong Zhang

- Identified radiance-color ambiguity in NeRF methods, leading to poor reconstruction of textureless or reflective objects.
- Integrated polarization cues and a normal-based loss to enhance NeRF optimization and reconstruction quality.
</div>
</div>

# 🎖 Honors and Awards

<div style="display: flex; align-items: center; margin-bottom: 1.5em;">
  <!-- 左侧视频 -->
  <div style="flex: 0 0 auto;">
    <video width="320" height="180" controls autoplay loop muted>
      <source src="images/rm.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <!-- 右侧文字 -->
  <div style="flex: 1; padding-left: 20px;">
    <p style="margin: 0;">
      <b>- <i>2021.09 – 2023.09</i></b><br>
      National Second/Third Prize in the <b>RoboMaster</b> National University Students' Robotics Competition.
    </p>
  </div>
</div>

- *2021.09 - 2023.09* National Second/Third Prize in the **RoboMaster** National University Students' Robotics Competition.
  <div align="center">
  <video width="320" height="180" controls autoplay loop muted>
    <source src="images/rm.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>


# 📖 Educations
- *2023.09 - 2026.06 (Expected)*, M.Sc., Southern University of Science and Technology. 
- *2019.09 - 2023.06*, B.Eng., Guangdong University of Technology. 

# 💻 Internships
- *2025.05 - 2025.08*, [Astribot](https://www.astribot.com/en), Shenzhen, China.
