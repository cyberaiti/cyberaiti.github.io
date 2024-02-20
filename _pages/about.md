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

I'm an associate professor and currently work as a senior security researcher at the Institute of Innovation in NSFOCUS. I obtained my PhD degree in 2018 from the University of Chinese Academy of Sciences, mentored by Prof. Jinlin Wang and Prof. Xiao Chen. I was a postdoctoral scholar in the School of Information Science and Technology at Tsinghua University from 2018 to 2021. I was selected for the Beijing Nova Program (北京市科技新星计划) in 2021.

My research interests focus on trustworthy AI for Cybersecurity and data-driven threat hunting. I'm now leading the AISecOps team, which targets at the cross research area of AISec, AIOps and SecOps. 
I am now working on several directions including: 

<div>
<ul>              
<li><b>Alert Prioritization</b></li>
<li><b>Security Knowledge Graph</b></li>
<li><b>Provenance Graph Mining</b></li>    
<li><b>LLMs for Security</b></li>
</ul>
</div>

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 
- Hao Yue, Tong Li, Di Wu, Runzi Zhang, et al. Detecting APT attacks using an attack intent-driven and sequence-based learning approach[J]. Computers & Security, 2024, 140: 103748.（SCI二区，影响因子5.6，网络与信息安全CCF B类期刊，人工智能+终端威胁分析方向）
- 王维靖，陈俊洁，杨林，侯德俊，王星凯，吴复迪，张润滋等.基于多元数据融合的网络侧告警排序方法[J].软件学报,2024, 35(8):0-0.（EI，中文核心，智能运维领域方向）
- Liu J, Zhang R*, Liu W, et al. Context2Vector: Accelerating security event triage via context representation learning[J]. Information and Software Technology, 2022, 146: 106856.（SCI二区，影响因子3.862，软件工程CCF B类期刊，可解释人工智能+智能运维领域方向）
- 张润滋,康彬. 数据驱动的威胁狩猎语言模型研究进展[J]. 数据与计算发展前沿, 2022, 4(5): 98-107.（智能威胁分析方向）
- Li J, Li T, Zhang R, et al. APM: An Attack Path-based Method for APT Attack Detection on Few-Shot Learning[C]. 2023 IEEE 22th International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom).（信息安全CCF C类会议，智能威胁分析方向）
- Li Z, Li T, Zhang R, et al. A Novel Network Alert Classification Model based on Behavior Semantic[C]. SEKE, 2022: 553-558.（信息安全CCF C类会议，智能安全运营方向）
- 薛见新,王星凯,张润滋等.基于异构属性图的自动化攻击行为语义识别方法[J].信息安全研究,2022,8(03):292-300.（中文科技核心，人工智能+威胁检测方向）
- Niu W, Yu Z, Li Z, Li B, Zhang R, et al. LogTracer: Efficient Anomaly Tracing Combining System Log Detection and Provenance Graph[C]. GLOBECOM 2022-2022 IEEE Global Communications Conference, 2022: 3356-3361.（网络通信CCF C类会议，人工智能+终端威胁分析方向）
- Zhao Z, Niu W, Zhang X, et al. Trine: Syslog anomaly detection with three transformer encoders in one generative adversarial network[J]. Applied Intelligence, 2022, 52(8): 8810-8819.（SCI二区，影响因子5.3，人工智能CCF C类期刊，人工智能+终端威胁分析方向）
- Liu X, Li T, Zhang R, et al. A GAN and feature selection-based oversampling technique for intrusion detection[J]. Security and Communication Networks, 2021, 2021: 1-15.（SCI四区，智能威胁分析方向）
- Li X, Niu W, Zhang X, Zhang R, et al. Improving Performance of Log Anomaly Detection With Semantic and Time Features Based on BiLSTM-Attention[C]. 2021 2nd International Conference on Electronics, Communications and Information Technology (CECIT), 2021: 661-666.（EI会议，智能日志分析方向）
- Wang G, Li T, Yue H, Yang Z, Zhang R, et al. Integrating Heterogeneous Security Knowledge Sources for Comprehensive Security Analysis[C]. 2021 IEEE 45th Annual Computers, Software, and Applications Conference (COMPSAC), 2021: 714-724.（信息安全CCF C类会议，知识图谱+安全建模方向）
- 张润滋,刘文懋. AISecOps智能安全运营技术体系框架[J]. 数据与计算发展前沿, 2021, 3(3): 32-47.（提出AISecOps框架，智能安全运营方向）
- Zhang R, Tong M, Chen L, et al. CMIRGen: Automatic Signature Generation Algorithm for Malicious Network Traffic[C]. 2020 IEEE 19th International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom), 2020: 736-743.（信息安全CCF C类会议，XAIGen项目代码已开源，可解释人工智能+流量分析方向）
- Tong M, Li G, Zhang R, et al. Far from classification algorithm: dive into the preprocessing stage in DGA detection[C]. 2020 IEEE 19th International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom), 2020: 468-474.（信息安全CCF C类会议，人工智能+域名分析方向）
- 陈磊,薛见新,张润滋等.基于信息熵的数据集重标识风险评估方法[J].信息技术与网络安全,2020,39(12):1-6+12.DOI:10.19358/j.issn.2096-5133.2020.12.001.（中文核心，数据安全方向）
- Zhang R, Wang J, Chen X, et al. EDW-voting: Robust realtime traffic classification combined with flow side information[C]. 2018 Tenth International Conference on Advanced Computational Intelligence (ICACI), 2018: 438-442.（EI会议，人工智能+网络流量分析方向）
- Zhang R, Wang J, Sheng Y, et al. Protocol-aware packet scheduling algorithm for multi-protocol processing in multi-core MPL architecture[J]. IEICE TRANSACTIONS on Information and Systems, 2017, 100(12): 2837-2846.（SCI四区，网络调度优化方向）

