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

📚 Yilun Wang is currently a RA at [Sun Yat-Sen University](https://sysu.edu.cn/), advised by Professor [Pengfei Chen](https://cse.sysu.edu.cn/teacher/ChenPengfei). Previously, he received a M.Eng from [Anhui University](https://www.ahu.edu.cn/) in 2024. He has interned at [Ant Group](https://www.antgroup.com/) in Cloud Platform Performance Management related departments, developing algorithms and solving real-world problems.

💡 His research interest lies in performance optimization for cloud and LLM systems(e.g., configuration, resource, workload management and scheduling). 


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Our InferLog was accepted without revision by <span style="color:Red ;">ICSE'26</span>.
- *2025.05*: &nbsp;🎉🎉 Our LLMConf was accepted by <span style="color:Red ;">IWQOS'25</span>.
- *2024.10*: &nbsp;🎉🎉 Our Mint was accepted by <span style="color:Red ;">ASPLOS'25</span>.[[News](https://mp.weixin.qq.com/s/xJs3I9jyX-xkuUpRu7_NWg)]
- *2024.09*: &nbsp;🎉🎉 Our LLM-based ECS metrics prediction solutions won excellent award🏆 in the 2024 [TIANCHI Cloud Native Programming Challenge](https://tianchi.aliyun.com/competition/entrance/532202) (Bonus 5000¥).[[News](https://developer.aliyun.com/article/1611031?spm=5176.26934562.main.1.507e1506evW7ia)]
- *2024.09*: &nbsp;🎉🎉 Our DeepCAT+ was accepted by <span style="color:Red ;">TPDS</span>.
- *2024.08*: &nbsp;🎉🎉 Our FaaSConf was accepted by <span style="color:Red ;">ASE'24</span>.
- *2024.07*: &nbsp;🎉🎉 Our FaaSRCA was accepted by <span style="color:Red ;">ISSRE'24</span>.
- *2022.06*: &nbsp;🎉🎉 Our DeepCAT was accepted by <span style="color:Red ;">ICPP'22</span> and was presented at <span style="color:Red;">ACM TURC'2023 & ChinaSys</span>.[[News](https://zhuanlan.zhihu.com/p/650016166)]


# 📝 Publications 
- &nbsp; <span class="badge" style="font-size:16px;">ICSE '26 (CCF A)</span> &nbsp;**InferLog: Accelerating LLM Inference for Online Log Parsing via ICL-oriented Prefix Caching**

  <span style="font-size:14px;"> **Yilun Wang**, Pengfei Chen, Haiyu Huang, Zilong He, Gou Tan, Chuanfu Zhang, Jingkai He and Zibin Zheng. </span>

  <span style="font-size:14px;"> *The 48th IEEE/ACM International Conference on Software Engineering, Rio de Janeiro, Brazil, April 2026.* </span>

  [[Paper](https://github.com/wiluen/wiluen.github.io/blob/main/files/inferlog/icse26.pdf)]
  [Code]
  [Slides]
  [[DOI](https://arxiv.org/abs/2507.08523)]
  
- &nbsp; <span class="badge" style="font-size:16px;">ASPLOS '25 (CCF A)</span> &nbsp;**Mint: Cost-Efficient Tracing with All Requests Collection via Commonality and Variability Analysis**

  <span style="font-size:14px;"> Haiyu Huang, Cheng Chen, Kunyi Chen, Pengfei Chen, Guangba Yu, Zilong He, **Yilun Wang**, Huxing Zhang and Qi Zhou. </span>

  <span style="font-size:14px;"> *The ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Rotterdam, the Netherlands, March-April 2025.* </span>

  [Paper]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge" style="font-size:16px;">IWQOS '25 (CCF B)</span> &nbsp;**LLMConf: Knowledge-Enhanced Configuration Optimization for Large Language Model Inference**

  <span style="font-size:14px;"> Jingkai He, Pengfei Chen, **Yilun Wang**, Haiyu Huang, Chuanfu Zhang, Haojia Huang, Danwen Chen. </span>

  <span style="font-size:14px;"> *IEEE/ACM International Symposium on Quality of Service, Gold Coast, Australia, July 2025.* </span> 

  [Paper]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge" style="font-size:16px;">TPDS '24 (CCF A)</span> &nbsp;**DeepCAT+: A Low-Cost and Transferrable Online Configuration Auto-Tuning Approach for Big Data Framework**

  <span style="font-size:14px;"> Hui Dou, **Yilun Wang**(student first author), Yiwen Zhang, Pengfei Chen, Zibin Zheng. </span>

  <span style="font-size:14px;"> *IEEE Transactions on Parallel and Distributed Systems.* </span>

  [Paper]
  [[Code](https://github.com/wiluen/DeepCAT)]
  [Slides]
  [DOI]
  
- &nbsp; <span class="badge" style="font-size:16px;">ASE '24 (CCF A)</span> &nbsp;**FaaSConf: QoS-aware Hybrid Resources Configuration for Serverless Workflows**

  <span style="font-size:14px;"> **Yilun Wang**, Pengfei Chen, Hui Dou, Guangba Yu, Zilong He and Haiyu Huang. </span>

  <span style="font-size:14px;"> *The 39th IEEE/ACM International Conference on Automated Software Engineering, California, United States, October 2024.* </span>

  [[Paper](https://github.com/wiluen/wiluen.github.io/blob/main/files/faasconf/faasconf_camera_ready.pdf)]
  [[Code](https://github.com/wiluen/FaaSConf)]
  [Slides]
  [[DOI](https://doi.org/10.1145/3691620.3695477)]

- &nbsp; <span class="badge" style="font-size:16px;">ISSRE '24 (CCF B)</span> &nbsp;**FaaSRCA: Full Lifecycle Root Cause Analysis for Serverless Applications**

  <span style="font-size:14px;"> Jin Huang, Pengfei Chen, Guangba Yu, **Yilun Wang**, Haiyu Huang and Zilong He. </span>

  <span style="font-size:14px;"> *The 35th International Symposium on Software Reliability Engineering, Tsukuba, Japan, October 2024.* </span>

  [Paper]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge" style="font-size:16px;">ICPP '22 (CCF B)</span> &nbsp;**DeepCAT: A Cost-Efficient Online Configuration Auto-Tuning Approach for Big Data Frameworks**

  <span style="font-size:14px;"> Hui Dou, **Yilun Wang**(student first author), Yiwen Zhang, Pengfei Chen. </span>

  <span style="font-size:14px;"> *The 51st International Conference on Parallel Processing, Bordeaux, France, August 2022.* </span>

  [[Paper](https://github.com/wiluen/wiluen.github.io/blob/main/files/deepcat/22ICPP.pdf)]
  [[Code](https://github.com/wiluen/DeepCAT)]
  [Slides]
  [[DOI](https://doi.org/10.1145/3545008.3545018)]

# 🎖 Honors and Awards
- *2024.09* Excellent Award, Alibaba Cloud TIANCHI Cloud Native Programming Challenge **(As Team Leader)**
- *2024.06* Outstanding Master's Graduates of Anhui University
- *2022.10* National Scholarship, Ministry of Education of the P.R. China
- *2022.09* Outstanding Graduate Student Model and First Prize Scholarship of Anhui University
- *2020.08* 2nd Prize at the National Level, The 13th Chinese Collegiate Computing Competition(4C) **(As Team Leader)**

# 📖 Educations
- *2023.03-2025.06*, Research Assistant, Sun Yat-Sen University
- *2021.09-2024.06*, Master of Engineering degree, Anhui University
- *2017.09-2021.06*, Bachelor degree
 


<!-- # 💻 Internships -->
