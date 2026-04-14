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

Jiawei Fan works for Intel Labs China <img src='images/intel.jpg' style='width: 2.5em;'> as an AI Research Scientist, supervised by <a href='https://yaoanbang.github.io/'>Anbang Yao</a>. His research interests span computer vision and model acceleration in deep learning. Previously, he explored knowledge transfer between models, contributing to model compression and training acceleration for omni-scale high-performance artificial intelligence systems.

He obtained master degree of computer science at Beijing University of Posts and Telecommunications (BUPT), supervised by <a href='https://teacher.bupt.edu.cn/songmeina/zh_CN/'>Meina Song</a>. Before that, he obtained **first-class honorable degree** of Bachelor of Science and Engineering. when he graduated from joint program of Beijing University of Posts and Telecommunications (BUPT) and Queen Mary University of London (QMUL).


# 🔥 News
- *2026.02*: &nbsp; A first-author paper on pre-training acceleration of Vision Foundational Models has been accepted to CVPR 2026.
- *2026.01*: &nbsp; A paper (SliderQuant) on post-training quantization for large language models was accepted to ICLR 2026.
- *2025.05*: &nbsp; A paper on diffusion acceleration framework that could accelerate any type of diffusion model has been accepted to ICML 2025.
- *2024.09*: &nbsp; A first-author paper on exploring KD method for transferring the scalability of pre-trained ViTs to various architectures has been accepted to NeurIPS 2024.
- *2023.09*: &nbsp; A first-author paper on efficient knowledge distillation for semantic segmentation has been accepted to NeurIPS 2023.
- *2022.12*: &nbsp; A first co-author paper on Video SSL has been accepted as a **Best Paper Award Honorable Mentioned** to ACCV 2022.  
- *2022.07*: &nbsp; A first-author paper on high-performance parameter-free regularization method for action recognition has been accepted to ACM MM 2022.  
- *2022.03*: &nbsp; A first-author paper on few-shot learning has been accepted to ICPR 2022. 
- *2021.05*: &nbsp; Rank 7th in the 3rd Person in Context workshop in CVPR 2021.

# 📝 Publications 

