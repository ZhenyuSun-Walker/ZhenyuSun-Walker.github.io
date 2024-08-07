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

<br> 
<strong> Welcome to Zhenyu's website! </strong>

I'm Zhenyu Sun, and you can also call me Walker or Sorry. These two nicknames come from the name and songof two musicians, Alan Waler and Justin Biber. I am now an undergraduate of South China University of Technology at Guangzhou, China, and [here](/Zhenyu_Sun_CV.pdf) is my CV for specific information.

My research so far has concentrated on 3D-Reconstruction and Generative AI. As I deepen my exploration of Generative models and 3D Reconstruction methods, my goal is to achieve the alignment and interaction between textual information and 3D scene presentation, and to establish a strong mapping between the two on LLM (Large Language Models), providing the cornerstone of Platonic cognition for advanced artificial intelligence.
e google scholar badge <a href='https://scholar.google.com/citations?user=ADd-qVsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=f
<strong><span style="color:red; font-size:larger;">Sincerely looking for 26 fall Ph.D position!</span></strong>
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.07*: &nbsp;🎉🎉 I'm going to visiting [Prof. Huan Wang](https://huanwang.tech/) at Westlake University!
- *2024.06*: &nbsp;🎉🎉 Harvest the National College Student Innovation and Entrepreneurship Training Program Outstanding Project Completion! 
- *2024.06*: &nbsp;🎉🎉 Third-class Academic Innovation Award, Future Technology Taihu Innovation Award by Wuxi government. 
- *2024.06*: &nbsp;🎉🎉 Get the National Second Prize of MathorCup Mathematical Application Challenge <span style="color:red;">(Top 5%)</span>!
- *2023.12*: &nbsp;🎉🎉 Get the First Prize of National College Students’ Mathematics Competition Guangdong Division! 
- *2023.12*: &nbsp;🎉🎉 Get the First Prize of Huawei ICT Competition Guangdong Division! 
- *2023.09*: &nbsp;🎉🎉 Join [Prof. Qi Liu](https://drliuqi.github.io/)’s Laboratory at South China University of Technology！
- *2023.09*: &nbsp;🎉🎉 Won the Third-Class South China University of Technology Scholarship.

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVCG 2024 Under Review</div><img src='/images/Aerial-NeRF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Aerial-NeRF: Adaptive Spatial Partitioning and Sampling for Large-Scale Aerial Rendering](https://arxiv.org/pdf/2405.06214)

Xiaohan Zhang, Yukui Qiu, **Zhenyu Sun**, Qi Liu\*
-  We propose Aerial-NeRF with three innovative modifications for jointly adapting NeRF in large-scaleaerial rendering. Our model allows us to perform rendering over 4 times
   as fast as compared to multiple competitors at this point.
</div>
</div>


# 🎖 Honors and Awards
- *2024.06* Third-class Academic Innovation Award, Future Technology Taihu Innovation Award by Wuxi government. 
- *2023.10* Merit Student Honors, South China University of Technology. 
- *2023.09* Third-Class South China University of Technology Scholarship. 

# 📖 Educations
- *2022.09 - present*, South China University of Technology, Undergraduate. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->



<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 🩴 My Interesting Life
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Interactive Timeline</title>
<style>
  body {
    font-family: Arial, sans-serif;
  }
  .timeline {
    position: relative;
    max-width: 1200px;
    margin: 0 auto;
  }
  .timeline::after {
    content: '';
    position: absolute;
    width: 6px;
    background-color: #ddd;
    top: 0;
    bottom: 0;
    left: 50%;
    margin-left: -3px;
  }
  .container {
    padding: 10px 40px;
    position: relative;
    background-color: inherit;
    width: 50%;
  }
  .container::after {
    content: '';
    position: absolute;
    width: 25px;
    height: 25px;
    right: -17px;
    background-color: white;
    border: 4px solid #FF9F55;
    top: 15px;
    border-radius: 50%;
    z-index: 1;
  }
  .left {
    left: 0;
  }
  .right {
    left: 50%;
  }
  .left::before {
    content: " ";
    height: 0;
    position: absolute;
    top: 22px;
    width: 0;
    z-index: 1;
    right: 30px;
    border: medium solid white;
    border-width: 10px 0 10px 10px;
    border-color: transparent transparent transparent white;
  }
  .right::before {
    content: " ";
    height: 0;
    position: absolute;
    top: 22px;
    width: 0;
    z-index: 1;
    left: 30px;
    border: medium solid white;
    border-width: 10px 10px 10px 0;
    border-color: transparent white transparent transparent;
  }
  .right::after {
    left: -16px;
  }
  .content {
    padding: 20px 30px;
    background-color: white;
    position: relative;
    border-radius: 6px;
  }
  @media screen and (max-width: 600px) {
    .timeline::after {
      left: 31px;
    }
    .container {
      width: 100%;
      padding-left: 70px;
      padding-right: 25px;
    }
    .container::before {
      left: 60px;
      border: medium solid white;
      border-width: 10px 10px 10px 0;
      border-color: transparent white transparent transparent;
    }
    .left::after, .right::after {
      left: 15px;
    }
    .right {
      left: 0%;
    }
  }
</style>
</head>
<body>

<h2>Interactive Timeline</h2>
<div class="timeline">
  <div class="container left">
    <div class="content">
      <h2>2023.02</h2>
      <p>I cycled around Hainan Island in nine days, about 850 KM. <a href="https://www.bilibili.com/video/BV14e4y1P7o7/?vd_source=87867a0ba7d93f723755287cbc2e89fd" target="_blank">Watch the video</a></p>
      <img src="images/cycle1.png" alt="Cycling around Hainan" width="100%">
    </div>
  </div>
  <div class="container right">
    <div class="content">
      <h2>2022.10</h2>
      <p>I starred in a drama, which received an overwhelming response and received reports from Guangdong Province.</p>
      <img src="images/drama1.png" alt="Starring in a drama" width="100%">
    </div>
  </div>
</div>

</body>
</html>
