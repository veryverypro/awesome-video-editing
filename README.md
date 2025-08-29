# Awesome DiT Video Generation & Editing Papers

A curated list of research papers on Diffusion Transformer (DiT) based video generation and editing (2024-2025)

## 📚 Table of Contents

- [🏗️ Foundational Models](#foundational-models)
- [🎬 Video Generation](#video-generation)
- [✂️ Video Editing](#video-editing)
- [🎨 Video Inpainting](#video-inpainting)
- [📊 Survey Papers](#survey-papers)
- [🔧 Open Source Projects](#open-source-projects)

---

## 🏗️ Foundational Models

### Core DiT Architecture
- **[DiT] Scalable Diffusion Models with Transformers** (2022) [[Paper]](https://arxiv.org/abs/2212.09748)
  - *Peebles et al.* - Foundational architecture for Diffusion Transformers

### Major Breakthroughs
- **[Sora] Video generation models as world simulators** (OpenAI, 2024) [[Paper]](https://openai.com/index/video-generation-models-as-world-simulators/)
  - *OpenAI* - Breakthrough DiT-based video generation model, up to 1 minute 1080p video

---

## 🎬 Video Generation

### 2025 Latest
- **[DyDiT++] Dynamic Diffusion Transformers for Efficient Visual Generation** (Apr 2025) [[Paper]](https://arxiv.org/abs/2504.06803)
  - *Dynamic adjustment of timestep and spatial dimensions for improved computational efficiency*

- **[RelightVid] Temporal-Consistent Diffusion Model for Video Relighting** (Jan 2025) [[Paper]](https://arxiv.org/html/2501.16330)
  - *Temporal-consistent video relighting using diffusion models*

- **[VideoPainter] Any-length Video Inpainting and Editing** (Mar 2025) [[Paper]](https://arxiv.org/html/2503.05639v1)
  - *Supports arbitrary-length video inpainting and editing, compatible with T2V and I2V DiT architectures*

### 2024 Core Papers
- **[Tora] Trajectory-oriented Diffusion Transformer for Video Generation** (Jul 2024) [[Paper]](https://arxiv.org/abs/2407.21705)
  - *First trajectory-oriented DiT framework integrating textual, visual, and trajectory conditions*

- **[CogVideoX] Text-to-Video Diffusion Models with An Expert Transformer** (Aug 2024) [[Paper]](https://arxiv.org/abs/2408.06072)
  - *Large-scale text-to-video generation model supporting 10-second 768×1360 resolution videos*

- **[DiVE] DiT-based Video Generation with Enhanced Control** (Sep 2024) [[Paper]](https://www.aimodels.fyi/papers/arxiv/dive-dit-based-video-generation-enhanced-control)
  - *Enhanced control DiT video generation with spatial-temporal conditioning and video editing interface*

- **[AV-DiT] Efficient Audio-Visual Diffusion Transformer** (Jun 2024) [[Paper]](https://openreview.net/forum?id=FE6zflN5G5)
  - *Efficient DiT model for synchronized audio-visual generation*

- **[GenTron] Diffusion Transformers for Image and Video Generation** (CVPR 2024) [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_GenTron_Diffusion_Transformers_for_Image_and_Video_Generation_CVPR_2024_paper.pdf)
  - *Diffusion transformers for image and video generation*

- **[VDT] General-purpose Video Diffusion Transformers via Mask Modeling** (ICLR 2024) [[Code]](https://github.com/RERV/VDT)
  - *General-purpose video diffusion transformers based on mask modeling*

- **[Latte] Latent Diffusion Transformer for Video Generation** (TMLR 2025) [[Code]](https://github.com/Vchitect/Latte)
  - *Latent diffusion transformer for video generation*

### Flow Matching Based
- **[Pyramid Flow] Pyramidal Flow Matching for Efficient Video Generative Modeling** (ICLR 2025) [[Paper]](https://arxiv.org/abs/2410.05954) [[Code]](https://github.com/jy0205/Pyramid-Flow)
  - *Flow matching based pyramidal video generation with 4x computational efficiency improvement*

- **[StreamDiT] Real-Time Streaming Text-to-Video Generation** (Jul 2025) [[Paper]](https://arxiv.org/abs/2507.03745)
  - *Real-time streaming text-to-video generation*

---

## ✂️ Video Editing

### DiT-Based Editing
- **[DiT4Edit] Diffusion Transformer for Image Editing** (Nov 2024) [[Paper]](https://arxiv.org/abs/2411.03286)
  - *First diffusion transformer-based image editing framework*

- **[VideoDirector] Precise Video Editing via Text-to-Video Models** (Nov 2024) [[Paper]](https://arxiv.org/abs/2411.17592)
  - *Precise video editing via text-to-video models*

- **[DiTCtrl] Attention Control in Multi-Modal Diffusion Transformer** (Dec 2024)
  - *Attention control in multi-modal diffusion transformers for tuning-free multi-prompt long video generation*

### Text-Driven Editing
- **[TokenFlow] Consistent Diffusion Features for Consistent Video Editing** (ICLR 2024) [[Paper]](https://arxiv.org/abs/2307.10373) [[Code]](https://github.com/omerbt/TokenFlow)
  - *Achieving video editing consistency through diffusion feature consistency*

- **[FateZero] Fusing Attentions for Zero-shot Text-based Video Editing** (ICCV 2023) [[Paper]](https://arxiv.org/abs/2303.09535) [[Code]](https://github.com/ChenyangQiQi/FateZero)
  - *Zero-shot text-based video editing with attention fusion mechanisms*

- **[CCEdit] Creative and Controllable Video Editing via Diffusion Models** (CVPR 2024)
  - *Creative and controllable video editing via diffusion models*

### Motion & Style Control
- **[Customize-A-Video] One-Shot Motion Customization** (Feb 2024) [[Paper]](https://arxiv.org/html/2402.14780v1)
  - *One-shot motion customization for text-to-video diffusion models*

- **[Tune-A-Video] One-Shot Tuning of Image Diffusion Models** (ICCV 2023) [[Code]](https://github.com/showlab/Tune-A-Video)
  - *One-shot tuning of image diffusion models for text-to-video generation*

### Advanced Editing Techniques
- **[FADE] Frequency-Aware Diffusion Model Factorization for Video Editing** (Jun 2025) [[Paper]](https://arxiv.org/abs/2506.05934)
  - *Frequency-aware diffusion model factorization for video editing*

- **[FlexEdit] Flexible and Controllable Diffusion-based Object-centric Image Editing** (Aug 2024) [[Paper]](https://arxiv.org/abs/2408.12429)
  - *Flexible and controllable diffusion-based object-centric image editing*

---

## 🎨 Video Inpainting

### 2025 Latest
- **[DiffuEraser] A Diffusion Model for Video Inpainting** (Jan 2025) [[Paper]](https://arxiv.org/html/2501.10018v1)
  - *Stable diffusion-based video inpainting model overcoming blurring and mosaic artifacts*

- **[VipDiff] Training-free Video Inpainting via Denoising Diffusion Models** (Jan 2025) [[Paper]](https://arxiv.org/html/2501.12267v1)
  - *Training-free video inpainting diffusion model*

### 2024 Core Works
- **[Video Diffusion Models are Strong Video Inpainter]** (Aug 2024) [[Paper]](https://arxiv.org/abs/2408.11402)
  - *First effective integration of image-to-video diffusion models into video inpainting tasks*

- **[Advanced Video Inpainting Using Optical Flow-Guided Efficient Diffusion]** (Dec 2024) [[Paper]](https://arxiv.org/html/2412.00857v2)
  - *Optical flow-guided efficient diffusion model for video inpainting*

- **[Semantically Consistent Video Inpainting with Conditional Diffusion Models]** (May 2024) [[Paper]](https://arxiv.org/abs/2405.00251)
  - *Semantically consistent video inpainting with conditional diffusion models*

### Specialized Applications
- **[ObjFiller-3D] Consistent Multi-view 3D Inpainting via Video Diffusion Models** (Aug 2025) [[Paper]](https://arxiv.org/html/2508.18271)
  - *Consistent multi-view 3D inpainting via video diffusion models*

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

### Major Open Source Models
- **[Open-Sora Plan]** [[Code]](https://github.com/hpcaitech/Open-Sora) [[Paper]](https://arxiv.org/abs/2412.00131)
  - *Open-source large-scale video generation model supporting 2s~15s, 144p-720p, arbitrary aspect ratios*
  - *Open-Sora 2.0 (11B) achieves performance comparable to HunyuanVideo with $300K budget*

- **[CogVideoX]** [[Code]](https://github.com/zai-org/CogVideo)
  - *Zhipu AI's open-source Sora alternative supporting text-to-video, video continuation, image-to-video*
  - *CogVideoX-5B runs on consumer-grade GPUs*

- **[DynamiCrafter]** (ECCV 2024 Oral) [[Code]](https://github.com/Doubiiu/DynamiCrafter)
  - *Open-domain image animation generation with video diffusion priors*

### Specialized Tools
- **[MagicTime]** (TPAMI 2025) [[Code]](https://github.com/PKU-YuanGroup/MagicTime)
  - *Time-lapse video generation models as metamorphic simulators for physical phenomena*

- **[Video-LLaVA]** (EMNLP 2024) [[Code]](https://github.com/PKU-YuanGroup/Video-LLaVA)
  - *Large-scale multimodal model with unified visual representation*

- **[StreamingT2V]** (CVPR 2025) [[Code]](https://github.com/Picsart-AI-Research/StreamingT2V)
  - *Consistent, dynamic, and extendable long video generation*

---

## 🎯 Research Directions

### Technical Trends
1. **From U-Net to Transformer**: DiT architecture shows better scalability and long-range dependency modeling in video generation
2. **Spatiotemporal Modeling**: Better temporal consistency through spacetime patch processing
3. **Zero-shot Editing**: Rapid development of training-free video editing techniques
4. **Efficiency Optimization**: Techniques like pyramidal flow matching significantly reduce computational costs
5. **Multimodal Fusion**: Unified representation learning for text, images, and videos

### Application Areas
- **Long Video Generation** (up to 2 minutes)
- **High Resolution Generation** (up to 1080p)
- **Physical Phenomena Simulation** (time-lapse videos, physical transformations)
- **Audio-Visual Synchronized Generation**
- **3D Consistent Modeling**

---

## 📈 Market Leaders (2024)

### Commercial Products
- **OpenAI Sora** - Industry benchmark, highest quality
- **RunwayML Gen-3/Gen-4** - Professional-grade video editing
- **Pika Labs** - Consumer-friendly with creative effects

### Open Source Alternatives
- **CogVideoX** - Best open-source alternative
- **Open-Sora Plan** - Fully open-source with performance close to commercial products
- **Pyramid Flow** - Efficient computation, open-source available

---

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

## 🔗 Useful Resources

- **[Awesome Video Diffusion](https://github.com/showlab/Awesome-Video-Diffusion)** - Curated video diffusion model resources
- **[Awesome Video Diffusion Models](https://github.com/ChenHsing/Awesome-Video-Diffusion-Models)** - CSUR survey companion resources
- **[CVPR 2024 Tutorial](https://showlab.github.io/cvpr2024-tutorial-video-diffusion-models/)** - Tutorial on diffusion-based video generation models

---

*Last Updated: 2025-08-29*
*Research Scope: DiT-based video generation and editing research 2024-2025*