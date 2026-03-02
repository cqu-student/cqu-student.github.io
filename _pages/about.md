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
<!-- ========== 横渠四句书法 ========== -->
<div style="text-align:center; padding:0.5rem; margin:0.5rem auto 1.5rem; max-width:600px;">
  <img src="images/hengqu.jpg" alt="横渠四句" style="max-width:80%; height:auto; display:block; margin:0 auto;">
</div>

<!-- ========== About Me ========== -->
<span class='anchor' id='about-me'></span>

<div style="margin:1.5rem 0; padding:1.5rem; border:1px solid #e1e4e8; border-radius:8px; background:#fff; line-height:1.8; color:#34495e;">

<p style="margin:0 0 1rem;">
  👋 Hi, I'm <strong>Yuyang Hong (洪宇洋)</strong>, a PhD candidate at Institute of Automation, Chinese Academy of Sciences (CASIA) 🎓, expected to graduate in 2028. I completed my undergraduate studies at <a href="https://www.cqu.edu.cn/" style="color:#667eea; text-decoration:none;">Chongqing University</a>, where I was fortunate to be advised by <a href="https://www.cse.cqu.edu.cn/info/2095/5360.htm" style="color:#667eea; text-decoration:none;"> Prof. Haibo Hu</a> and <a href="https://www.cse.cqu.edu.cn/info/2095/7113.htm" style="color:#667eea; text-decoration:none;">Prof. Yongxin Ge</a>. Currently, I am honored to work under the supervision of <a href="https://people.ucas.ac.cn/~xiangshiming?language=cn" style="color:#667eea; text-decoration:none;">Prof. Shiming Xiang</a> at CASIA, with valuable guidance from <a href="https://yannqi.github.io/" style="color:#667eea; text-decoration:none;">Qi Yang</a> 🙏.
</p>

<p style="margin:0;">
  💼 I am currently a Research Intern at <a href="https://cn.aliyun.com/" style="color:#667eea; text-decoration:none;">Alibaba Cloud (Feitian Lab)</a>, mentored by <a href="https://lubinfan.github.io/" style="color:#667eea; text-decoration:none;">Lubin Fan</a>, and collaborating with <a href="https://gujiaqivadin.github.io/" style="color:#667eea; text-decoration:none;">Jiaqi Gu</a>, <strong>Yujin Lou</strong>, and <strong>Jinhui Guo</strong> 🤝. My research focuses on <strong>Vision-Language Models (VLM)</strong> 🖼️🗣️, <strong>Retrieval-Augmented Generation (RAG)</strong> 🔍, <strong>Continual Learning</strong> 🔄, and <strong>Audio-Visual Segmentation</strong> 🔊👁️. Thanks for anyone who helped me, and feel free to contact with me— 📧 <a href="mailto:hongyuyang2023@ia.ac.cn" style="color:#667eea; text-decoration:none;">hongyuyang2023@ia.ac.cn</a> ✨
</p>

</div>

---

# 📝 Publications

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div>
<img src='images/Neurlps2025.png' alt="thumbnail" style="width:100%; height:180px; object-fit:cover; object-position:center; border-radius:6px; display:block;">
</div></div>
<div class='paper-box-text' markdown="1">

