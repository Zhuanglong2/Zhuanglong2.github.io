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

## 😄 About Me

I am currently a second-year Ph.D. student at Southeast University, supervised by Associate Professor <font color="#9b008b">Yiqing Yao</font>.

My research focuses on millimeter-wave radar-based environmental perception and localization for autonomous driving in complex environments, with an emphasis on deep learning and multi-sensor fusion. <a href="https://scholar.google.com/citations?user=uzRvavcAAAAJ">
  <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a>


## 🔥 News

- **2026-03-21**: 🎉 Our paper <font color="#9b008b">RCPRNet</font> has been <font color="#9b008b">Accpet</font> in <font color="#9b008b">TIE</font>.
- **2026-03-19**: 🎉 Our paper <a href="https://ieeexplore.ieee.org/document/11432979" style="color: #9b008b; text-decoration: none;">RCOC-Distill</a> is published in <font color="#9b008b">TMM</font>. [[Paper]](https://ieeexplore.ieee.org/document/11432979) [[Code]](https://github.com/Zhuanglong2/RCOC-Distill)
- **2025-12-15**: Selected for the <font color="#9b008b">2025 Special Program for Doctoral Students</font> under the <font color="#9b008b">CSCS Young Science and Technology Talent Cultivation Project</font>.
- **2025-10-27**: Received a verbal offer from an overseas supervisor and will apply for the <font color="#9b008b">CSC Scholarship</font>. Planned <font color="#9b008b">one-year joint Ph.D. training abroad</font> (Sep. 2026 – Aug. 2027).

# 📝 Publications 
🔹 **<u>Long Zhuang</u>**, Yiqing Yao\*, and Tao Zhang.  
*RCPRNet: Robust 4D Radar-Camera Place Recognition.* 
<i>IEEE Transactions on Industrial Electronics</i>, 2026.  

---

🔹 **<u>Long Zhuang</u>**, Yiqing Yao\*, and Tao Zhang.  
*RCOC-Distill: Boosting 4D Radar-Camera Online Calibration with Knowledge Distillation from LiDAR Features.*[[Paper]](https://ieeexplore.ieee.org/document/11432979) [[Code]](https://github.com/Zhuanglong2/RCOC-Distill)  
<i>IEEE Transactions on Multimedia</i>, 2026.  

---

🔹 **<u>Long Zhuang</u>**, Yiqing Yao\*, and Nuo Li.  
*RC-ROSNet: Fusing 3D Radar Range-Angle Heat Maps and Camera Images for Radar Object Segmentation.*[[Paper]](https://ieeexplore.ieee.org/document/11112643) [[Code]](https://github.com/Zhuanglong2/RC-ROSNet)  
<i>IEEE Transactions on Circuits and Systems for Video Technology</i>, 2026.  

---

🔹 **<u>Long Zhuang</u>**, Tiezhen Jiang\*, Hao Jiang, Anqi Wang, and Zhixiang Huang.  
*LQCANet: Learnable-Query-Guided Multi-Scale Fusion Network Based on Cross-Attention for Radar Semantic Segmentation.*[[Paper]](https://ieeexplore.ieee.org/document/10356738)  
<i>IEEE Transactions on Intelligent Vehicles</i>, 2024.  

---

🔹 **<u>Long Zhuang</u>**, Kai Luo, and Zhibo Yang\*.  
*A Multimodal Gated Recurrent Unit Neural Network Model for Damage Assessment in CFRP Composites Based on Lamb Waves and Minimal Sensing.*<span style="color:#B19CD9;">⭐ (ESI Highly Cited Paper)</span> [[Paper]](https://ieeexplore.ieee.org/document/10379118)  
<i>IEEE Transactions on Instrumentation and Measurement</i>, 2024.  
 
---

🔹 **<u>Long Zhuang</u>**, Yiqing Yao\*, Nuo Li, Zijian Wang, Lingtong Zhong, Zijing Zhang, and Tao Zhang.  
*4DRC-OC: Online Calibration of 4D Millimeter Wave Radar-Camera With Depth Map Assistance.*[[Paper]](https://ieeexplore.ieee.org/document/10950073) [[Code]](https://github.com/Zhuanglong2/4DRC-OC)  
<i>IEEE Robotics and Automation Letters</i>, 2025.  

---

🔹 **<u>Long Zhuang</u>**, Yiqing Yao\*, Taihong Yang, Zijian Wang, and Tao Zhang.  
*Boosting FMCW Radar Heat Map Object Detection with Raw ADC Data.*[[Paper]](https://ieeexplore.ieee.org/document/11192687) [[Code]](https://github.com/Zhuanglong2/Mamba-RODNet)  
<i>IEEE Robotics and Automation Letters</i>, 2025.  

---

🔹 **<u>Long Zhuang</u>**, Tiezhen Jiang\*, Meng Qiu, Anqi Wang, and Zhixiang Huang.  
*Transformer Generates Conditional Convolution Kernels for End-to-End Lane Detection.*[[Paper]](https://ieeexplore.ieee.org/document/10608068) [[Code]](https://github.com/Zhuanglong2/Condformer)  
<i>IEEE Sensors Journal</i>, 2024.  

---

🔹 **<u>Long Zhuang</u>**, Tiezhen Jiang\*, Jianhua Wang, Qi An, Kai Xiao, and Anqi Wang.  
*Effective mmWave Radar Object Detection Pretraining Based on Masked Image Modeling.*[[Paper]](https://ieeexplore.ieee.org/document/10353950)  
<i>IEEE Sensors Journal</i>, 2024.  

---

🔹 Tiezhen Jiang, **<u>Long Zhuang*</u>**, Qi An, Jianhua Wang, Kai Xiao, and Anqi Wang.  
*T-RODNet: Transformer for Vehicular Millimeter-Wave Radar Object Detection.*[[Paper]](https://ieeexplore.ieee.org/document/9989400) [[Code]](https://github.com/Zhuanglong2/T-RODNet)    
<i>IEEE Transactions on Instrumentation and Measurement</i>, 2023.  

---

🔹 Tiezhen Jiang, Qingzhu Li, Zhixiang Huang, and **<u>Long Zhuang*</u>**, et al.  
*CT-RURnet: a novel network design for radar unmanned aerial vehicles recognition.*[[Paper]](https://iopscience.iop.org/article/10.1088/1361-6501/ada1ef)  
<i>Measurement Science and Technology</i>, 2024.  

---

🔹 Tiezhen Jiang, **<u>Long Zhuang*</u>**, Jianhua Wang, Qi An.  
*Design of dual-band filtering patch antenna slot coupling feed.*[[Paper]](https://www.cambridge.org/core/journals/international-journal-of-microwave-and-wireless-technologies/article/abs/design-of-dualband-filtering-patch-antenna-slot-coupling-feed/9588005D36E787CF1AEB3C0F640AEACD)  
<i>International Journal of Microwave and Wireless Technologies</i>, 2024.  


# 📖 Educations
- *2024.09 - present*, Ph.D. candidate at Southeast University, Nanjing, China. Doctoral Advisor: Yiqing Yao
- *2021.09 - 2024.06*, M.S. at Anhui University, Hefei, China. Master's Advisor: Tiezhen Jiang


# 🤝 Collaborators
- [Lianqing Zheng](https://zhenglianqing.github.io/#-Short%20Bio), Ph.D. candidate in the School of Automotive Studies, Tongji University, Shanghai.
- [Kai Luo](https://scholar.google.com.hk/citations?hl=en&user=ZK6p4eEAAAAJ), Ph.D. candidate in the School of Automation and Intelligent Manufacturing (AIM), Southern University of Science and Technology, Shenzhen, P. R. China.
- Yuan Fang, Ph.D. candidate in the Urban wireless sensing lab, Department of Security and Crime Science, University College London, United Kingdom.
- Wenkai Zhu, [Zihang Wang](https://wangzihanggg.github.io/), Ph.D. candidate in Southeast University.
