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

📚 Yilun Wang is currently a 1st-year CSE Ph.D. student at [The Chinese University of Hong Kong](https://www.cse.cuhk.edu.hk/), advised by [Prof. Michael R. Lyu](https://www.cse.cuhk.edu.hk/lyu/). Previously, he recieved Master degree from [AHU](https://en.ahu.edu.cn/)-[SYSU](https://www.sysu.edu.cn/sysuen/) joint program under the guidance of [Prof. Pengfei Chen](https://cse.sysu.edu.cn/teacher/ChenPengfei) and Prof. Hui Dou.

💡 His research interest lies in (1)Performance optimization for cloud and LLM systems; (2)LLM4SE


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 Our DRR was accepted by <span style="color:Red ;">SoCC'25</span>.
- *2025.06*: &nbsp;🎉🎉 Our InferLog was accepted without revision by <span style="color:Red ;">ICSE'26</span> with an acceptance rate of 9% (60/660).
- *2025.05*: &nbsp;🎉🎉 Our LLMConf was accepted by <span style="color:Red ;">IWQOS'25</span>.
- *2024.10*: &nbsp;🎉🎉 Our Mint was accepted by <span style="color:Red ;">ASPLOS'25</span>.[[News](https://mp.weixin.qq.com/s/xJs3I9jyX-xkuUpRu7_NWg)]
- *2024.09*: &nbsp;🎉🎉 Our LLM-based ECS metrics prediction solutions won excellent award🏆 in the 2024 [TIANCHI Cloud Native Programming Challenge](https://tianchi.aliyun.com/competition/entrance/532202) (Bonus 5000¥).[[News](https://developer.aliyun.com/article/1611031?spm=5176.26934562.main.1.507e1506evW7ia)]
- *2024.09*: &nbsp;🎉🎉 Our DeepCAT+ was accepted by <span style="color:Red ;">TPDS</span>.
- *2024.08*: &nbsp;🎉🎉 Our FaaSConf was accepted by <span style="color:Red ;">ASE'24</span>.
- *2024.07*: &nbsp;🎉🎉 Our FaaSRCA was accepted by <span style="color:Red ;">ISSRE'24</span>.
- *2022.06*: &nbsp;🎉🎉 Our DeepCAT was accepted by <span style="color:Red ;">ICPP'22</span> and was presented at <span style="color:Red;">ACM TURC'2023 & ChinaSys</span>.[[News](https://zhuanlan.zhihu.com/p/650016166)]


# 📝 Publications 
  
- &nbsp; <span class="badge" style="font-size:16px;">ICSE '26 (CCF A)</span> &nbsp;**InferLog: Accelerating LLM Inference for Online Log Parsing via ICL-oriented Prefix Caching**

  <span style="font-size:14px;"> <strong style="color:#DE3163">Yilun Wang</strong>, Pengfei Chen*, Haiyu Huang, Zilong He, Gou Tan, Chuanfu Zhang, Jingkai He and Zibin Zheng. </span>

  <span style="font-size:14px;"> *The 48th IEEE/ACM International Conference on Software Engineering, Rio de Janeiro, Brazil, April 2026.* </span>[[Paper](https://arxiv.org/abs/2507.08523)][[Code](https://github.com/wiluen/InferLog)]
  
  
- &nbsp; <span class="badge" style="font-size:16px;">ASPLOS '25 (CCF A)</span> &nbsp;**Mint: Cost-Efficient Tracing with All Requests Collection via Commonality and Variability Analysis**

  <span style="font-size:14px;"> Haiyu Huang, Cheng Chen, Kunyi Chen, Pengfei Chen*, Guangba Yu, Zilong He, <strong style="color:#DE3163">Yilun Wang</strong>, Huxing Zhang and Qi Zhou. </span>

  <span style="font-size:14px;"> *The ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Rotterdam, the Netherlands, March-April 2025.* </span>[[Paper](https://doi.org/10.1145/3669940.3707287)]
  

- &nbsp; <span class="badge" style="font-size:16px;">SoCC '25 (CCF B)</span> &nbsp;**Defragmentation Scheduling with Deep Reinforcement Learning in Shared GPU Clusters**

  <span style="font-size:14px;"> Qingfu Wu, Pengfei Chen*, <strong style="color:#DE3163">Yilun Wang</strong>.

  <span style="font-size:14px;"> *The 16th ACM Symposium on Cloud Computing, Virtual event, November 2025.* </span>
  

- &nbsp; <span class="badge" style="font-size:16px;">ASE '24 (CCF A)</span> &nbsp;**FaaSConf: QoS-aware Hybrid Resources Configuration for Serverless Workflows**

  <span style="font-size:14px;"> <strong style="color:#DE3163">Yilun Wang</strong>, Pengfei Chen, Hui Dou*, Guangba Yu, Zilong He and Haiyu Huang. </span>

  <span style="font-size:14px;"> *The 39th IEEE/ACM International Conference on Automated Software Engineering, California, United States, October 2024.* </span>[[Paper](https://github.com/wiluen/wiluen.github.io/blob/main/files/faasconf/faasconf_camera_ready.pdf)][[Code](https://github.com/wiluen/FaaSConf)]

  
- &nbsp; <span class="badge" style="font-size:16px;">TPDS '24 (CCF A)</span> &nbsp;**DeepCAT+: A Low-Cost and Transferrable Online Configuration Auto-Tuning Approach for Big Data Framework**

  <span style="font-size:14px;"> Hui Dou, <strong style="color:#DE3163">Yilun Wang(1st student author)</strong>, Yiwen Zhang*, Pengfei Chen, Zibin Zheng. </span>

  <span style="font-size:14px;"> *IEEE Transactions on Parallel and Distributed Systems.* </span>[[Paper](https://doi.org/10.1109/TPDS.2024.3459889)][[Code](https://github.com/wiluen/DeepCAT)]

  

- &nbsp; <span class="badge" style="font-size:16px;">IWQOS '25 (CCF B)</span> &nbsp;**LLMConf: Knowledge-Enhanced Configuration Optimization for Large Language Model Inference**

  <span style="font-size:14px;"> Jingkai He, Pengfei Chen*, <strong style="color:#DE3163">Yilun Wang</strong>, Haiyu Huang, Chuanfu Zhang, Haojia Huang, Danwen Chen. </span>

  <span style="font-size:14px;"> *IEEE/ACM International Symposium on Quality of Service, Gold Coast, Australia, July 2025.* </span> [[Code](https://github.com/IntelligentDDS/LLMConf)]


- &nbsp; <span class="badge" style="font-size:16px;">ISSRE '24 (CCF B)</span> &nbsp;**FaaSRCA: Full Lifecycle Root Cause Analysis for Serverless Applications**

  <span style="font-size:14px;"> Jin Huang, Pengfei Chen*, Guangba Yu, <strong style="color:#DE3163">Yilun Wang</strong>, Haiyu Huang and Zilong He. </span>

  <span style="font-size:14px;"> *The 35th International Symposium on Software Reliability Engineering, Tsukuba, Japan, October 2024.* </span>[[Paper](https://arxiv.org/abs/2412.02239)]

- &nbsp; <span class="badge" style="font-size:16px;">ICPP '22 (CCF B)</span> &nbsp;**DeepCAT: A Cost-Efficient Online Configuration Auto-Tuning Approach for Big Data Frameworks**

  <span style="font-size:14px;"> Hui Dou, <strong style="color:#DE3163">Yilun Wang(1st student author)</strong>, Yiwen Zhang*, Pengfei Chen. </span>

  <span style="font-size:14px;"> *The 51st International Conference on Parallel Processing, Bordeaux, France, August 2022.* </span>[[Paper](https://github.com/wiluen/wiluen.github.io/blob/main/files/deepcat/22ICPP.pdf)][[Code](https://github.com/wiluen/DeepCAT)]

# 💻 Internships
 <!-- ![Huawei Logo](https://wiluen.github.io/images/Huawei.png){:width="30" height="30"} *2025.07 - Now*, Intern, Huawei Cloud, Shenzhen, China -->

  ![Ant Logo](https://wiluen.github.io/images/Ant.png){:width="30" height="30"} *2023.12 - 2024.08*, Intern, Ant Group, Beijing, China


# 🎖 Honors and Awards
- *2024.09* Excellent Award, Alibaba Cloud TIANCHI Cloud Native Programming Challenge **(As Team Leader)**
- *2024.06* Outstanding Master's Graduates
- *2022.10* National Scholarship, Ministry of Education of the P.R. China
- *2022.09* Outstanding Graduate Student Model and First Prize Scholarship
- *2020.08* 2nd Prize at the National Level, The 13th Chinese Collegiate Computing Competition(4C) **(As Team Leader)**

# 📖 Teaching
- Teaching Assistant of ENGG1110, Problem Solving by Programming (2025-2026 Term 1)
<!-- # # 📖 Educations-->
<!-- # - *2023.03-2025.06*, Research Assistant, Sun Yat-Sen University -->
<!-- # - *2021.09-2024.06*, Master of Engineering degree, Anhui University -->
<!-- # - *2017.09-2021.06*, Bachelor degree -->
 