**Knowledge-based Visual Question Answering with Multimodal Processing, Retrieval and Filtering**  
[📄 Paper](https://arxiv.org/abs/2510.14605) | [💻 GitHub](https://github.com/cqu-student/Wiki-PRF) | [🤗 HuggingFace](https://huggingface.co/hongyuyang23casia/Wiki-PRF-7B-Infoseek)

**Yuyang Hong**<sup>*</sup>, Jiaqi Gu<sup>*</sup>, Qi Yang, Lubin Fan<sup>†</sup>, Yue Wu, Ying Wang, Kun Ding<sup>†</sup>, Shiming Xiang, Jieping Ye

<span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span>

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVPR 2026</div>
<img src='images/CVPR2026.jpg' alt="thumbnail" style="width:100%; height:180px; object-fit:cover; object-position:center; border-radius:6px; display:block;">
</div></div>
<div class='paper-box-text' markdown="1">

**CC-VQA: Conflict- and Correlation-Aware Method for Mitigating Knowledge Conflict in Knowledge-Based Visual Question Answering**  
[📄 Paper](https://arxiv.org/abs/2602.23952v1) | [💻 GitHub](https://github.com/cqu-student/CC-VQA)

**Yuyang Hong**<sup>*</sup>, Jiaqi Gu<sup>*</sup>, Yujin Lou, Lubin Fan<sup>†</sup>,  Qi Yang, Ying Wang, Kun Ding, Yue Wu, Shiming Xiang, Jieping Ye

<span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span>

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">arXiv 2025</div>
<img src='images/arxiv2025.png' alt="thumbnail" style="width:100%; height:180px; object-fit:cover; object-position:center; border-radius:6px; display:block;">
</div></div>
<div class='paper-box-text' markdown="1">

**Taming Modality Entanglement in Continual Audio-Visual Segmentation**  
[📄 Paper](https://arxiv.org/abs/2510.17234) | [💻 GitHub](https://github.com/cqu-student/CMR) | [🤗 HuggingFace](https://huggingface.co/datasets/casiatao/IF-Bench)

**Yuyang Hong**<sup>*</sup>, Qi Yang, Tao Zhang, Zili Wang, Zhaojin Fu, Kun Ding, Bin Fan, Shiming Xiang

<span class='show_paper_citations' data='DhtAFkwAAAAJ:REPLACE_WITH_PAPER_ID'></span>

</div>
</div>

<!-- 无图论文 1: IF-Bench (共一标注) -->
<div style="margin:1.5rem 0; padding:1.2rem; border:1px solid #e1e4e8; border-radius:8px; background:#fff;">
  <span style="display:inline-block; padding:4px 10px; margin-right:10px; vertical-align:middle; background:linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius:4px; font-size:0.75rem; font-weight:600; color:white;">CVPR 2026</span> 
  <strong>IF-Bench: Benchmarking and Enhancing MLLMs for Infrared Images with Generative Visual Prompting</strong> <br><br>
  <a href="https://arxiv.org/abs/2512.09663" style="margin-left:10px;">📄 Paper </a> <a href="https://github.com/casiatao/IF-Bench" style="margin-left:10px;">💻 Github</a> <a href="https://arxiv.org/abs/2512.09663" style="margin-left:10px;">🤗 HuggingFace</a><br><br>
  Tao Zhang<sup>*</sup>, <strong>Yuyang Hong</strong><sup>*</sup>, Yang Xia, Kun Ding, Zeyu Zhang, Ying Wang, Shiming Xiang, Chunhong Pan<br>
</div>

<!-- 无图论文 2: ICASSP 2026 -->
<div style="margin:1.5rem 0; padding:1.2rem; border:1px solid #e1e4e8; border-radius:8px; background:#fff;">
  <span style="display:inline-block; padding:4px 10px; margin-right:10px; vertical-align:middle; background:linear-gradient(135deg, #fa709a 0%, #fee140 100%); border-radius:4px; font-size:0.75rem; font-weight:600; color:white;">ICASSP 2026</span> 
  <strong>Enhanced Graph Transformer with Serialized Graph Tokens</strong>
  <a href="https://arxiv.org/abs/2602.09065" style="margin-left:10px;">📄 Paper</a><br><br>
  Ruixiang Wang, <strong>Yuyang Hong</strong>, Shiming Xiang, Chunhong Pan
</div>

---

# 📖 Education
- *2023.09 – 2028.06 (Expected)*, PhD Candidate, Institute of Automation, Chinese Academy of Sciences, Beijing. 
- *2019.09 – 2023.06*, Bachelor, Data Science and Big Data Technology, Chongqing University, Chongqing. 

---

# 💻 Internships
- *2025.12 – Present*, [Alibaba Cloud](https://cn.aliyun.com/), Hangzhou, China.
