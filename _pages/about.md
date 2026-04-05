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

Here is **Tao Zhang (Tao, 张涛)**.

I am a Ph.D. student in the School of Engineering at Westlake University, majoring in Computer Science under the supervision of Professor [Tailin Wu](https://tailin.org/). In the future, I hope to integrate control theory and artificial intelligence to make impactful contributions.

If you are interested in any aspect of me, I would love to chat and collaborate, please email me at - *zhangtao@westlake.edu.cn*

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->
# Research Interests
- Generative Models for Science (Diffusion Models, Flow Matching)
- AI for PDE Simulation and Control
- Complex Systems

My current research focuses on leveraging generative models (diffusion models, flow matching) for scientific simulation, control, and inverse design of complex physical systems.

# 📖 Educations
- *2020.09 - 2024.06*, B.S. in Wuhan University 
- *2024.09 - now*, PhD in Westlake University & Zhejiang University 

<!-- # 🔥 News -->

# 📝 Publications 

- **Feb 2025：** ICLR(2026), [VFScale: Intrinsic Reasoning through Verifier-Free Test-time Scalable Diffusion Model](https://arxiv.org/abs/2502.01989), Tao Zhang\*, Jia-Shu Pan\*, Ruiqi Feng, Tailin Wu\*†.

- **Jan 2025：** ICLR(2026), [GenCP: Towards Generative Modeling Paradigm of Coupled Physics](https://arxiv.org/abs/2601.19541), Tianrun Gao, Haoren Zheng, Wenhao Deng, Haodong Feng, Tao Zhang, Ruiqi Feng, Qianyi Chen, Tailin Wu†.

- **Dec 2024：** ICML(2025), [M2PDE: Compositional Generative Multiphysics and Multi-component PDE Simulation](https://arxiv.org/abs/2412.04134), Tao Zhang, Zhenhai Liu, Feipeng Qi, Yongjun Jiao†, Tailin Wu†.

- **Feb 2025：** ICML(2025), [From Uncertain to Safe: Conformal Fine-Tuning of Diffusion Models for Safe PDE Control](https://arxiv.org/abs/2502.02205), Peiyan Hu\*, Xiaowei Qian\*, Wenhao Deng, Rui Wang, Haodong Feng, Ruiqi Feng, Tao Zhang, Long Wei, Yue Wang, Zhi-Ming Ma, Tailin Wu†.

- **Aug 2024：** ICLR(2025), [CL-DiffPhyCon: Closed-loop Diffusion Control of Complex Physical Systems](https://arxiv.org/abs/2408.03124), Long Wei\*, Haodong Feng\*, Yuchen Yang, Ruiqi Feng, Peiyan Hu, Xiang Zheng, Tao Zhang, Dixia Fan, Tailin Wu†.

- **Dec 2024：** ICLR(2025), [Wavelet Diffusion Neural Operator](https://arxiv.org/abs/2412.04833), Peiyan Hu\*, Rui Wang\*, Xiang Zheng, Tao Zhang, Haodong Feng, Ruiqi Feng, Long Wei, Yue Wang, Zhi-Ming Ma, Tailin Wu†.

- **Jul 2024：** NeurIPS(2024), [DiffPhyCon: A Generative Approach to Control Complex Physical Systems](https://arxiv.org/abs/2407.06494), Long Wei\*, Peiyan Hu\*, Ruiqi Feng\*, Haodong Feng, Yixuan Du, Tao Zhang, Rui Wang, Yue Wang, Zhi-Ming Ma, Tailin Wu†.

- **Feb 2024：** ICLR(2024,spotlight), [Compositional Generative Inverse Design](https://arxiv.org/abs/2401.13171), Tailin Wu\*, Takashi Maruyama\*, Long Wei\*, Tao Zhang\*, Yilun Du\*, Gianluca Iaccarino, Jure Leskovec.