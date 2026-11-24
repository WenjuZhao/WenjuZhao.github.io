---
permalink: /
title: "Wenju Zhao | PhD Candidate at HUST | AI & Computer Architecture"
description: "Wenju Zhao is a PhD candidate at HUST researching efficient AI acceleration, LLM inference, quantization, graph neural networks, and computer architecture."
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

# Wenju Zhao (赵文举)

Wenju Zhao (赵文举) is a PhD candidate in the School of Computer Science and Technology at Huazhong University of Science and Technology, advised by <a href="http://faculty.hust.edu.cn/xfliao/zh_CN/index.htm" target="_blank">Prof. Xiaofei Liao</a>. He conducts his research within the Key Laboratory of Services Computing Technology and System, Ministry of Education (CGCL). Prior to his PhD, he received his bachelor's degree in Data Science and Big Data Technology from Wuhan University of Technology (2018–2022).

His research focuses on efficient AI acceleration, particularly on the co-design of algorithms and hardware for Large Language Models (LLMs) and Graph Neural Networks (GNNs). He also works on model compression techniques such as quantization and pruning, which complement his system-level designs by reducing computational and memory demands. Overall, his work aims to develop more efficient architectural support for modern AI inference workloads.

<p style="color: #c62828;">I am seeking industry positions or postdoctoral opportunities in efficient AI inference, model compression, and computer architecture. Please feel free to contact me if you have suitable opportunities.</p>

<!-- <p>
  <a href="{{ '/append/CV_EN.pdf' | relative_url }}" download>Download CV (PDF)</a>
  &nbsp;|&nbsp;
  <a href="{{ '/append/Transcripts-WenjuZhao.pdf' | relative_url }}" download>Download Transcripts (PDF)</a>
</p> -->

<span class="anchor" id="educations"></span>

# 📖 Education

- ***2026.08 – present*** (visit expected to end in April 2027)<br>
  Visiting PhD student, School of Computing, National University of Singapore. Research on LLM inference acceleration and model compression with <a href="https://www.comp.nus.edu.sg/~hebs/">Prof. Bingsheng He</a>.

- ***2022.09 – present*** (expected graduation in June 2027)<br>
  PhD candidate in Computer Science, Huazhong University of Science and Technology. Advised by <a href="http://faculty.hust.edu.cn/xfliao/zh_CN/index.htm">Prof. Xiaofei Liao</a>. GPA 3.77/4 (ranked 1 of 11).

- ***2018.09 – 2022.06***<br>
  Bachelor of Engineering in Data Science and Big Data Technology, Wuhan University of Technology. GPA 4.317/5 (ranked 1 of 33).


<span class="anchor" id="publications"></span>

# 📝 Publications (**<u>first author</u>**, **<u>co-first author*</u>**, **<u>student first author<sup>#</sup></u>**)

