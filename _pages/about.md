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

An AI-powered platform for generating and editing product visuals for e-commerce applications.

**Key Contributions:**
- Built workflow for product background replacement with 10+ customizable style templates
- Implemented virtual try-on system preserving garment texture and fit with 90% user satisfaction
- Developed color adjustment algorithms maintaining consistency across different lighting conditions

## Music Visualization Agent (Lyrics-to-Visual Generation)
**Technologies:** Qwen-57B-MoRE, Flux, CLIP, Chain-of-Thought  
**Time:** 2024.09 - 2024.12

<img src="assets/music_visualization_demo.png" alt="Music Visualization Demo" width="400" style="max-width: 100%; height: auto;">

An AI agent that generates coherent visual sequences from song lyrics for music streaming platforms.

**Key Contributions:**
- Designed CoT-based pipeline for decomposing lyrics into structured visual prompts
- Leveraged Flux model for high-quality image generation with lyrical relevance
- Implemented CLIP-based filtering to reduce visual repetition by 40% in generated galleries

## Commercial AI Portrait Studio System
**Technologies:** Stable Diffusion, ControlNet, InstantID, LoRA  
**Time:** 2024.03 - 2024.07

<img src="assets/portrait_studio_demo.png" alt="AI Portrait Studio Demo" width="400" style="max-width: 100%; height: auto;">

An end-to-end system for generating professional portrait photographs in various artistic styles.

**Key Contributions:**
- Developed 3 distinct workflow templates for different portrait categories
- Trained 8+ style-specific LoRA adapters while maintaining subject identity
- Optimized inference pipeline to achieve average generation time of 3 seconds per image

## Multimodal Large Model for Power System Inspection
**Technologies:** VisualGLM-6B, LoRA, MMDetection, LangChain  
**Time:** 2023.06 - 2024.10

<img src="assets/power_inspection_demo.png" alt="Power System Inspection Demo" width="400" style="max-width: 100%; height: auto;">

A vision-language model specialized for power equipment defect detection and knowledge-based Q&A.

**Key Contributions:**
- Fine-tuned VisualGLM-6B on 5K+ domain-specific instruction pairs using LoRA
- Achieved >97% accuracy on critical safety scenarios (e.g., helmet detection)
- Built RAG-based Q&A system with reranking, achieving 73% answer relevance score
- Optimized DINO-InternImage model for small defect detection, improving mAP by 9.7%

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
