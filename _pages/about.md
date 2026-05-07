---
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
<div style="background-color: #f0f7ff; padding: 25px; border-radius: 8px; border-left: 5px solid #005bac; margin-bottom: 30px;">
  <h1 style="margin-top: 0; color: #005bac;">About Me</h1>
  <p style="font-size: 16.5px; line-height: 1.7; margin-bottom: 0; color: #24292e;">
    Hello! I am a Ph.D. candidate at <a href="https://www.hust.edu.cn/" style="color: #005bac; font-weight: bold;">Huazhong University of Science and Technology (HUST)</a>, specialized in Optical Engineering. My research, co-advised by <a href="http://faculty.hust.edu.cn/ZhangCheng/zh_CN/index.htm" style="color: #005bac;">Prof. Cheng Zhang</a> and <a href="http://faculty.hust.edu.cn/LIUZEYANG/zh_CN/index.htm" style="color: #005bac;">Dr. Zeyang Liu</a>, focuses on metaphotonics and holographic displays.
    <br><br>
    Contact: <a href="mailto:zhiyuning@hust.edu.cn" style="color: #005bac;">zhiyuning@hust.edu.cn</a>
    <div style="margin-top: 15px;">
<a href="/assets/CV_Zhiyu_Ning.pdf" target="_blank" style="display: inline-block; padding: 8px 16px; background-color: #2b7bb9; color: white; text-decoration: none; border-radius: 4px; font-weight: bold; font-size: 14px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
    📄 Download Full CV
  </a>
</div>
  </p>
</div>

<span class='anchor' id='-news'></span>
# News
<div style="max-height: 250px; overflow-y: auto; border: 1px solid #e1e4e8; padding: 15px 20px; border-radius: 6px; background-color: #f6f8fa; font-size: 15px; margin-bottom: 30px; box-shadow: inset 0 1px 3px rgba(0,0,0,0.05);">
  <ul style="margin: 0; padding-left: 20px; line-height: 1.8;">
    <li><strong>2026.04:</strong> 🎉 <strong>Paper</strong> "Waveguide-based four-channel crosstalk-free metahologram multiplexed by diffraction orders" has been officially <strong>Published</strong> in an issue of <em>Nanophotonics</em>.</li>
    <li><strong>2026.03:</strong> 📝 <strong>Paper</strong> "Waveguide-based four-channel crosstalk-free metahologram multiplexed by diffraction orders" has been <strong>Accepted</strong> for publication.</li>
    <li><strong>2025.05:</strong> 🎤 <strong>Oral Presentation Accepted</strong> at 2025 China Optics Valley · Optoelectronics Undergraduate and Graduate Academic Exchange Conference.</li>
    <li><strong>2025.05:</strong> ⚡ <strong>Flash Report Accepted</strong> at the 4th AI Photonics Technology Symposium.</li>
    <li><strong>2024.07:</strong> 📊 <strong>Poster Presentation Accepted</strong> at the 5th Anniversary Academic Forum of Advanced Photonics and the 6th China Optics Valley (Wuhan) Laser Technology Young Researchers Forum.</li>
    <li><strong>2024.06:</strong> 🎓 I received my <strong>B.S. Degree</strong> from Huazhong University of Science and Technology.</li>
    <li><strong>2024.05:</strong> 🎤 <strong>Oral Presentation Accepted</strong> at 2024 China Optics Valley Optoelectronics Undergraduate Forum.</li>
  </ul>
</div>

<span class='anchor' id='-research-interests'></span>
# Research Interests
<div style="display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 30px;">
  <div style="flex: 1 1 250px; padding: 20px 25px; border-radius: 4px; background-color: #ffffff; border: 1px solid #eaecef; border-left: 4px solid #2b7bb9; box-shadow: 0 2px 8px rgba(0,0,0,0.03);">
    <h3 style="margin-top: 0; margin-bottom: 8px; font-size: 18px; color: #24292e;">Metaphotonics</h3>
    <p style="margin: 0; font-size: 15px; color: #586069; line-height: 1.6;">Metasurfaces, Meta-holography, and Light-field manipulation.</p>
  </div>
  
  <div style="flex: 1 1 250px; padding: 20px 25px; border-radius: 4px; background-color: #ffffff; border: 1px solid #eaecef; border-left: 4px solid #2b7bb9; box-shadow: 0 2px 8px rgba(0,0,0,0.03);">
    <h3 style="margin-top: 0; margin-bottom: 8px; font-size: 18px; color: #24292e;">Augmented Reality (AR)</h3>
    <p style="margin: 0; font-size: 15px; color: #586069; line-height: 1.6;">Waveguide-coupled systems, Full-color 3D displays.</p>
  </div>
</div>

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

<span class='anchor' id='-patents'></span>
# Patents
<ul style="margin: 0; padding-left: 20px; line-height: 1.8; font-size: 16px;">
  <li style="margin-bottom: 15px;">
    张诚, <strong>宁志宇</strong>, 刘泽阳, 郑德乾, 刘妞, 高豪, 
    <a href="https://patents.google.com/patent/CN120276228B/" target="_blank" style="color: #2b7bb9; text-decoration: none;">"一种超构全息器件及其设计方法和成像方法"</a>, 
     Patent No. CN120276228B, 2026. 
    <span style="display: inline-block; padding: 2px 8px; background-color: #e1f5fe; color: #0277bd; border-radius: 12px; font-size: 13px; font-weight: bold; margin-left: 5px;">Authorized</span>
  </li>
  <li style="margin-bottom: 10px;">
    张诚, 刘泽阳, 廖二宁, <strong>宁志宇</strong>, 
    <a href="https://patents.google.com/patent/CN120577961A/" target="_blank" style="color: #2b7bb9; text-decoration: none;">"一种基于高阶色散匹配的宽带消色差超构表面器件设计方法"</a>, Pub. No. CN120577961A, 2025. 
    <span style="display: inline-block; padding: 2px 8px; background-color: #fff8e1; color: #f57f17; border-radius: 12px; font-size: 13px; font-weight: bold; margin-left: 5px;">Under Review</span>
  </li>
</ul>

<span class='anchor' id='-honors-and-awards'></span>
# Honors and Awards
- *2025.05* &nbsp;🏆🏆 Third Prize for Oral Presentation, 2025 China Optics Valley · Optoelectronics Undergraduate and Graduate Academic Exchange Conference - Parallel Conference of the 20th OVC Expo (2025中国光谷·光电本科生论坛、光电研究生学术交流会 - 第二十届武汉光博会同期会议). 
- *2024.06* &nbsp;🏆🏆 Excellent Undergraduate Thesis of 2024 Graduates, Huazhong University of Science and Technology (HUST) (华中科技大学2024届本科生优秀毕业设计论文). 
- *2024.05* &nbsp;🏆🏆 Third Prize for Oral Presentation, 2024 China Optics Valley Optoelectronics Undergraduate Forum (2024中国光谷·光电子本科生论坛). 

<span class='anchor' id='-educations'></span>
# Education
- *2024.09 - Present*, Huazhong University of Science and Technology, Ph.D. Student
- *2020.09 - 2024.06*, Huazhong University of Science and Technology, B.S.

