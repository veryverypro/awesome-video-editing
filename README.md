# Awesome DiT Video Editing Papers

A curated list of research papers on Diffusion Transformer (DiT) based video editing (2024-2025)

## 📝 Key Insights for Research

### Technical Advantages
1. **DiT vs U-Net**: DiT performs better in long-range dependency modeling and scalability
2. **Temporal Consistency**: Achieved through attention mechanisms and feature consistency constraints
3. **Computational Efficiency**: Pyramidal architecture and dynamic resolution adjustment significantly reduce costs
4. **Control Precision**: Trajectory guidance and multimodal conditions provide more precise control

### Research Opportunities
1. **DiT Video Editing Specialization**: Current DiT models mainly focus on generation, editing applications are relatively limited
2. **Real-time Editing**: Most methods still require long processing times
3. **Fine-grained Control**: Object-level and region-level precise editing still has room for improvement
4. **Physical Consistency**: Modeling of complex physical phenomena still needs improvement

---

## 📚 Table of Contents

- [📝 Key Insights for Research](#key-insights-for-research)
- [✂️ Video Editing](#video-editing)
- [🎨 Video Inpainting](#video-inpainting)
- [📊 Survey Papers](#survey-papers)
- [🔧 Open Source Projects](#open-source-projects)
- [🎯 Video Editing Research Directions](#video-editing-research-directions)
- [📈 Video Editing Tools](#video-editing-tools)
- [🔗 Useful Resources](#useful-resources)

---


## ✂️ Video Editing

### 2025 Latest Breakthroughs
- **[FADE] Frequency-Aware Diffusion Model Factorization for Video Editing** (Jun 2025) [[Paper]](https://arxiv.org/abs/2506.05934)
  - *Training-free video editing leveraging frequency-aware factorization of pre-trained video diffusion models*

- **[DAPE] Dual-Stage Parameter-Efficient Fine-Tuning for Consistent Video Editing** (May 2025) [[Paper]](https://arxiv.org/abs/2505.07057)
  - *High-quality yet cost-effective two-stage parameter-efficient fine-tuning framework for video editing*

- **[FlowV2V] Consistent Video Editing as Flow-Driven Image-to-Video Generation** (Jun 2025) [[Paper]](https://arxiv.org/abs/2506.07713)
  - *Re-investigating video editing as flow-driven I2V generation for better motion modeling*

- **[WeatherWeaver] Controllable Weather Synthesis and Removal** (Jul 2025) [[Paper]](https://arxiv.org/abs/2505.00704)
  - *Video diffusion model for synthesizing and removing weather effects without 3D modeling*

### DiT-Based Editing (2024)
- **[DiT4Edit] Diffusion Transformer for Image Editing** (Nov 2024) [[Paper]](https://arxiv.org/abs/2411.03286)
  - *First diffusion transformer-based image editing framework*

- **[VideoDirector] Precise Video Editing via Text-to-Video Models** (Nov 2024) [[Paper]](https://arxiv.org/abs/2411.17592)
  - *Precise video editing via text-to-video models*

- **[Re-Attentional Controllable Video Diffusion Editing]** (Dec 2024) [[Paper]](https://arxiv.org/html/2412.11706v1)
  - *Re-attentional control for video diffusion editing*

### Text-Driven Editing (2024)
- **[TokenFlow] Consistent Diffusion Features for Consistent Video Editing** (ICLR 2024) [[Paper]](https://arxiv.org/abs/2307.10373) [[Code]](https://github.com/omerbt/TokenFlow)
  - *Achieving video editing consistency through diffusion feature consistency*

- **[FateZero] Fusing Attentions for Zero-shot Text-based Video Editing** (ICCV 2023) [[Paper]](https://arxiv.org/abs/2303.09535) [[Code]](https://github.com/ChenyangQiQi/FateZero)
  - *Zero-shot text-based video editing with attention fusion mechanisms*

- **[CCEdit] Creative and Controllable Video Editing via Diffusion Models** (CVPR 2024)
  - *Creative and controllable video editing via diffusion models*

### Motion & Style Control (2024)
- **[Customize-A-Video] One-Shot Motion Customization** (Feb 2024) [[Paper]](https://arxiv.org/html/2402.14780v1)
  - *One-shot motion customization for text-to-video diffusion models*

- **[Tune-A-Video] One-Shot Tuning of Image Diffusion Models** (ICCV 2023) [[Code]](https://github.com/showlab/Tune-A-Video)
  - *One-shot tuning of image diffusion models for text-to-video generation*

### Advanced Editing Techniques (2024)
- **[FlexEdit] Flexible and Controllable Diffusion-based Object-centric Image Editing** (Aug 2024) [[Paper]](https://arxiv.org/abs/2408.12429)
  - *Flexible and controllable diffusion-based object-centric image editing*

---

## 🎨 Video Inpainting

### 2025 Latest
- **[DiffuEraser] A Diffusion Model for Video Inpainting** (Jan 2025) [[Paper]](https://arxiv.org/html/2501.10018v1)
  - *Stable diffusion-based video inpainting model overcoming blurring and mosaic artifacts*

- **[VipDiff] Training-free Video Inpainting via Denoising Diffusion Models** (Jan 2025) [[Paper]](https://arxiv.org/html/2501.12267v1)
  - *Training-free video inpainting diffusion model*

- **[ObjFiller-3D] Consistent Multi-view 3D Inpainting via Video Diffusion Models** (Aug 2025) [[Paper]](https://arxiv.org/html/2508.18271)
  - *Consistent multi-view 3D inpainting via video diffusion models*

- **[VideoPainter] Any-length Video Inpainting and Editing** (Mar 2025) [[Paper]](https://arxiv.org/html/2503.05639v1)
  - *Supports arbitrary-length video inpainting and editing, compatible with T2V and I2V DiT architectures*

### 2024 Core Works
- **[Video Diffusion Models are Strong Video Inpainter]** (Aug 2024) [[Paper]](https://arxiv.org/abs/2408.11402)
  - *First effective integration of image-to-video diffusion models into video inpainting tasks*

- **[Advanced Video Inpainting Using Optical Flow-Guided Efficient Diffusion]** (Dec 2024) [[Paper]](https://arxiv.org/html/2412.00857v2)
  - *Optical flow-guided efficient diffusion model for video inpainting*

- **[Semantically Consistent Video Inpainting with Conditional Diffusion Models]** (May 2024) [[Paper]](https://arxiv.org/abs/2405.00251)
  - *Semantically consistent video inpainting with conditional diffusion models*


---

## 📊 Survey Papers

- **[A Survey on Video Diffusion Models]** (2024) [[Paper]](https://arxiv.org/abs/2310.10647) [[ACM]](https://dl.acm.org/doi/10.1145/3696415)
  - *Comprehensive survey on video diffusion models covering generation, editing, and understanding tasks*

- **[Diffusion Model-Based Video Editing: A Survey]** (Jul 2024) [[Paper]](https://arxiv.org/html/2407.07111v1)
  - *Survey on diffusion model-based video editing techniques*

- **[Video Diffusion Models: A Survey]** (May 2024) [[Paper]](https://arxiv.org/html/2405.03150v2)
  - *Survey on video diffusion models*

---

## 🔧 Open Source Projects

### Video Editing Frameworks
- **[DynamiCrafter]** (ECCV 2024 Oral) [[Code]](https://github.com/Doubiiu/DynamiCrafter)
  - *Open-domain image animation generation with video diffusion priors*

### Video Understanding & Analysis
- **[Video-LLaVA]** (EMNLP 2024) [[Code]](https://github.com/PKU-YuanGroup/Video-LLaVA)
  - *Large-scale multimodal model with unified visual representation for video understanding*

---

## 🎯 Video Editing Research Directions

### Technical Trends in Video Editing
1. **From U-Net to Transformer**: DiT architecture shows better scalability and long-range dependency modeling in video editing tasks
2. **Spatiotemporal Consistency**: Better temporal consistency through spacetime patch processing in editing workflows
3. **Zero-shot Editing**: Rapid development of training-free video editing techniques
4. **Attention-based Control**: Precise editing control through attention mechanism manipulation
5. **Multimodal Conditioning**: Text, image, and trajectory-guided video editing

### Video Editing Applications
- **Text-driven Video Editing** (modify content based on text prompts)
- **Video Inpainting & Object Removal** (fill missing regions, remove unwanted objects)
- **Style Transfer & Appearance Editing** (change visual style while preserving motion)
- **Motion Control & Animation** (modify object trajectories and movements)
- **Temporal Consistency Maintenance** (ensure coherent edits across frames)

---

## 📈 Video Editing Tools (2024)

### Commercial Video Editing Tools
- **RunwayML Gen-3/Gen-4** - Professional-grade AI video editing capabilities
- **Pika Labs** - Consumer-friendly with creative video effects and editing
- **Adobe Firefly Video** - Enterprise video editing with AI assistance

### Open Source Video Editing Tools
- **TokenFlow** - Consistent video editing through diffusion features
- **FateZero** - Zero-shot text-based video editing
- **DynamiCrafter** - Image-to-video animation for editing workflows

---

## 🔗 Useful Resources

- **[Awesome Video Diffusion](https://github.com/showlab/Awesome-Video-Diffusion)** - Curated video diffusion model resources
- **[Awesome Video Diffusion Models](https://github.com/ChenHsing/Awesome-Video-Diffusion-Models)** - CSUR survey companion resources
- **[CVPR 2024 Tutorial](https://showlab.github.io/cvpr2024-tutorial-video-diffusion-models/)** - Tutorial on diffusion-based video generation models

---

*Last Updated: 2025-08-29*
*Research Scope: DiT-based video editing research 2024-2025*