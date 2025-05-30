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

I am a first-year Ph.D student at the [School of Computer Science, Wuhan University](https://cs.whu.edu.cn/), advised by [Prof. Bo Du](https://scholar.google.com/citations?user=Shy1gnMAAAAJ&hl=zh-CN) and [Prof. Juhua Liu](https://scholar.google.com/citations?user=wN-rIgIAAAAJ&hl=zh-CN). I work closely with [Dr. Jing Zhang](https://scholar.google.com/citations?user=9jH5v74AAAAJ&hl=zh-CN). I previously interned at JD Explore Academy and iFLYTEK Research.

My research interest includes Computer Vision, Large Language Model, and Multimodal Large Language Model. I previously focused on Optical Character Recognition (OCR) related topics. Now, my research interest lies in Multimodal Large Language Model. In addition, I closely follow the latest developments in Large Language Model.


# 🔥 News
- *2025.05*: &nbsp;🚀🚀 We release [LogicOCR](https://ymy-k.github.io/LogicOCR.github.io/), a benchmark designed to evaluate the logical reasoning abilities of Large Multimodal Models (LMMs) on text-rich images, while minimizing reliance on domain-specific knowledge. We offer key insights for enhancing multimodal reasoning.
- *2024.11*: &nbsp;🎉🎉 Hi-SAM is accepted by **IEEE TPAMI**. 
- *2024.09*: &nbsp;🎉🎉 One paper about video text spotting is accepted by **NeurIPS 2024**. 

# 📝 Publications 

\* : Co-first author

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TPAMI</div><img src='images/hisam.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Hi-SAM: Marrying Segment Anything Model for Hierarchical Text Segmentation](https://arxiv.org/abs/2401.17904) (**IEEE TPAMI**, <font color='red'><b>CCF-A</b></font>)

**Maoyuan Ye**, Jing Zhang,  Juhua Liu, Chenyu Liu, Baocai Yin, Cong Liu, Bo Du, Dacheng Tao

[**Project**](https://github.com/ymy-k/Hi-SAM)  <a href="https://github.com/ymy-k/Hi-SAM"><img src="https://img.shields.io/github/stars/ymy-k/Hi-SAM.svg?logo=github&label=Stars"></a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/gomatching.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[GoMatching: A Simple Baseline for Video Text Spotting via Long and Short Term Matching](https://arxiv.org/abs/2401.07080) (**NeurIPS 2024**, <font color='red'><b>CCF-A</b></font>)

Haibin He\*, **Maoyuan Ye**\*, Jing Zhang,  Juhua Liu, Bo Du, Dacheng Tao

[**Project**](https://github.com/Hxyz-123/GoMatching)  <a href="https://github.com/Hxyz-123/GoMatching"><img src="https://img.shields.io/github/stars/Hxyz-123/GoMatching.svg?logo=github&label=Stars"></a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/deepsolo.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DeepSolo: Let Transformer Decoder with Explicit Points Solo for Text Spotting](https://arxiv.org/abs/2211.10772) (**CVPR 2023**, <font color='red'><b>CCF-A</b></font>)

**Maoyuan Ye**\*, Jing Zhang\*, Shanshan Zhao, Juhua Liu, Tongliang Liu, Bo Du, Dacheng Tao

[**Project**](https://github.com/ViTAE-Transformer/DeepSolo)  <a href="https://github.com/ViTAE-Transformer/DeepSolo"><img src="https://img.shields.io/github/stars/ViTAE-Transformer/DeepSolo.svg?logo=github&label=Stars"></a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/dptext_detr.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DPText-DETR: Towards Better Scene Text Detection with Dynamic Points in Transformer](https://arxiv.org/abs/2207.04491) (**AAAI 2023, Oral**, <font color='red'><b>CCF-A</b></font>)

**Maoyuan Ye**, Jing Zhang, Shanshan Zhao, Juhua Liu, Bo Du, Dacheng Tao

[**Project**](https://github.com/ymy-k/DPText-DETR)   <a href="https://github.com/ymy-k/DPText-DETR"><img src="https://img.shields.io/github/stars/ymy-k/DPText-DETR.svg?logo=github&label=Stars"></a>
</div>
</div>


# 📝 Preprints 

\* : Co-first author

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv preprint</div><img src='images/logicocr.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LogicOCR: Do Your Large Multimodal Models Excel at Logical Reasoning on Text-Rich Images?](https://arxiv.org/abs/2505.12307)

**Maoyuan Ye**, Jing Zhang, Juhua Liu, Bo Du, Dacheng Tao

[**Project**](https://ymy-k.github.io/LogicOCR.github.io/)  <a href="https://github.com/MiliLab/LogicOCR"><img src="https://img.shields.io/github/stars/MiliLab/LogicOCR.svg?logo=github&label=Stars"></a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv preprint</div><img src='images/reasoning-ocr.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reasoning-OCR: Can Large Multimodal Models Solve Complex Logical Reasoning Problems from OCR Cues?](https://arxiv.org/abs/2505.12766)

Haibin He\*, **Maoyuan Ye**\*, Jing Zhang, Xiantao Cai, Juhua Liu, Bo Du, Dacheng Tao

[**Project**](https://github.com/Hxyz-123/ReasoningOCR)  <a href="https://github.com/Hxyz-123/ReasoningOCR"><img src="https://img.shields.io/github/stars/Hxyz-123/ReasoningOCR.svg?logo=github&label=Stars"></a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv preprint</div><img src='images/ele-sam.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adapting Segment Anything Model for Power Transmission Corridor Hazard Segmentation](https://arxiv.org/abs/2505.22105)

Hang Chen\*, **Maoyuan Ye**\*, Peng Yang, Haibin He, Juhua Liu, Bo Du

[**Project**](https://github.com/Hhaizee/ELE-SAM)  <a href="https://github.com/Hhaizee/ELE-SAM"><img src="https://img.shields.io/github/stars/Hhaizee/ELE-SAM.svg?logo=github&label=Stars"></a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv preprint</div><img src='images/gomatching++.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GoMatching++: Parameter- and Data-Efficient Arbitrary-Shaped Video Text Spotting and Benchmarking](https://arxiv.org/abs/2505.22228)

Haibin He, Jing Zhang, **Maoyuan Ye**, Juhua Liu, Bo Du, Dacheng Tao

[**Project**](https://github.com/Hxyz-123/GoMatching)  <a href="https://github.com/Hxyz-123/GoMatching"><img src="https://img.shields.io/github/stars/Hxyz-123/GoMatching.svg?logo=github&label=Stars"></a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv preprint</div><img src='images/deepsolo++.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DeepSolo++: Let Transformer Decoder with Explicit Points Solo for Multilingual Text Spotting](https://arxiv.org/abs/2305.19957)

**Maoyuan Ye**\*, Jing Zhang\*, Shanshan Zhao, Juhua Liu, Tongliang Liu, Bo Du, Dacheng Tao

[**Project**](https://github.com/ViTAE-Transformer/DeepSolo)  <a href="https://github.com/ViTAE-Transformer/DeepSolo"><img src="https://img.shields.io/github/stars/ViTAE-Transformer/DeepSolo.svg?logo=github&label=Stars"></a>
</div>
</div>


# 💻 Internships
- *2023.07 - 2024.02*, iFLYTEK Research, IFLYTEK CO. LTD., China.
- *2022.02 - 2023.06*, JD Explore Academy, JD Inc., China.

# 📖 Academic Service
- Conference Reviewer: CVPR, NeurIPS, ICCV, AAAI, ACM MM.
- Journal Reviewer: IEEE TPAMI, IJCV, TIP.