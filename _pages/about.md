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

I am a master's student at Harbin Institute of Technology (Shenzhen), under the supervision of Prof. [Shuhan Qi](https://homepage.hit.edu.cn/qishuhan). I am now a visiting student at Hong Kong University of Science and Technology, working with Prof. [Long Chen](https://zjuchenlong.github.io/). 

# 🤔 Research Interests
- Multimodal: Multimodal Large Language Models
- Efficient Methods: Efficient Training & Inference, Model Compression

<font color="#ff644e">I am enthusiastic about minimalist, effective, and practical methods.</font>

# 🔥 News
- Honored to join [LONG Group](https://long-group.cse.ust.hk/) at HKUST as a visiting student, working with Prof. [Long Chen](https://zjuchenlong.github.io/).
- One paper on continual learning for MLLMs is accepted by EMNLP 2025.
- One [Zhihu blog](https://zhuanlan.zhihu.com/p/1926805011641372983) on Mechanism of MLLMs is forwarded by [PaperWeekly](https://mp.weixin.qq.com/s/B4SSNI2-0_zYsM4cLimNLQ).
- One paper on compressing diffusion models is out on arXiv.
- Excited to be a Research Intern at OPPO AI Center.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/MERA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Merge then Realign: Simple and Effective Modality-Incremental Continual Learning for Multimodal LLMs](https://arxiv.org/abs/2503.07663)

**Dingkun Zhang**, Shuhan Qi, Xinyu Xiao, Kehai Chen, Xuan Wang

[**Paper**](https://arxiv.org/pdf/2503.07663) <strong><span class='show_paper_citations' data='ZxPZDesAAAAJ:u-x6o8ySG0sC'></span></strong>
- Expand existing MLLMs to more modalities efficiently.
- Minimalist, Anti-Catastrophic Forgetting.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/LAPTOP-Diff.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LAPTOP-Diff: Layer Pruning and Normalized Distillation for Compressing Diffusion Models](https://arxiv.org/abs/2404.11098)

**Dingkun Zhang**\*, Sijia Li\*, Chen Chen, Qingsong Xie, Haonan Lu

[**Paper**](https://arxiv.org/pdf/2404.11098) <strong><span class='show_paper_citations' data='ZxPZDesAAAAJ:u5HHmVD_uO8C'></span></strong>
- Compress diffusion models through layer pruning and knowledge distillation.
</div>
</div>

# 📖 Educations
- *2024.06 - present*, Master's Student, Harbin Institute of Technology (Shenzhen).
- *2020.09 - 2024.06*, Undergraduate Student, Harbin Institute of Technology (Shenzhen).

# 💻 Internships
- *2025.10 - present*, Visiting Student, Hong Kong University of Science and Technology.
- *2023.09 - 2024.04*, Research Intern, OPPO AI Center.
