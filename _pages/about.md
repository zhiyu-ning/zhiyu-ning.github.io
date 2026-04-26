<img width="1362" height="481" alt="image" src="https://github.com/user-attachments/assets/7f723f9e-3939-4284-8e63-ed8bbef93b47" />---
permalink: /
title: "Zhiyu Ning's Homepage"
excerpt: /
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

<span class='anchor' id='-about-me'></span>
# About Me
Hello! I am a Ph.D. candidate at [Huazhong University of Science and Technology (HUST)](https://www.hust.edu.cn/), specialized in Optical Engineering. My research, co-advised  by [Prof. Cheng Zhang](http://faculty.hust.edu.cn/ZhangCheng/zh_CN/index.htm) and [Dr. Zeyang Liu](http://faculty.hust.edu.cn/LIUZEYANG/zh_CN/index.htm), focuses on metaphotonics and holographic displays.  
Contact: [zhiyuning@hust.edu.cn](zhiyuning@hust.edu.cn).

<span class='anchor' id='-news'></span>
# News
<div style="max-height: 250px; overflow-y: auto; border: 1px solid #e1e4e8; padding: 15px 20px; border-radius: 6px; background-color: #f6f8fa; font-size: 15px; margin-bottom: 30px; box-shadow: inset 0 1px 3px rgba(0,0,0,0.05);">
  <ul style="margin: 0; padding-left: 20px; line-height: 1.8;">
    <li><strong>2026.04:</strong> 🎉 "Waveguide-based four-channel crosstalk-free metahologram..." has been officially published in an issue of <em>Nanophotonics</em>.</li>
    <li><strong>2026.03:</strong> 📝 "Waveguide-based four-channel crosstalk-free metahologram..." has been accepted for publication.</li>
    <li><strong>2025.05:</strong> 🎤 Oral Presentation Accepted at 2025 China Optics Valley Exchange Conference.</li>
    <li><strong>2025.05:</strong> ⚡ Flash Report Accepted at the 4th AI Photonics Technology Symposium.</li>
    <li><strong>2024.07:</strong> 📊 Poster Presentation Accepted at the 5th Anniversary Academic Forum of Advanced Photonics.</li>
    <li><strong>2024.06:</strong> 🎓 I received my B.S. degree from Huazhong University of Science and Technology.</li>
  </ul>
</div>

- *2026.04*: &nbsp;🎉🎉 "**[Waveguide-based four-channel crosstalk-free metahologram multiplexed by diffraction orders](https://doi.org/10.1002/nap2.70078)**" has been officially published in an issue of *Nanophotonics*.
- *2026.03*: &nbsp;🎉🎉 "**Waveguide-based four-channel crosstalk-free metahologram multiplexed by diffraction orders**" has been accepted for publication in *Nanophotonics*.
- *2025.05*: &nbsp;🎉🎉 Oral Presentation Accepted at [2025 China Optics Valley · Optoelectronics Undergraduate and Graduate Academic Exchange Conference - Parallel Conference of the 20th OVC Expo](https://cn.ovcexpo.com.cn/content.html?id=Expo_Axj_N2IzYjNkM2JhYmM3Y2I3Yjk0NTcyNzkyM2Y0ZGY2ZWQ=).
- *2025.05*: &nbsp;🎉🎉 Flash Report Accepted at [the 4th AI Photonics Technology Symposium](https://cn.ovcexpo.com.cn/content.html?id=Expo_Axj_ZTJiYjA2ZmFiNGMyMGNkOGM1OTJlODkyMjJkMzc3ZGI=).
- *2024.07*: &nbsp;🎉🎉 Poster Presentation Accepted at [the 5th Anniversary Academic Forum of Advanced Photonics and the 6th China Optics Valley (Wuhan) Laser Technology Young Researchers Forum](https://www.opticsjournal.net/cl/apwh.html). 
- *2024.06*: &nbsp;🎉🎉 I received my B.S. degree from Huazhong University of Science and Technology.
- *2024.05*: &nbsp;🎉🎉 Oral Presentation Accepted at [2024 China Optics Valley Optoelectronics Undergraduate Forum](https://oei.hust.edu.cn/info/1091/8844.htm).

<span class='anchor' id='-research-interests'></span>
# Research Interests
- **Metaphotonics**: Metasurfaces, Meta-holography, and Light-field manipulation.
- **Augmented Reality (AR)**: Waveguide-coupled systems, Full-color 3D displays.

<span class='anchor' id='-publications'></span>
# Publications 
<style>
  /* 基础容器样式 */
  .pub-row {
    display: flex;
    flex-wrap: wrap;
    align-items: center; /* PC端垂直居中 */
    justify-content: center;
    gap: 30px;
    margin-bottom: 40px;
    width: 100%;
  }

  /* 图片容器样式 */
  .pub-image {
    flex: 0 0 260px; /* PC端固定基础宽度 */
    max-width: 280px;
    text-align: center;
  }

  .pub-image img {
    width: 100%;
    border-radius: 6px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    display: block;
  }

  /* 文字容器样式 */
  .pub-text {
    flex: 1 1 350px;
    font-size: 16px;
    line-height: 1.7;
    text-align: left;
  }

  /* 📱 手机端适配逻辑 */
  @media (max-width: 768px) {
    .pub-row {
      gap: 15px; /* 缩小间距 */
    }
    .pub-image {
      flex: 0 0 100%; /* 图片容器强制占满 100% 宽度 */
      max-width: 100%;
      order: 1; /* 确保图片在上 */
    }
    .pub-text {
      flex: 0 0 100%;
      order: 2; /* 确保文字在下 */
      text-align: left; /* 手机端文字通常建议左对齐或两端对齐 */
    }
  }
</style>

<div class="pub-row">
  <div class="pub-image">
    <img src="/images/Nanophotonics_2026.jpg" alt="Waveguide Metahologram">
  </div>
  <div class="pub-text">
    <strong>Zhiyu Ning</strong>†, Zeyang Liu†*, Deqian Zheng, Niu Liu, Hao Gao, Tianzhang Peng, Ziqian Xi, Xinliang Zhang, Cheng Zhang*, 
    <a href="https://doi.org/10.1002/nap2.70078" style="text-decoration: underline; color: #2b7bb9;">
      "Waveguide-based four-channel crosstalk-free metahologram multiplexed by diffraction orders"
    </a>, 
    <strong style="color: #e6a200;"><em>Nanophotonics</em></strong>, e70078 (2026).
  </div>
</div>

<span class='anchor' id='-honors-and-awards'></span>
# Honors and Awards
- *2025.05* &nbsp;🏆🏆 Third Prize for Oral Presentation, 2025 China Optics Valley · Optoelectronics Undergraduate and Graduate Academic Exchange Conference - Parallel Conference of the 20th OVC Expo (2025中国光谷·光电本科生论坛、光电研究生学术交流会 - 第二十届武汉光博会同期会议). 
- *2024.06* &nbsp;🏆🏆 Excellent Undergraduate Thesis of 2024 Graduates, Huazhong University of Science and Technology (HUST) (华中科技大学2024届本科生优秀毕业设计论文). 
- *2024.05* &nbsp;🏆🏆 Third Prize for Oral Presentation, 2024 China Optics Valley Optoelectronics Undergraduate Forum (2024中国光谷·光电子本科生论坛). 

<span class='anchor' id='-educations'></span>
# Education
- *2024.09 - Present*, Huazhong University of Science and Technology, Ph.D. Student
- *2020.09 - 2024.06*, Huazhong University of Science and Technology, B.S.

