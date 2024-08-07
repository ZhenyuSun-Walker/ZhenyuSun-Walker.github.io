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

My research so far has concentrated on 3D-Reconstruction and Generative AI. As I deepen my exploration of Generative models and 3D Reconstruction methods, my goal is to achieve the alignment and interaction between textual information and 3D scene presentation, and to establish a strong mapping between the two on LLM (Large Language Models), providing the cornerstone of Platonic cognition for strong artificial intelligence.

<strong><span style="color:red; font-size:larger;">Sincerely looking for 26 fall Ph.D position!</span></strong>
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.07*: &nbsp;🎉🎉 I'm going to visiting [Prof. Huan Wang](https://huanwang.tech/) at Westlake University!
- *2024.06*: &nbsp;🎉🎉 Harvest the National College Student Innovation and Entrepreneurship Training Program Outstanding Project Completion! 
- *2024.06*: &nbsp;🎉🎉 Get the National Second Prize of MathorCup Mathematical Application Challenge <span style="color:red;">(Top 5%)</span>!
- *2023.12*: &nbsp;🎉🎉 Get the First Prize of National College Students’ Mathematics Competition Guangdong Division! 
- *2023.12*: &nbsp;🎉🎉 Get the First Prize of Huawei ICT Competition Guangdong Division! 
- *2023.09*: &nbsp;🎉🎉 Join [Prof. Qi Liu](https://drliuqi.github.io/)’s Laboratory at South China University of Technology！

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
- *2024.05* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2023.09* Third-Class South China University of Technology Scholarship. 

# 📖 Educations
- *2022.09 - present*, South China University of Technology, Undergraduate. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->



<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

<!-- # 🩴 My Interesting Life
- *2023.02*, **I cycled around Hainan Island in nine days, about 850 KM**, there is also a [video](https://www.bilibili.com/video/BV14e4y1P7o7/?vd_source=87867a0ba7d93f723755287cbc2e89fd) to record this.<br>
<div style="display:flex; justify-content:center; align-items:flex-start; flex-wrap:wrap;">
  <img src="images/cycle1.png" alt="Cycling around Hainan" title="Cycling around Hainan" width="330"/>&nbsp;&nbsp;&nbsp;
  <img src="images/cycle2.png" alt="Cycling around Hainan" title="Cycling around Hainan" width="330"/>
</div>

<br>

- *2022.10*, **I starred in a drama, which received an overwhelming response and received reports from Guangdong Province**<br>
<div style="display:flex; justify-content:center; align-items:flex-start; flex-wrap:wrap;">
  <img src="images/drama1.png" alt="Starring in a drama" title="Starring in a drama" width="445"/>&nbsp;&nbsp;&nbsp;
  <img src="images/drama2.png" alt="Starring in a drama" title="Starring in a drama" width="200"/>
</div>
<br>

- **I like football and travelling, especially with my friends and girlfriend.**<br>
<div id="slider" style="width: 900px; overflow: hidden; margin-left: 56px;">
    <div id="slider-inner">
        <img src="images/1.png" alt="Image 1">
        <img src="images/2.png" alt="Image 2">
        <img src="images/3.png" alt="Image 3">
        <img src="images/4.png" alt="Image 4">
        <img src="images/5.png" alt="Image 5">
        <img src="images/6.png" alt="Image 6">
        <img src="images/7.png" alt="Image 7">
        <img src="images/8.png" alt="Image 8">
        <img src="images/9.png" alt="Image 9">
        <img src="images/10.png" alt="Image 10">
        <img src="images/11.png" alt="Image 11">
        <img src="images/12.png" alt="Image 12">
        <img src="images/14.png" alt="Image 14">
    </div>
</div>

<script>
var slider = document.getElementById('slider');
var sliderInner = document.getElementById('slider-inner');
var images = sliderInner.getElementsByTagName('img');
var totalWidth = 0;
var currentOffset = 0;
var animationSpeed = 1;

// 计算所有图片的总宽度
function calculateTotalWidth() {
    totalWidth = Array.from(images).reduce((acc, img) => acc + img.offsetWidth + 10, 0); // 加上margin的宽度
}

// 动态移动图片以实现无限滚动
function cycleImages() {
    var firstImageWidth = images[0].offsetWidth + 10; // 加上margin的宽度

    if (currentOffset >= firstImageWidth) {
        sliderInner.appendChild(images[0]); // 将第一张图片移动到最后
        currentOffset -= firstImageWidth; // 调整当前偏移量
        sliderInner.style.transform = 'translateX(-' + currentOffset + 'px)';
    }
}

// 更新滚动动画
function updateAnimation() {
    currentOffset += animationSpeed;
    sliderInner.style.transform = 'translateX(-' + currentOffset + 'px)';
    cycleImages(); // 检查是否需要循环图片
    requestAnimationFrame(updateAnimation);
}

// 初始化
calculateTotalWidth();
requestAnimationFrame(updateAnimation);

// 当窗口大小变化时重新计算宽度
window.addEventListener('resize', calculateTotalWidth);
</script>

<style>
#slider img {
    max-height: 280px;
    height: auto;
    min-width: 100px; /* 根据实际情况调整 */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    border: 1px solid #ddd;
    margin-right: 10px; /* 增加间距 */
    border-radius: 10px; /* 圆角边框 */
    flex-shrink: 0;
}

#slider-inner {
    display: flex;
    align-items: center;
    transition: none; /* 移除过渡效果以避免移动时的跳动 */
}

@keyframes scroll {
    0% { transform: translateX(0); }
    100% { transform: translateX(calc(-1 * var(--totalWidth))); }
}

#slider img:hover {
    transform: scale(1.50); /* 鼠标悬停时放大 */
    box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2); /* 鼠标悬停时增加阴影 */
}

/* 如果图片未加载，显示一个简单的加载动画 */
#slider img:not([src]), 
#slider img:empty {
    min-width: 100px;
    background: linear-gradient(130deg, #e6e9f0 0%, #eef1f5 50%, #e6e9f0 100%);
    background-size: 200% 100%;
    animation: loadingAnimation 1s infinite;
}

@keyframes loadingAnimation {
    0% { background-position: 100% 0; }
    100% { background-position: 0 0; }
}
</style>

<br>
<div style="width: 500px; height: 500px; margin: auto;">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=UC6ibAca1Av5EPZP3WPd9Xzwv1J1pzlCFAfXYn0DNqI"></script>
</div>
<br> -->