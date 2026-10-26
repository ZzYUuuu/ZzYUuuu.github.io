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

I am currently a second-year Ph.D. student in the School of Computer Science and Technology at Anhui University, under the supervision of Prof. Yiwen Zhang. I have also been invited to serve as a reviewer for several international conferences and journals, including SIGIR, WWW and AAAI. My research primarily focuses on recommender systems, particularly collaborative filtering and generative recommendation: 

1. **Collaborative Filtering**: Collaborative filtering leverages historical user-item interactions to discover collaborative relationships and infer user preferences. By employing advanced representation learning techniques, such as graph neural networks and contrastive learning, collaborative filtering methods can effectively capture complex interaction patterns and learn informative user and item representations, thereby improving recommendation accuracy.

2. **Generative Recommendation**: Generative recommendation introduces a new paradigm for personalized recommendation by formulating recommendation tasks as generative processes. By leveraging techniques such as autoregressive modeling and large language models, these approaches capture user preferences and item dependencies to directly generate personalized recommendation results, offering greater flexibility in modeling complex user-item relationships.

# 🔥 News
- *2026.10*: &nbsp;🎉🎉 I am selected for the 2026 China Association for Science and Technology Young Scientist Sponsorship Program (Doctoral Student Special Project). 
- *2026.09*: &nbsp;🎉🎉 Winning China National Scholarship (Ranked 2nd in the School of Computer Science and Technology, Anhui University, 2026). 
- *2026.06*: &nbsp;🎉🎉 Winning Top 2% (21th) place in the preliminary round of the Tencent Advertising Algorithm Competition 2026.
- *2026.05*: &nbsp;🎉🎉 One paper focusing on refining alignment and uniformity in CF is accepted by the SIGKDD Conference on Knowledge Discovery and Data Mining (KDD’26).
- *2026.04*: &nbsp;🎉🎉 One paper focusing on intent space representation optimization for RS is accepted by the SIGIR Conference on Research and Development in Information Retrieval (SIGIR’26).
- *2025.11*: &nbsp;🎉🎉 One co-authored paper focusing on graph filter for RecSys is accepted by the Fortieth AAAI Conference on Artificial Intelligence (AAAI’26).
- *2025.09*: &nbsp;🎉🎉 Winning Top 1% (14th) place in the preliminary round of the Tencent Advertising Algorithm Competition 2025.
- *2025.04*: &nbsp;🎉🎉 One paper focusing on contrastive learning in CF is accepted by the SIGIR Conference on Research and Development in Information Retrieval (SIGIR’25).

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2026</div><img src='images/ReAU.pdf' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**ReAU: A Global-to-Local Perspective for Refining Alignment and Uniformity in Collaborative Filtering**](https://dl.acm.org/doi/10.1145/3770855.3817818)

**Yu Zhang**, Yi Zhang, Yiwen Zhang. 
The 32nd SIGKDD Conference on Knowledge Discovery and Data Mining (**KDD'26, CCF A**)[[Code](https://github.com/ZzYUuuu/ReAU)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2026</div><img src='images/DIAURec.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**DIAURec: Dual-Intent Space Representation Optimization for Recommendation**](https://dl.acm.org/doi/10.1145/3805712.3809551)

**Yu Zhang**, Yiwen Zhang, Yi Zhang, Lei Sang. 
The 49th International ACM SIGIR Conference on Research and Development in Information Retrieval (**SIGIR'26, CCF A**)[[Code](https://github.com/ZzYUuuu/DIAURec)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2025</div><img src='images/LightCCF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Unveiling Contrastive Learning’s Capability of Neighborhood Aggregation for Collaborative Filtering**](https://dl.acm.org/doi/10.1145/3770855.3817818)

**Yu Zhang**, Yiwen Zhang, Yi Zhang, Lei Sang, Yun Yang. 
The  48th International ACM SIGIR Conference on Research and Development in Information Retrieval (**SIGIR'25, CCF A**)[[Code](https://github.com/ZzYUuuu/LightCCF)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA 2025</div><img src='images/SUAU.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Towards Similar Alignment and Unique Uniformity in Collaborative Filtering**](https://www.sciencedirect.com/science/article/pii/S0957417424022139)

Lei Sang, **Yu Zhang**, Yi Zhang, Honghao Li, Yiwen Zhang.
Expert Systems With Applications (**ESWA'25, CCF C, JCR Q1**)[[Code](https://github.com/ZzYUuuu/SUAU)]
</div>
</div>

# 📝 Other Publications 
1. [**Revisiting Contrastive Learning in Collaborative Filtering via Parallel Graph Filters**](https://ojs.aaai.org/index.php/AAAI/article/view/38521).
Fang Kai, **Yu Zhang**, Kaibin Wang, Lei Sang, Yiwen Zhang. The Fortieth AAAI Conference on Artificial Intelligence (AAAI'26)

1. [**Semantic Augmented Multiview Graph Learning With Frequency-Aware Propagation for Recommendation**](https://ieeexplore.ieee.org/abstract/document/11656239).
Yixin Liu, **Yu Zhang**, Lei Sang, Yiwen Zhang. IEEE Transactions on Computational Social Systems (TCSS'26).

1. [**Joint Contrastive Representation Learning via Alignment and Uniformity for Collaborative Filtering**](https://ieeexplore.ieee.org/abstract/document/11535508).
Shihao Li, Xinzhe Jiang, **Yu Zhang**, Lei Sang, Yiwen Zhang. IEEE Transactions on Consumer Electronics (TCE'26)

1. [**Spatio-Temporal Context-Aware Web Service QoS Prediction via Contrastive Learning**](https://link.springer.com/chapter/10.1007/978-981-92-1300-9_4).
Xiang Mao, **Yu Zhang**, Yiwen Zhang, Xiaoyao Zheng. Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD'26)

# 🎖 Honors and Awards
- 🏆 2026 China Association for Science and Technology Young Scientist Sponsorship Program (Doctoral Student Special Project)
- 🏆 China National Scholarship (Ranked 2nd in the School of Computer Science and Technology, Anhui University, 2026)
- 🏆 First-Class Academic Scholarship (Awarded consecutively from 2023 to 2026, Anhui University)
- 🏆 Winning Top 2% (21th) place in the preliminary round of the Tencent Advertising Algorithm Competition 2026.
- 🏆 Winning Top 1% (14th) place in the preliminary round of the Tencent Advertising Algorithm Competition 2025.

# 📖 Educations
- *2023.09 - 2028.06 (now)*, Ph.D. student in the combined master’s and doctoral program in the School of Computer Science and Technology at Anhui University.
- *2019.09 - 2023.06*, Undergraduate student at Putian University.