- **[MICRO 2026] SkewQ: Skewness-Aware Cross-Layer Quantization for Efficient LLM Inference via Software-Hardware Co-Design**<br>
**<u>Wenju Zhao</u>**, Jianhui Yue, Pengcheng Yao, Jiaqi Zhai, Yundong Zhang, Yu Huang, Shunsen Lv, Bing Zhu, Zhongtian Long, Chencheng Ye, Lihong Gu, Jingling Xue, Hai Jin, and Xiaofei Liao<br>
*The International Symposium on Microarchitecture (CCF-A Conference, Top Tier Conference in Computer Architecture)*
- **[DAC 2026] FuseDot: A Multiplication-Fused Dot Product Accelerator for Efficient LLM Inference**<br>
**<u>Wenju Zhao</u>**, Jianhui Yue, Pengcheng Yao, Yujia Cui, Qinggang Wang, Yufei Sun, Jiaqi Zhai, Hai Jin, and Xiaofei Liao<br>
*The Chips to Systems Conference (CCF-A Conference, Top Tier Conference in EDA)*
- **[HPCA 2025] MeHyper: Accelerating Hypergraph Neural Networks by Exploring Implicit Dataflows**<br>
**<u>Wenju Zhao</u>**, Pengcheng Yao, Dan Chen, Long Zheng, Xiaofei Liao, Qinggang Wang, Shaobo Ma, Yu Li, Haifeng Liu, Wenjing Xiao, Yufei Sun, Bing Zhu, Hai Jin, and Jingling Xue<br>
*The International Symposium on High-Performance Computer Architecture (CCF-A Conference, Top Tier Conference in Computer Architecture)*
- **[TCAD 2026] HyperPIM: A Redundancy-Aware Heterogeneous PIM Accelerator for Hypergraph Neural Networks**<br>
**<u>Zhongtian Long*, Wenju Zhao*</u>**, Mo Zou, Hongrui Guo, Jin Zhao, Qiyuan Niu, Yutao Fu, Shunsen Lv, Zixiao Wang, Yuluo Guo, Yongwei Zhao, Yu Zhang, and Hai Jin<br>
*IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (CCF-A Journal)*
- **[JCST 2024] Towards High-Performance Graph Processing: From a Hardware/Software Co-Design Perspective**<br>
**<u>Xiaofei Liao, Wenju Zhao<sup>#</sup></u>**, Hai Jin, Pengcheng Yao, Yu Huang, Qinggang Wang, Jin Zhao, Long Zheng, Yu Zhang, and Zhiyuan Shao<br>
*Journal of Computer Science and Technology (CCF-B Journal, <span style="color:red">Cover Article</span>)*
- **[PPoPP 2027] EvoCG: Self-Evolving Precision Control for Faster Conjugate Gradient**<br>
Jiaqi Zhai, Haozhi Han, Kaiyi Huang, **Wenju Zhao**, Yifeng Chen, Yunquan Zhang, Ting Cao, Yunxin Liu, Hai Jin, Xuanhua Shi, and Kun Li<br>
*The ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming (CCF-A Conference, Top Tier Conference in Computer Systems)*
- **[TACO 2027] DeGCN: Accelerating Inference for Deep Graph Convolutional Networks by Exploiting Feature Similarity**<br>
Shunsen Lv, Jianhui Yue, Yu Zhang, Jiaqi Zhai, Jiangqiu Shen, Zhongtian Long, **Wenju Zhao**, Hai Jin, and Xiaofei Liao<br>
*ACM Transactions on Architecture and Code Optimization (CCF-A Journal)*
- **[arXiv 2026] ActTune: Action-Aware Precision and GPU Operating-Point Adaptation for Energy-Efficient Vision-Language-Action Inference**<br>
Zou Qingyun, Bin Gao, **Wenju Zhao**, Weng-Fai Wong, Bingsheng He, and Tulika Mitra<br>
*arXiv preprint* · [arXiv:2610.08444v1](https://arxiv.org/abs/2610.08444v1)
- **[arXiv 2026] From Splats to Silicon: Rethinking Computational Efficiency of 3DGS**<br>
Minnan Pei, Qiwei Dong, Yihan Zhou, Gang Li, Yuchen Zhu, **Wenju Zhao**, Zhongtian Long, Siting Wang, Peisong Wang, and Jian Cheng<br>
*arXiv preprint* · [arXiv:2609.06157](https://arxiv.org/abs/2609.06157)
- **[ICCD 2026] ReHyper: A Redundancy-Eliminated Accelerator for Dynamic Hypergraph Neural Networks**<br>
Zhongtian Long, Mo Zou, Qiyuan Niu, **Wenju Zhao**, Yutao Fu, Jiaqi Zhai, Shunsen Lv, Zixiao Wang, Yuluo Guo, Yuanyuan Liang, Hongrui Guo, Jin Zhao, and Yu Zhang<br>
*IEEE International Conference on Computer Design (CCF-B Conference)*
- **[TCAD 2026] SpecTwin: Accelerating Tree-based Speculative Decoding via Differential Token Quantization**<br>
Yufei Sun, Pengcheng Yao, Long Zheng, Yundong Zhang, Yu Huang, Qinggang Wang, Huize Li, **Wenju Zhao**, Bing Zhu, Haifeng Liu, Xiaofei Liao, and Hai Jin<br>
*IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (CCF-A Journal)*
- **[MICRO 2026] RAIL: A Reconfigurable Spatial Accelerator for Linear-Time Sequence Model Inference**<br>
Xinyu Zhu, Qinggang Wang, **Wenju Zhao**, Bing Zhu, Runze Wang, Long Zheng, Xiaofei Liao, Hai Jin, and Jingling Xue<br>
*The International Symposium on Microarchitecture (CCF-A Conference, Top Tier Conference in Computer Architecture)*
- **[ISCA 2026] ParetoES: Hardware-Accelerated Sparse Embedding Similarity via Pareto-Optimal Pruning**<br>
Jiaqi Zhai, Xuanhua Shi, **Wenju Zhao**, Kaiyi Huang, Chencheng Ye, Shunsen Lv, Zhongtian Long, Bingsheng He, and Hai Jin<br>
*The International Symposium on Computer Architecture (CCF-A Conference, Top Tier Conference in Computer Architecture)*
- **[SSI 2026] A High-Efficiency 3D-Stacked Accelerator for Deep Graph Neural Network Inference**<br>
Zhongtian Long, Yu Zhang, Yutao Fu, Qiyuan Niu, Shunsen Lv, Jiaqi Zhai, **Wenju Zhao**, Yingqi Zhao, and Hai Jin<br>
*Scientia Sinica Informationis (CCF-T1 Journal)*
- **[TACO 2025] PRAGA: A Priority-Aware Hardware/Software Co-design for High-Throughput Graph Processing Acceleration**<br>
Long Zheng, Bing Zhu, Pengcheng Yao, Yuhang Zhou, Chengao Pan, **Wenju Zhao**, Xiaofei Liao, Hai Jin, and Jingling Xue<br>
*ACM Transactions on Architecture and Code Optimization (CCF-A Journal)*

## Manuscripts under review

- **MetaKV: Metadata-Aware KV-Cache Quantization for Efficient Long-Context LLM Inference via Software-Hardware Co-Design**<br>
  **<u>Wenju Zhao</u>**, Bowen Rao, Pengcheng Yao, Jianhui Yue, Shunsen Lv, Zhongtian Long, Jiaqi Zhai, Nanxun Wu, Zhen Zeng, Yu Huang, Bingsheng He, Jingling Xue, Hai Jin, and Xiaofei Liao
- **AdaVLA: A Spatiotemporally Adaptive Chiplet Architecture for Asynchronous Vision-Language-Action Inference**<br>
  **<u>Wenju Zhao</u>**, Bowen Rao, Pengcheng Yao, Chunlin Tian, Qingyun Zou, Mingjia Fan, Shihong Xi, Yongzhi Qian, Bingsheng He, and Xiaofei Liao

<span class="anchor" id="academic-achievements"></span>

# ⭐ Academic Achievements
- ***2026.06:*** **Best Paper Award**, FuseDot: A Multiplication-Fused Dot Product Accelerator for Efficient LLM Inference. 4th CS Academic Annual Conference, HUST, China.
- ***2025.09:*** **Invited Talks**, MeHyper: Accelerating Hypergraph Neural Networks by Exploring Implicit Dataflows. Session 3: GPU and Domain Specific Accelerator Architectures, CCFSys 2025, Beijing, China.
- ***2024:*** **Cover Article**, Journal of Computer Science and Technology
(Work on high performance graph processing).
- ***2022:*** **Outstanding Undergraduate Thesis**, Parallel Optimization of Sparse Triangular Matrix Solution Based on Shared Memory, Wuhan University of Technology.

<span class="anchor" id="honors-and-awards"></span>

# 🎖 Honors and Services

- ***2026.10:*** MICRO 2026 Travel Grant
- ***2026.04:*** Member, ISCA 2026 Artifact Evaluation Committee
- ***2026, 2024, 2020:*** National Scholarship, Ministry of Education, China
- ***2024:*** Science and Technology Innovation Scholarship, Huazhong University of Science and Technology
- ***2023, 2022:*** First Class Doctoral Scholarship, Huazhong University of Science and Technology
- ***2021:*** Outstanding Scholarship, Wuhan University of Technology (highest honor of the university, Top 0.1%)
- ***2021:*** Mathematical Contest in Modeling – Meritorious Winner
- ***2020.11:*** China Undergraduate Mathematical Contest in Modeling – Second Prize
