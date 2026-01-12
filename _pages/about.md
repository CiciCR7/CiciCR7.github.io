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

I am a recent Master's graduate from the joint program between Hefei University and the Chinese Academy of Sciences. My research focuses on **Generative AI**, particularly **Image Generation** and **Multimodal Large Models**. I have practical experience in fine-tuning, deploying, and applying diffusion models and vision-language models to industrial applications such as digital content creation, e-commerce visualization, and power system inspection. I am passionate about advancing controllable generation techniques and making generative AI more accessible in vertical domains.

<a href='https://scholar.google.com/citations?user=wKuDueAAAAJ'>Google Scholar citations: <strong><span id='total_cit'></span></strong></a>

# 🚀 Projects

## AI-Powered Professional Photo Editing System

### AI去路人效果
<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 20px 0;">
  <!-- 第一组 -->
  <div style="text-align: center;">
    <img src="assets/remove_persons_source2.png" alt="Original Scene with People" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
    <p style="margin-top: 8px; font-size: 14px; color: #666;">原始场景（含路人）</p>
  </div>
  <div style="text-align: center;">
    <img src="assets/remove_persons_result2.png" alt="Scene with People Removed" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
    <p style="margin-top: 8px; font-size: 14px; color: #666;">AI去路人效果</p>
  </div>
  <!-- 第二组 -->
  <div style="text-align: center;">
    <img src="assets/remove_persons_source1.png" alt="Original Scene with People" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
    <p style="margin-top: 8px; font-size: 14px; color: #666;">原始场景（含路人）</p>
  </div>
  <div style="text-align: center;">
    <img src="assets/remove_persons_result1.png" alt="Scene with People Removed" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
    <p style="margin-top: 8px; font-size: 14px; color: #666;">AI去路人效果</p>
  </div>
</div>

### AI换商品背景效果
<div style="display: flex; flex-direction: column; gap: 30px; margin: 20px 0;">
  <!-- 第一组 -->
  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
    <div style="text-align: center;">
      <img src="assets/change_bg_source1.jpg" alt="Original Product Background 1" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <p style="margin-top: 8px; font-size: 14px; color: #666;">商品原始背景</p>
    </div>
    <div style="text-align: center;">
      <img src="assets/change_bg_result1.png" alt="Product with New Background 1" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <p style="margin-top: 8px; font-size: 14px; color: #666;">AI更换背景后（风格1）</p>
    </div>
  </div>
  <!-- 第二组 -->
  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
    <div style="text-align: center;">
      <img src="assets/change_bg_source2.jpg" alt="Original Product Background 2" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <p style="margin-top: 8px; font-size: 14px; color: #666;">商品原始背景</p>
    </div>
    <div style="text-align: center;">
      <img src="assets/change_bg_result2.png" alt="Product with New Background 2" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <p style="margin-top: 8px; font-size: 14px; color: #666;">AI更换背景后（风格2）</p>
    </div>
  </div>
</div>

### AI融图功能（Logo智能合成）
<div style="display: flex; flex-direction: column; gap: 30px; margin: 20px 0;">
  <!-- 第一组 -->
  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; align-items: flex-start;">
    <div style="display: flex; flex-direction: column; gap: 10px; text-align: center;">
      <img src="assets/rongtu_source1.jpg" alt="Background Image 1" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <p style="margin-top: 8px; font-size: 14px; color: #666;">背景图像</p>
    </div>
    <div style="display: flex; flex-direction: column; gap: 10px; text-align: center;">
      <img src="assets/logo1.jpg" alt="Logo Image 1" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <p style="margin-top: 8px; font-size: 14px; color: #666;">Logo图像</p>
    </div>
    <div style="text-align: center;">
      <img src="assets/rongtu_result1.png" alt="Merged Result 1" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <p style="margin-top: 8px; font-size: 14px; color: #666;">AI融图效果</p>
    </div>
  </div>
  <!-- 第二组 -->
  <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; align-items: flex-start;">
    <div style="display: flex; flex-direction: column; gap: 10px; text-align: center;">
      <img src="assets/rongtu_source2.jpg" alt="Background Image 2" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <p style="margin-top: 8px; font-size: 14px; color: #666;">背景图像</p>
    </div>
 
    <div style="text-align: center;">
      <img src="assets/rongtu_result2.png" alt="Merged Result 2" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <p style="margin-top: 8px; font-size: 14px; color: #666;">AI融图效果</p>
    </div>
  </div>
</div>

### Joker风格化效果
<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 20px 0;">
  <div style="text-align: center;">
    <img src="assets/1.jpg" alt="Original Portrait" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
    <p style="margin-top: 8px; font-size: 14px; color: #666;">原始人像</p>
  </div>
  <div style="text-align: center;">
    <img src="assets/joker_1.png" alt="Joker Style Transformation" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
    <p style="margin-top: 8px; font-size: 14px; color: #666;">Joker风格化效果</p>
  </div>
</div>
