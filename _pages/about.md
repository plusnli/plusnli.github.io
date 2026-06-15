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

Hi there👋I am Jiaxi Li, a Ph.D. student at the University of Georgia. I obtained my Bachelor's degree in Computer Science from Shandong University in June 2024.

My research interests lie in Machine Reasoning and Large Language Models.


<!-- # 📝 Selected Publications -->
# 📝 Publications and Preprints
\* Equal Contribution; $\dagger$ Corresponding Author.

<div class='paper-box'>
<div class='paper-box-image'><div>
  <div class="badge">Preprint</div>
  <img src='images/papers/SGDR.png' alt="sym" width="78%">
</div></div>

<div class='paper-box-text' markdown="1">

[Online Skill Learning for Web Agents via State-Grounded Dynamic Retrieval](https://arxiv.org/abs/2606.04391)

**Jiaxi Li**, Ke Deng, Yun Wang, Jingyuan Huang, Yucheng Shi, Qiaoyu Tan, Jin Lu, Ninghao Liu

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div>
  <div class="badge">PAKDD 2026 Oral</div>
  <img src='images/papers/MITS.png' alt="sym" width="78%">
</div></div>

<div class='paper-box-text' markdown="1">

[MITS: Enhanced Tree Search Reasoning for LLMs via Pointwise Mutual Information](https://arxiv.org/abs/2510.03632)

**Jiaxi Li**, Yucheng Shi, Xiao Huang, Jin Lu, Ninghao Liu

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div>
  <div class="badge">NeurIPS 2025</div>
  <img src='images/papers/SymMPO.png' alt="sym" width="78%">
</div></div>

<div class='paper-box-text' markdown="1">

[Mitigating Hallucination Through Theory-Consistent Symmetric Multimodal Preference Optimization](https://arxiv.org/abs/2506.11712)

Wenqi Liu, Xuemeng Song$\dagger$, **Jiaxi Li**, Yinwei Wei, Na Zheng, Jianhua Yin, Liqiang Nie

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div>
  <div class="badge">EMNLP 2025 Main</div>
  <img src='images/papers/helene_3.png' alt="sym" width="72%">
</div></div>

<div class='paper-box-text' markdown="1">

[HELENE: Hessian Layer-wise Clipping and Gradient Annealing for Accelerating Fine-tuning LLM with Zeroth-order Optimization](https://arxiv.org/abs/2411.10696)

Huaqin Zhao\*, **Jiaxi Li\***, Yi Pan, Shizhe Liang, Xiaofeng Yang, Wei Liu, Xiang Li, Fei Dou, Tianming Liu, Jin Lu

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div>
  <div class="badge">Preprint</div>
  <img src='images/papers/MKJ.png' alt="sym" width="78%">
</div></div>

<div class='paper-box-text' markdown="1">

[Fact or Guesswork? Evaluating Large Language Models' Medical Knowledge with Structured One-Hop Judgments](https://arxiv.org/abs/2502.14275)

**Jiaxi Li**, Yiwei Wang, Kai Zhang, Yujun Cai, Bryan Hooi, Nanyun Peng, Kai-Wei Chang, Jin Lu

</div>
</div>


# 📖 Educations
- *2020.09 - 2024.06*, Shandong University, B.E. in Computer Science and Technology. 
- *2024.08 - current*, University of Georgia, Ph.D. in Computer Science.


# 💬 Selected Presentations
- *2023.10*, When do graph neural networks work on node classfication task and when not? [\[Blog\]](https://hackmd.io/@QpKVe67xTdOFuQ9_s2hbyA/B1qSq09g6) [\[知乎\]](https://zhuanlan.zhihu.com/p/662077835)
- *2024.10*, Scaling up test-time compute for LLM reasoning. [\[Slides\]](./data/Scaling_LLM_Test-Time_Compute_split.pdf)

# 📝 Services
- Reviewer for ACL 2025, EMNLP 2025.

# 🎖 Honors and Awards
- *2024.06* Outstanding graduate of Shandong Province.


<a href="https://clustrmaps.com/site/1c67i"  title="ClustrMaps"><img src="//www.clustrmaps.com/map_v2.png?d=V1E3PnXJSHWsLUVDYM88W42GIHb_kUaZXn5ehZkrHCk&cl=ffffff" /></a>

<style>
.paper-box-image {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 200px;
    overflow: hidden;
}
.paper-box-image img {
    width: auto !important;
    height: 100%;
    object-fit: contain;
}
</style>