(* Equal contribution, # Corresponding author)


## Selected Publications


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/com-pt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Chain-of-Models Pre-training: Rethinking Training Acceleration of Vision Foundational Models](https://arxiv.org/pdf/2411.06786)

**Jiawei Fan**, Shigeng Wang, Chao Li, Xiaolong Liu, Anbang Yao\#

[**Code**](https://github.com/deep-optimization/CoM-PT) **|** [**Project**](https://github.com/deep-optimization/CoM-PT)
- This is the first work that unlocks the training efficiency scaling favorably with the VFM family size.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/ScaleKD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ScaleKD: Strong Vision Transformer Could Be Excellent Teachers](https://arxiv.org/pdf/2411.06786)

**Jiawei Fan**, Chao Li, Xiaolong Liu, Anbang Yao\#

[**Code**](https://github.com/deep-optimization/ScaleKD) **|** [**Project**](https://deep-optimization.github.io/scalekd/)
- It is the first work to explore how to transfer the scalable property of pre-trained large vision transformer models to smaller target models.
- ScaleKD could be used as a more efficient alternative to the time-intensive pre-training paradigm for any target student model on large-scale datasets.
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/afdcd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Augmentation-free Dense Contrastive Distillation for Efficient Semantic Segmentation](https://openreview.net/forum?id=caUhYUVsLl)

**Jiawei Fan**, Chao Li, Xiaolong Liu, Meina Song, Anbang Yao\#

[**Code**](https://github.com/OSVAI/Af-DCD)
- Af-DCD is a new augmentation-free dense contrastive distillation framework for efficient semantic segmentation. 
</div>
</div>

- [SliderQuant: Accurate Post-Training Quantization for Large Language Models.](https://jwfandl.github.io/), Shigeng Wang, Chao Li, Yangyuxuan Kang, **Jiawei Fan**, Zhonghong Ou, Anbang Yao#, International Conference on Learning Representations (ICLR 2026).
- [Morse: Faster Sampling for Accelerating Diffusion Models Universally.](https://jwfandl.github.io/), Chao Li, **Jiawei Fan**, Anbang Yao, International Conference on Machine Learning (ICML 2025).
- [DTR: An Information Bottleneck Based Regularization Framework for Video Action Recognition](https://dl.acm.org/doi/abs/10.1145/3503161.3548326), **Jiawei Fan\***, Yu Zhao\*\#, Xie Yu, Lihua Ma, Junqi Liu, Fangqiu Yi, Boxun Li, Proceedings of the 30th ACM International Conference on Multimedia (ACM-MM 2022).
- [TCVM: Temporal Contrasting Video Montage Framework for Self-supervised Video Representation Learning](https://openaccess.thecvf.com/content/ACCV2022/papers/Tian_TCVM_Temporal_Contrasting_Video_Montage_Framework_for_Self-supervised_Video_Representation_ACCV_2022_paper.pdf), Fengrui Tian\*, **Jiawei Fan\***, Xie Yu, Shaoyi Du#, Meina Song, Yu Zhao, Proceedings of the Asian Conference on Computer Vision (ACCV 2022). <font color='red'><b>(Oral and Best Paper Award Honorable Mentioned)</b></font>
- [Episodic Projection Network for Out-of-Distribution Detection in Few-shot Learning.](https://www.computer.org/csdl/proceedings-article/icpr/2022/09956184/1IHqfHmafKM), **Jiawei Fan**, Zhonghong Ou\#, Xie Yu, Junwei Yang, Shigeng Wang, Xiaoyang Kang, Hongxing Zhang, Meina Song, 26th International Conference on Pattern Recognition (ICPR 2022).


# 📖 Educations
- *2020.09 - 2023.06*, Master at Beijing University of Posts and Telecommunications.
- *2016.09 - 2020.06*, Bachelor at Beijing University of Posts and Telecommunications and Queen Mary University of London.

# 🎖 Honors and Awards
- *2023.11* Intel Labs China DRA Award.
- *2022.12* Best Paper Honorable Mentioned in ACCV 2022.
- *2022.04* MEGVII Outstanding Interns.
- *2021.10* First Class Scholarship of 2021.
- *2021.05* Win 7th in the 3rd Person in Context workshop in CVPR 2021.
- *2021.01* First Prize in Graduate Innovation and Entrepreneurship Competition.
- *2020.10* First Class Scholarship of 2020.
- *2020.06* BUPT Star of Youth. (10 students per year)
- *2020.02* M Prize in Mathematical Contest in Modeling.
- *2019.10* Tongding Enterprise Scholarship of 2019. (1 student per department)
- *2019.01* First Prize in Graduate Innovation and Entrepreneurship Competition. (as an undergraduate student)
- *2018.10* Hengtong Enterprise Scholarship of 2018.
- *2017.10* National Encouragement Scholarship of 2017.

# 💬 Academic service
Reviewer:  ICML 2025, ICLR 2025, NeurIPS 2024, AISTAT 2025, ACCV 2022.

<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Experieces
- *2022.07 - now*, Intel Labs, China. <img src='images/intel.jpg' style='width: 2.5em;'> Researcher, supervised by Anbang Yao.
- *2021.12 - 2022.07*, MEGVII Inc, China. <img src='images/megvii.png' style='width: 3.5em;'> Research Intern, supervised by Yu Zhao.
- *2021.04 - 2021.10*, Peking University, China. <img src='images/peking_university.png' style='width: 4.0em;'> Visit Student, supervised by Yang Liu.
- *2019.09 - 2019.11*, ByteDance Inc, China. <img src='images/bytedance.jpg' style='width: 4.3em;'> Data Engineer Intern.
