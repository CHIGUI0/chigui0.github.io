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

Hi, I'm Chi Gui. I am a Master's student in Computer Science at the University of Illinois
Urbana-Champaign, advised by Prof. [Vikram Adve](https://vikram.cs.illinois.edu/).
I am also fortunate to work with Prof. [Manling Li](https://limanling.github.io/)
as a Research Intern at [Machine Learning and Language Lab](https://www.mll.lab.northwestern.edu/). Previously, I completed my B.S. at the Chinese University of Hong Kong, Shenzhen,
where I had the privilege of being mentored by Prof. [Benyou Wang](https://wabyking.github.io/old.html).

# 🔬 Research

My research aims to build **grounded and generalizable agents** that learn from
continuous interaction with the world. I focus on how reinforcement learning can
shape reasoning behaviors for reliable long-horizon decision-making. My interests
include:

- **Reasoning-Centric RL 🧠**: Eliciting robust reasoning through
  multi-turn and long-horizon reinforcement learning.
- **Interactive Agents 🔍**: Enabling agents to actively seek information and decide
  when to ask, reason, or act under incomplete inputs.
- **Multi-Agent Learning 🤝**: Studying RL for collaborative multi-agent settings.


# 📝 Publications 
\* indicates equal contribution.

- [“RAGEN-2: Reasoning Collapse in Agentic RL”](https://arxiv.org/abs/2604.06268), Zihan Wang *, **Chi Gui** *, Xing Jin *, Qineng Wang *, Licheng Liu *, Kangrui Wang, Shiqi Chen, Linjie Li, Zhengyuan Yang, Pingyue Zhang, Yiping Lu, Jiajun Wu, Li Fei-Fei, Lijuan Wang, Yejin Choi, Manling Li, ICML, 2026, <span style="color:red;">Oral</span>

- [“MIRAGE: A Benchmark for Multimodal Information-Seeking and Reasoning in Agricultural Expert-Guided Conversations”](https://arxiv.org/abs/2506.20100), Vardhan Dongre *, **Chi Gui** *, Shubham Garg, Hooshang Nayyeri, Gokhan Tur, Dilek Hakkani-Tür, Vikram S. Adve, NeurIPS Datasets & Benchmarks Track, 2025

- [“COD, Towards an Interpretable and Controllable Medical Agent using Chain of Diagnosis”](https://arxiv.org/abs/2407.13301), Junying Chen *, **Chi Gui** *, Anningzhe Gao, Ke Ji, Xidong Wang, Xiang Wan, Benyou Wang, ACL Findings, 2025
  
- [“HuatuoGPT-Vision, Towards Injecting Medical Visual Knowledge into Multimodal LLMs at Scale”](https://arxiv.org/abs/2406.19280), Junying Chen, **Chi Gui**, Anningzhe Gao, Shunian Chen, Guiming Hardy Chen, Xidong Wang, Ruifei Zhang, Zhenyang Cai, Ke Ji, Guangjun Yu, Xiang Wan, Benyou Wang, Proceeding of EMNLP, 2024

- [“Joint Optimization of Speaker Extraction and Diarization”](https://drive.google.com/file/d/10RNzRyDHseDmn73n-YiQn1zLFi9ueX17/view), Junyi Ao, **Chi Gui**, Meng Ge, Jingru Lin, Shuai Wang, Haizhou Li, Proceeding of National Conference on Man-Machine Speech Communication, 2023

# 📖 Educations
- *2024.08 - now*, Master of Science in Computer Science, University of Illinois Urbana-Champaign. 
- *2020.09 - 2024.05*, Bachelor of Computer Science and Engineering, the Chinese University of Hong Kong (Shenzhen). 

# 💻 Internships
- *2023.06 - 2023.09*, Hopesen, Shenzhen, China.
