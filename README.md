# Awesome DiT Video Editing Papers

A curated list of research papers on Diffusion Transformer (DiT) based video editing (2024-2025)

## 📚 Table of Contents

- [🎯 Video Editing Research Directions](#video-editing-research-directions)
- [📝 Key Insights for Research](#key-insights-for-research)
- [✂️ Video Editing](#video-editing)
- [🎨 Video Inpainting](#video-inpainting)
- [📊 Survey Papers](#survey-papers)
- [🔧 Open Source Projects](#open-source-projects)
- [📈 Video Editing Tools](#video-editing-tools)
- [🔗 Useful Resources](#useful-resources)

---

## 🎯 Video Editing Research Directions

### Technical Trends in Video Editing
1. **Hybrid Training Strategies**: Evolution from training-free methods (TokenFlow, FateZero) to parameter-efficient fine-tuning (DAPE) and unified frameworks (VACE)
2. **Flow and Motion Modeling**: Integration of optical flow for temporal coherence (FlowV2V) and motion transfer (Video Motion Transfer)
3. **Frequency Domain Processing**: Spectrum-guided approaches for improved editing quality without training (FADE)
4. **Object-Centric Processing**: Region-specific computational allocation achieving 10x efficiency gains (Object-Centric Diffusion)
5. **Inversion Precision Enhancement**: Advanced solvers improving reconstruction accuracy for rectified flow models (RF-Solver-Edit)
6. **Attention Fusion Mechanisms**: Zero-shot editing through attention map manipulation and feature propagation
7. **Domain-Specific Specialization**: Targeted solutions for specific editing tasks (WeatherWeaver for weather effects)

### Video Editing Applications
- **Text-driven Content Modification** (TokenFlow, FateZero, VideoDirector)
- **Video Inpainting & Object Removal** (DiffuEraser, VipDiff, VideoPainter)
- **Domain-Specific Editing** (WeatherWeaver for weather effects, specialized scenarios)
- **Motion Transfer & Animation** (Video Motion Transfer, Customize-A-Video)
- **Multi-Task Unified Editing** (VACE for creation and editing integration)
- **Efficiency-Optimized Editing** (Object-Centric Diffusion for 10x speedup)
- **High-Precision Reconstruction** (RF-Solver-Edit for inversion accuracy)

---

## 📝 Key Insights for Research

### Technical Advantages
1. **Architecture Flexibility**: Both DiT (VACE, RF-Solver-Edit) and U-Net (FateZero, Object-Centric) architectures show effectiveness with different optimization strategies
2. **Training Efficiency**: Multiple approaches from zero-shot (TokenFlow, FateZero) to parameter-efficient fine-tuning (DAPE) reduce training costs
3. **Computational Optimization**: Object-centric processing (10x speedup) and frequency-domain methods (FADE) significantly improve efficiency
4. **Temporal Coherence**: Advanced consistency through flow modeling, attention propagation, and feature matching across frames
5. **Reconstruction Fidelity**: Enhanced inversion techniques (RF-Solver-Edit) enable higher-quality editing results

### Research Opportunities
1. **Cross-Task Unification**: VACE demonstrates potential for unified creation and editing frameworks, but more comprehensive solutions needed
2. **Real-time Performance**: Despite efficiency improvements (Object-Centric Diffusion's 10x speedup), most methods still require optimization for real-time applications
3. **Architecture-Specific Optimization**: Limited DiT-specific editing methods compared to U-Net approaches, opportunity for transformer-native techniques
4. **Advanced Motion Control**: Beyond basic motion transfer, need for complex physics-aware and multi-object interaction modeling
5. **Cross-Domain Generalization**: WeatherWeaver shows domain-specific success, opportunity for broader cross-domain editing capabilities
6. **Quality-Efficiency Trade-offs**: Balance between editing quality and computational cost remains challenging across different hardware constraints

---

## ✂️ Video Editing

### 2025 Latest Breakthroughs
- **[VACE] All-in-One Video Creation and Editing** (Mar 2025) [[Paper]](https://arxiv.org/abs/2503.07598)
  - *Unified framework for video creation and editing using Diffusion Transformers*

- **[RF-Solver-Edit] Taming Rectified Flow for Inversion and Editing** (ICML 2025) [[Paper]](https://arxiv.org/abs/2411.04746) [[Code]](https://github.com/wangjiangshan0725/RF-Solver-Edit)
  - *Training-free sampler for FLUX and OpenSora video editing with enhanced inversion precision*

- **[FADE] Frequency-Aware Diffusion Model Factorization for Video Editing** (Jun 2025) [[Paper]](https://arxiv.org/abs/2506.05934)
  - *Training-free video editing leveraging frequency-aware factorization of pre-trained video diffusion models*

- **[DAPE] Dual-Stage Parameter-Efficient Fine-Tuning for Consistent Video Editing** (May 2025) [[Paper]](https://arxiv.org/abs/2505.07057)
  - *High-quality yet cost-effective two-stage parameter-efficient fine-tuning framework for video editing*

- **[FlowV2V] Consistent Video Editing as Flow-Driven Image-to-Video Generation** (Jun 2025) [[Paper]](https://arxiv.org/abs/2506.07713)
  - *Re-investigating video editing as flow-driven I2V generation for better motion modeling*

- **[WeatherWeaver] Controllable Weather Synthesis and Removal** (Jul 2025) [[Paper]](https://arxiv.org/abs/2505.00704)
  - *Video diffusion model for synthesizing and removing weather effects without 3D modeling*

- **[Video Motion Transfer with Diffusion Transformers]** (Dec 2024) [[Paper]](https://arxiv.org/html/2412.07776v1)
  - *Training-free motion transfer method for video DiTs with zero-shot synthesis capabilities*

### DiT-Based Editing (2024)
- **[DiT4Edit] Diffusion Transformer for Image Editing** (Nov 2024) [[Paper]](https://arxiv.org/abs/2411.03286)
  - *First diffusion transformer-based image editing framework*

- **[VideoDirector] Precise Video Editing via Text-to-Video Models** (CVPR 2025) [[Paper]](https://arxiv.org/abs/2411.17592)
  - *Precise video editing via text-to-video models addressing color flickering and content distortion*

- **[Object-Centric Diffusion] Efficient Video Editing** (ECCV 2024) [[Paper]](https://arxiv.org/html/2401.05735)
  - *Object-centric sampling and token merging for 10x speed-up in video editing*

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

### 2025 Video Editing Frameworks
- **[Diffusion as Shader]** (SIGGRAPH 2025) [[Code]](https://github.com/IGL-HKUST/DiffusionAsShader)
  - *3D-aware video diffusion for versatile video generation control*

- **[EditDuet] Multi-Agent System for Video Non-Linear Editing** (SIGGRAPH 2025)
  - *Multi-agent system approach for advanced video editing workflows*

### Video Editing Frameworks (2024)
- **[DynamiCrafter]** (ECCV 2024 Oral) [[Code]](https://github.com/Doubiiu/DynamiCrafter)
  - *Open-domain image animation generation with video diffusion priors*

### Video Understanding & Analysis
- **[Video-LLaVA]** (EMNLP 2024) [[Code]](https://github.com/PKU-YuanGroup/Video-LLaVA)
  - *Large-scale multimodal model with unified visual representation for video understanding*

---

## 🔗 Useful Resources

- **[Awesome Video Diffusion](https://github.com/showlab/Awesome-Video-Diffusion)** - Curated video diffusion model resources
- **[Awesome Video Diffusion Models](https://github.com/ChenHsing/Awesome-Video-Diffusion-Models)** - CSUR survey companion resources
- **[CVPR 2024 Tutorial](https://showlab.github.io/cvpr2024-tutorial-video-diffusion-models/)** - Tutorial on diffusion-based video generation models

---

*Last Updated: 2025-08-29*
*Research Scope: DiT-based video editing research 2024-2025*