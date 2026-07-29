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

# ⌨️ About Me
<span class='anchor' id='about-me'></span>
<strong> Welcome to Zhenyu's website! </strong> 

I am **Zhenyu Sun**, a graduate student majored in Artificial Intelligence, South China University of Technology (SCUT), where I earned a GPA of **3.97/4.00** (rank:**1/76**). 

Here is my [**CV**](/ZhenyuSun_CV.pdf) for specific information. 

My research so far has concentrated on **Next-Generation 3DV**, targeting robust, efficient, adaptive and physically plausible 3D reconstruction and generation. 

I'm also interested in **Generative World Model**, aiming at realize world understanding, disambiguation, and prediction, with geometry and physics-based protocol.

I believe the exploration above will pave the way for realizing **Multimodal Intelligence** and **Generalized Intelligence**.

## <span style="color:red;">**I will spend the Ph.D journey supervised by esteemed [Prof. Yuanbo Xiangli](https://kam1107.github.io/), in School of Artificial Intelligence, Shanghai Jiao Tong University (SJTU), from 2026 fall！**</span>


# 🔥 News
- *2026.06*: &nbsp;🎉🎉 Congrats that our [CGGS: Consistency-Augmented Geometric Gaussian Splatting for Ego-Centric 3D Scene Generation](https://cggs-26.github.io/cggs26/) has been accepted by **TIP 2026**！
- *2026.06*: &nbsp;🎉🎉 My undergraduate thesis has received the **Excellent** evaluation！
- *2026.05*: &nbsp;🌟🌟 I had the privilege of participating in **CCIG 2026**. I was delighted to reunite with [Prof. Huan Wang](https://huanwang.tech/), [Prof. Qi Liu](https://drliuqi.github.io/) and [Prof. Xiaoguang Han](https://sse.cuhk.edu.cn/en/faculty/hanxiaoguang)！
- *2026.04*: &nbsp;🌟🌟 I was honored to participate in **China3DV 2026**, where I had the opportunity to engage in stimulating exchanges of ideas with scholars and professors in the field！
- *2026.03*: &nbsp;✨✨ I'm undertaking an on-site research internship, supervised by [Prof. Yuanbo Xiangli](https://kam1107.github.io/), at **Shanghai Jiao Tong University**.
- *2025.10*: &nbsp;🎉🎉 I have received **National Scholarship** (¥10,000, <span style="color:red;">**Top 0.4%, national wide**</span>) for the academic year 2024-2025, with the rank **1/76**！
- *2025.09*: &nbsp;✨✨ I'm conducting remote collaborative research with [Prof. Yuanbo Xiangli](https://kam1107.github.io/), at **Cornell University**.
- *2025.09*: &nbsp;🎉🎉 I am honored to have been admitted to the doctoral program at the **School of AI, Shanghai Jiao Tong University (SJTU)**! I'll spend the Ph.D journey supervised by [Prof. Yuanbo Xiangli](https://kam1107.github.io/)!
- *2024.12*: &nbsp;🎉🎉 Our work [Toy-GS: Assembling Local Gaussians for Precisely Rendering Large-Scale Free Camera Trajectories](https://arxiv.org/pdf/2412.10078v1) has been accepted by **AAAI 2025**!
- *2024.10*: &nbsp;🎉🎉 I have received **National Scholarship** (¥10,000, <span style="color:red;">**Top 0.4%, national wide**</span>) for the academic year 2023-2024, with the rank **1/76**.
- *2024.09*: &nbsp;🎉🎉 I have received **First-Class South China University of Technology Scholarship** (¥30,000, <span style="color:red;">**Top 1%**</span>) for the academic year 2023-2024.
- *2024.08*: &nbsp;✨✨ I am going to visiting _ENCODE Lab_ of [Prof. Huan Wang](https://huanwang.tech/) at **WLU**!
- *2024.06*: &nbsp;🎉🎉 I have harvested the **National College Student Innovation and Entrepreneurship Training Program <span style="color:red;">Outstanding Project Completion</span>**! 
- *2024.06*: &nbsp;🎉🎉 I have received the Third-class Academic Innovation Award, Future Technology Taihu Innovation Award by Wuxi government. 
- *2024.06*: &nbsp;🎉🎉 I have gotten the National Second Prize of MathorCup Mathematical Application Challenge <span style="color:red;">(Top 5%)</span>!
- *2023.12*: &nbsp;🎉🎉 I have won the **First Prize of National College Students’ Mathematics Competition Guangdong Division**! 
- *2023.12*: &nbsp;🎉🎉 I have won the **First Prize of Huawei ICT Competition Guangdong Division**! 
- *2023.09*: &nbsp;🎉🎉 I am going to join _MPRG Lab_ of [Prof. Qi Liu](https://drliuqi.github.io/) at **SCUT**！
- *2023.09*: &nbsp;🎉🎉 I have received the **Merit Student Honors, SCUT**.
- *2022.09*: &nbsp;🎉🎉 I have been admitted to **South China University of Technology (SCUT)**!


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2026</div><img src='/images/Publication/CGGS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CGGS: Consistency-Augmented Geometric Gaussian Splatting for Ego-Centric 3D Scene Generation](https://cggs-26.github.io/cggs26/)

**Zhenyu Sun**, Xiaohan Zhang, Qi Liu $^\uparrow$, Huan Wang $^\uparrow$
-  We propose CGGS, a new framework for ego-centric 3D scene generation from textual description. With the novel insight in MV-LDM and 3D Gaussian optimization, our method surpasses previous counterparts in terms of semantic alignment, perceptual quality, and rendering fidelity when producing realistic, domain-free 3D scenes.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2025</div><img src='/images/Publication/Garment-X.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GarmentX: Autoregressive Parametric Representations for High-Fidelity 3D Garment Generation](https://arxiv.org/pdf/2504.20409)

Jingfeng Guo, Jinnan Chen, Weikai Chen, **Zhenyu Sun**, Lanjiong Li, Baozhu Zhao, Lingting Zhu, Xin Wang, Qi Liu $^\uparrow$
-  We propose GarmentX, an image-guided 3D garment generator that produces editable garment parameters, decodes valid sewing patterns,
and simulates wearable 3D garments. By adjusting garment parameters, users can easily modify the shape, style, and even category of the
garments. The generated garments are diverse, high-fidelity, and physically plausible.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='/images/Publication/Toy-GS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Toy-GS: Assembling Local Gaussians for Precisely Rendering Large-Scale Free Camera Trajectories](https://arxiv.org/pdf/2412.10078v1)

Xiaohan Zhang, **Zhenyu Sun**, Yukui Qiu, Junyan Su, Qi Liu $^\uparrow$
-  We propose Toy-GS, a novel method that adaptively assembles local Gaussians to enhance rendering quality and reduce GPU memory usage for large-scale free camera trajectories.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2024</div><img src='/images/Publication/Aerial-NeRF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Aerial-NeRF: Adaptive Spatial Partitioning and Sampling for Large-Scale Aerial Rendering](https://arxiv.org/pdf/2405.06214)

Xiaohan Zhang, Yukui Qiu, **Zhenyu Sun**, Qi Liu $^\uparrow$
-  We propose Aerial-NeRF with three innovative modifications for jointly adapting NeRF in large-scale aerial rendering. Our model allows us to perform rendering over 4 times as fast as compared to multiple competitors.
</div>
</div>


# 🥇 Honors and Awards
- *2026.05* **Excellent Undergraduate Thesis**, for the academic year 2025-2026.
- *2025.10* **National Scholarship**, for the academic year 2024-2025.
- *2025.10* **Merit Student Honors**, South China University of Technology, for the academic year 2024-2025. 
- *2025.09* **Second-Class South China University of Technology Scholarship**, for the academic year 2024-2025.
- *2024.10* **National Scholarship**, for the academic year 2023-2024.
- *2024.10* **Merit Student Honors**, South China University of Technology, for the academic year 2023-2024. 
- *2024.09* **First-Class South China University of Technology Scholarship**, for the academic year 2023-2024.
- *2024.06* **Third-class Academic Innovation Award**, Future Technology Taihu Innovation Award by Wuxi government. 
- *2023.10* **Merit Student Honors**, South China University of Technology, for the academic year 2022-2023. 
- *2023.09* **Third-Class South China University of Technology Scholarship**, for the academic year 2022-2023. 

# 📖 Educations
- *2026.09*, SJTU, Ph.D. **(Incoming)**
- *2022.09 - 2026.06*, SCUT, Undergraduate. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->


# 💻 Professional Experiences
- *2026.03 - 2026.09* I'm undertaking an on-site research internship under the supervision of [Prof. Yuanbo Xiangli](https://kam1107.github.io/), at **Shanghai Jiao Tong University**.
- *2025.09 - 2026.02* I conduct remote collaborative research with [Prof. Yuanbo Xiangli](https://kam1107.github.io/), at **Shanghai Jiao Tong University**.
- *2024.08 - 2025.05* I visit _ENCODE Lab_ of [Prof. Huan Wang](https://huanwang.tech/) for research collaboration, at **Westlake University**. 
- *2023.09 - 2024.08* I join the _MPRG Lab_ of [Prof. Qi Liu](https://drliuqi.github.io/), at **South China University of Technology**.

<!-- Globe Widget -->
<br>
<div style="width: 200px; height: 200px; margin: auto;"> 
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=Cl6nCOwEKjyf4Du8XRwYJPZeD-QM6VPN5tFwyzzHDUk"></script>
</div>
<br>