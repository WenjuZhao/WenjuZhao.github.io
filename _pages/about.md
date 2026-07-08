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

Wenju Zhao (赵文举) is a fourth-year PhD candidate in the School of Computer Science and Technology at Huazhong University of Science and Technology, advised by <a href="http://faculty.hust.edu.cn/xfliao/zh_CN/index.htm" target="_blank">Prof. Xiaofei Liao</a>. He conducts his research within the Key Laboratory of Services Computing Technology and System, Ministry of Education (CGCL). Prior to his PhD, he received his bachelor's degree in Data Science and Big Data Technology from Wuhan University of Technology (2018–2022).

His research focuses on efficient AI acceleration, particularly on the co-design of algorithms and hardware for Large Language Models (LLMs) and Graph Neural Networks (GNNs). He also works on model compression techniques such as quantization and pruning, which complement his system-level designs by reducing computational and memory demands. Overall, his work aims to develop more efficient architectural support for modern AI inference workloads.


<span class="anchor" id="educations"></span>

# 📖 Education
- ***2026.08 – 2027.06:*** 
  Visiting Scholar, School of Computing, National University of Singapore; Supervised by <a href="https://www.comp.nus.edu.sg/~hebs/" target="_blank">Prof. Bingsheng He</a>; Working on machine learning acceleration.

- ***2022.06 – 2027.06:*** 
  PhD Candidate in Computer Science, Huazhong University of Science and Technology; Supervised by <a href="http://faculty.hust.edu.cn/xfliao/zh_CN/index.htm" target="_blank">Prof. Xiaofei Liao</a>; GPA: 3.77/4; Rank: 1/11

- ***2018.09 – 2022.06:***
  Bachelor of Engineering in Data Science and Big Data Technology, Wuhan University of Technology; GPA: 4.317/5; Rank: 1/33


<span class="anchor" id="publications"></span>

# 📝 Publications
- **[MICRO 2026] SkewQ: Skewness-Aware Cross-Layer Quantization for Efficient LLM Inference via Software-Hardware Co-Design**<br>
**<u>Wenju Zhao</u>**, Jianhui Yue, Pengcheng Yao, Jiaqi Zhai, Yundong Zhang, Yu Huang, Shunsen Lv, Bing Zhu, Zhongtian Long, Chencheng Ye, Lihong Gu, Jingling Xue, Hai Jin, Xiaofei Liao
<br>
*The International Symposium on Microarchitecture (CCF-A Conference, Top Tier Conference in Computer Architecture)*
- **[MICRO 2026] RAIL: A Reconfigurable Spatial Accelerator for Linear-Time Sequence Model Inference**<br>
Xinyu Zhu, Qinggang Wang, **<u>Wenju Zhao</u>**, Bing Zhu, Runze Wang, Long Zheng, Xiaofei Liao, Hai Jin, Jingling Xue
<br>
*The International Symposium on Microarchitecture (CCF-A Conference, Top Tier Conference in Computer Architecture)*
- **[ISCA 2026] ParetoES: Hardware-Accelerated Sparse Embedding Similarity via Pareto-Optimal Pruning**<br>
Jiaqi Zhai, Xuanhua Shi, **<u>Wenju Zhao</u>**, Kaiyi Huang, Chencheng Ye, Shunsen Lv, Zhongtian Long, Bingsheng He, Hai Jin
<br>
*The International Symposium on Computer Architecture (CCF-A Conference, Top Tier Conference in Computer Architecture)*
- **[DAC 2026] FuseDot: A Multiplication-Fused Dot Product Accelerator for Efficient LLM Inference**<br>
**<u>Wenju Zhao</u>**, Jianhui Yue, Pengcheng Yao, Yujia Cui, Qinggang Wang, Yufei Sun, Jiaqi Zhai, Hai Jin, Xiaofei Liao
<br>
*The Chips to Systems Conference (CCF-A Conference, Top Tier Conference in EDA)*
- **[SSI 2026] A High-Efficiency 3D-Stacked Accelerator for Deep Graph Neural Network Inference**<br>
Zhongtian Long, Yu Zhang, Yutao Fu, Qiyuan Niu, Shunsen Lv, Jiaqi Zhai, **<u>Wenju Zhao</u>**, Yingqi Zhao, Hai Jin<br>
*Scientia Sinica Informationis (CCF-T1 Journal)*
- **[HPCA 2025] MeHyper: Accelerating Hypergraph Neural Networks by Exploring Implicit Dataflows**<br>
**<u>Wenju Zhao</u>**, Pengcheng Yao, Dan Chen, Long Zheng, Xiaofei Liao, Qinggang Wang, Shaobo Ma, Yu Li, Haifeng Liu, Wenjing Xiao, Yufei Sun, Bing Zhu, Hai Jin, Jingling Xue<br>
*The International Symposium on High-Performance Computer Architecture (CCF-A Conference, Top Tier Conference in Computer Architecture)*
- **[TACO 2025] PRAGA: A Priority-Aware Hardware/Software Co-design for High-Throughput Graph Processing Acceleration**<br>
Long Zheng, Bing Zhu, Pengcheng Yao, Yuhang Zhou, Chengao Pan, **<u>Wenju Zhao</u>**, Xiaofei Liao, Hai Jin, and Jingling Xue<br>
*ACM Transactions on Architecture and Code Optimization (CCF-A Journal)*
- **[JCST 2024] Towards High-Performance Graph Processing: From a Hardware/Software Co-Design Perspective**<br>
**<u>Xiaofei Liao, Wenju Zhao</u>**, Hai Jin, Pengcheng Yao, Yu Huang, Qinggang Wang, Jin Zhao, Long Zheng, Yu Zhang, Zhiyuan Shao<br>
*Journal of Computer Science and Technology (CCF-B Journal, <span style="color:red">Cover Article</span>)*

<span class="anchor" id="honors-and-awards"></span>

# 🎖 Honors and Awards
- ***2024, 2020:*** National Scholarship, Ministry of Education, China
- ***2024:*** Science and Technology Innovation Scholarship, Huazhong University of Science and Technology
- ***2023, 2022:*** First Class Doctoral Scholarship, Huazhong University of Science and Technology
- ***2021:*** Outstanding Scholarship, Wuhan University of Technology (highest honor of the university, Top 0.1%)
- ***2021:*** Mathematical Contest in Modeling – Meritorious Winner
- ***2021:*** China Undergraduate Mathematical Contest in Modeling – Second Prize

<span class="anchor" id="academic-achievements"></span>

# ⭐ Academic Achievements
, 4th CS Academic Annual Conference, HUST
- ***2026.06:*** **Best Paper Award**, FuseDot: A Multiplication-Fused Dot Product Accelerator for Efficient LLM Inference. 4th CS Academic Annual Conference, HUST, China.
- ***2025.09:*** **Invited Talks**, MeHyper: Accelerating Hypergraph Neural Networks by Exploring Implicit Dataflows. Session 3: GPU and Domain Specific Accelerator Architectures, CCFSys 2025, Beijing, China.
- ***2024:*** **Cover Article**, Journal of Computer Science and Technology
(Work on high performance graph processing).
- ***2022:*** **Outstanding Undergraduate Thesis**, Parallel Optimization of Sparse Triangular Matrix Solution Based on Shared Memory, Wuhan University of Technology.