# 📖 White Papers
- *2023.09*, 《安全行业大模型SecLLM技术》
- *2021.11*, 《安全知识图谱技术白皮书》
- *2020.12*, 《AISecOps智能安全运营技术白皮书》

# 💬 Invited Talks
<!-- - *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

- *2023.06*, 《ChatGPT等AI大模型对网络安全的机遇与挑战》工联安全大讲堂
- *2022.08*, 《名侦探的下午茶：Hunting with Provenance》 KCon 2022
- *2022.02*, 《From AISec to AISecOps：安全智能应用之道》 网络安全创新大会2021
- *2020.08*, 《打造风险驱动的智能威胁推荐引擎》 XCON 2020 
- *2020.10*, 《AISecOps智能安全运营技术体系与实践》 网络安全创新大会 2020
- *2019.11*, 《XAI与可信任安全智能》 网络安全创新大会 2019
- *2019.10*, 《基于可信线索挖掘的威胁狩猎》 INSEC WORLD 2019

# 🎖 Honors and Awards
- *2023*, 2022年度北京市科学技术奖科学技术进步奖二等奖
- *2023*, 第六届强网杯全国网络安全挑战赛 人工之智能专项赛 加密流量赛道 第二名 二等奖 （国家级）
- *2023*, 第六届强网杯全国网络安全挑战赛 人工之智能专项赛 智能渗透赛道 第三名 二等奖 （国家级）
- *2023*, 第六届强网杯全国网络安全挑战赛 人工之智能专项赛 智能渗透赛道 优秀指导教师  （国家级）
- *2022*, 入选2022年中国科协智库青年人才计划
- *2022*, 2022年中国计算机学会CCF科技成果奖科技进步二等奖
- *2022*, 2022年科技部全国颠覆性技术创新大赛领域赛优秀奖
- *2022*, 第一届中国科技青年论坛 中国科学技术协会 优秀奖
- *2022*, 中国人工智能产业发展联盟，人工智能关键技术和应用评测重点实验室 突出贡献个人
- *2021*, 第一届清华大学博士后创新创业大赛 清华大学 优胜奖
- *2021*, 入选北京市科技新星人才计划（北京市财政经费支持，市科委、中关村管委会组织实施的青年科技人才培养计划）