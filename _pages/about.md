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
**Technologies:** Diffusion Models, GANs, OpenCV, PyTorch  
**Time:** 2024.12 - Present



### AI去路人效果
<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin: 20px 0;">
  <div style="text-align: center;">
    <img src="assets/remove_persons_source2.png" alt="Original Scene with People" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
    <p style="margin-top: 8px; font-size: 14px; color: #666;">原始场景（含路人）</p>
  </div>
  <div style="text-align: center;">
    <img src="assets/remove_persons_result2.png" alt="Scene with People Removed" width="350" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
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
**技术原理：** 结合了Inpainting扩散模型与传统图像修复算法，实现了复杂场景下的高质量人物去除与背景补全。

**Key Contributions:**
- 集成基于扩散模型的Inpainting技术，实现复杂场景的智能修复（如去路人、背景补全）
- 开发实时人像美化管线，每帧处理时间<30ms
- 结合规则化色彩校正与AI驱动的风格迁移，实现一致的美学效果

# 📚 Publications

1. **Wang, Q.**, et al. (2024). "A Fine-Tuned Multimodal Large Model for Power Defect Image-Text Question-Answering." *Signal, Image and Video Processing* (SCI). [[PDF]](link-to-pdf)

2. **Wang, Q.**, et al. (2024). "A Multi-degradation Modeling and Deep Joint Prediction Approach for Video Quality Assessment." (Master's Thesis)

# 💻 Technical Skills
- **Generative AI:** Diffusion Models (Stable Diffusion, Flux), GANs, Transformer-based Generators
- **Multimodal Models:** LLaVA, InstructBLIP, Qwen-VL, InternLM-XComposer, VisualGLM
- **Framework & Tools:** PyTorch, Hugging Face, OpenCV, MMDetection, ComfyUI, LangChain
- **Model Optimization:** LoRA, P-Tuning, Quantization, Model Compression, ONNX/TensorRT
- **Programming:** Python, C++, Shell Scripting, JavaScript/TypeScript (basic)
- **MLOps:** Docker, Git, CI/CD, Model Serving, Performance Monitoring

# 📖 Education
- **M.Eng. in Computer Technology** (2022-2025)  
  Chinese Academy of Sciences & Hefei University (Joint Program)  
  Thesis: Video Quality Assessment via Multi-degradation Modeling

- **B.S. in Computer Science and Technology** (2018-2022)  
  Hefei University  
  Focus: Machine Learning & Computer Vision

# 🎖 Honors & Awards
- **First Prize**, Postgraduate Scholarship, Hefei University (2023)
- **Second Prize**, National College Students Mathematics Competition, Anhui Division (2021)
- **Outstanding Student Cadre**, Hefei University (2019)

# 👨‍💻 Online Profiles
- [**GitHub**](https://github.com/yourusername)
- [**Hugging Face**](https://huggingface.co/qqwangcr7)
- [**Google Scholar**](https://scholar.google.com/citations?user=wKuDueAAAAJ)
- [**LinkedIn**](https://linkedin.com/in/yourprofile)
- **Email**: qqwang0823@163.com
