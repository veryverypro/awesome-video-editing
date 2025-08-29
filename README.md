# Awesome DiT Video Generation & Editing Papers

基于 Diffusion Transformer (DiT) 的视频生成与编辑研究论文汇总 (2024-2025)

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
  - *Peebles et al.* - 奠定了 Diffusion Transformer 的基础架构

### Major Breakthroughs
- **[Sora] Video generation models as world simulators** (OpenAI, 2024) [[Paper]](https://openai.com/index/video-generation-models-as-world-simulators/)
  - *OpenAI* - 基于 DiT 的突破性视频生成模型，最长可生成 1 分钟 1080p 视频

---

## 🎬 Video Generation

### 2025 Latest
- **[DyDiT++] Dynamic Diffusion Transformers for Efficient Visual Generation** (Apr 2025) [[Paper]](https://arxiv.org/abs/2504.06803)
  - *动态调整时间步和空间维度，提升计算效率*

- **[RelightVid] Temporal-Consistent Diffusion Model for Video Relighting** (Jan 2025) [[Paper]](https://arxiv.org/html/2501.16330)
  - *基于扩散模型的时序一致性视频重光照技术*

- **[VideoPainter] Any-length Video Inpainting and Editing** (Mar 2025) [[Paper]](https://arxiv.org/html/2503.05639v1)
  - *支持任意长度视频的修复和编辑，兼容 T2V 和 I2V DiT 架构*

### 2024 Core Papers
- **[Tora] Trajectory-oriented Diffusion Transformer for Video Generation** (Jul 2024) [[Paper]](https://arxiv.org/abs/2407.21705)
  - *首个轨迹导向的 DiT 框架，集成文本、视觉和轨迹条件*

- **[CogVideoX] Text-to-Video Diffusion Models with An Expert Transformer** (Aug 2024) [[Paper]](https://arxiv.org/abs/2408.06072)
  - *大规模文本到视频生成模型，支持 10 秒 768×1360 分辨率视频*

- **[DiVE] DiT-based Video Generation with Enhanced Control** (Sep 2024) [[Paper]](https://www.aimodels.fyi/papers/arxiv/dive-dit-based-video-generation-enhanced-control)
  - *增强控制的 DiT 视频生成，包含时空条件和视频编辑界面*

- **[AV-DiT] Efficient Audio-Visual Diffusion Transformer** (Jun 2024) [[Paper]](https://openreview.net/forum?id=FE6zflN5G5)
  - *高效音视频同步生成的 DiT 模型*

- **[GenTron] Diffusion Transformers for Image and Video Generation** (CVPR 2024) [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_GenTron_Diffusion_Transformers_for_Image_and_Video_Generation_CVPR_2024_paper.pdf)
  - *图像和视频生成的扩散变换器*

- **[VDT] General-purpose Video Diffusion Transformers via Mask Modeling** (ICLR 2024) [[Code]](https://github.com/RERV/VDT)
  - *通用视频扩散变换器，基于掩码建模*

- **[Latte] Latent Diffusion Transformer for Video Generation** (TMLR 2025) [[Code]](https://github.com/Vchitect/Latte)
  - *潜在扩散变换器视频生成模型*

### Flow Matching Based
- **[Pyramid Flow] Pyramidal Flow Matching for Efficient Video Generative Modeling** (ICLR 2025) [[Paper]](https://arxiv.org/abs/2410.05954) [[Code]](https://github.com/jy0205/Pyramid-Flow)
  - *基于流匹配的金字塔视频生成，计算效率提升 4 倍*

- **[StreamDiT] Real-Time Streaming Text-to-Video Generation** (Jul 2025) [[Paper]](https://arxiv.org/abs/2507.03745)
  - *实时流式文本到视频生成*

---

## ✂️ Video Editing

### DiT-Based Editing
- **[DiT4Edit] Diffusion Transformer for Image Editing** (Nov 2024) [[Paper]](https://arxiv.org/abs/2411.03286)
  - *首个基于扩散变换器的图像编辑框架*

- **[VideoDirector] Precise Video Editing via Text-to-Video Models** (Nov 2024) [[Paper]](https://arxiv.org/abs/2411.17592)
  - *基于文本到视频模型的精确视频编辑*

- **[DiTCtrl] Attention Control in Multi-Modal Diffusion Transformer** (Dec 2024)
  - *多模态扩散变换器中的注意力控制，用于无调优多提示长视频生成*

### Text-Driven Editing
- **[TokenFlow] Consistent Diffusion Features for Consistent Video Editing** (ICLR 2024) [[Paper]](https://arxiv.org/abs/2307.10373) [[Code]](https://github.com/omerbt/TokenFlow)
  - *通过扩散特征一致性实现视频编辑的一致性*

- **[FateZero] Fusing Attentions for Zero-shot Text-based Video Editing** (ICCV 2023) [[Paper]](https://arxiv.org/abs/2303.09535) [[Code]](https://github.com/ChenyangQiQi/FateZero)
  - *零样本基于文本的视频编辑，融合注意力机制*

- **[CCEdit] Creative and Controllable Video Editing via Diffusion Models** (CVPR 2024)
  - *基于扩散模型的创意可控视频编辑*

### Motion & Style Control
- **[Customize-A-Video] One-Shot Motion Customization** (Feb 2024) [[Paper]](https://arxiv.org/html/2402.14780v1)
  - *单次运动定制文本到视频扩散模型*

- **[Tune-A-Video] One-Shot Tuning of Image Diffusion Models** (ICCV 2023) [[Code]](https://github.com/showlab/Tune-A-Video)
  - *单样本调优图像扩散模型用于文本到视频生成*

### Advanced Editing Techniques
- **[FADE] Frequency-Aware Diffusion Model Factorization for Video Editing** (Jun 2025) [[Paper]](https://arxiv.org/abs/2506.05934)
  - *频域感知的扩散模型分解用于视频编辑*

- **[FlexEdit] Flexible and Controllable Diffusion-based Object-centric Image Editing** (Aug 2024) [[Paper]](https://arxiv.org/abs/2408.12429)
  - *灵活可控的基于扩散的对象中心图像编辑*

---

## 🎨 Video Inpainting

### 2025 Latest
- **[DiffuEraser] A Diffusion Model for Video Inpainting** (Jan 2025) [[Paper]](https://arxiv.org/html/2501.10018v1)
  - *基于稳定扩散的视频修复模型，克服变换器模型的模糊和马赛克伪影*

- **[VipDiff] Training-free Video Inpainting via Denoising Diffusion Models** (Jan 2025) [[Paper]](https://arxiv.org/html/2501.12267v1)
  - *无训练视频修复扩散模型*

### 2024 Core Works
- **[Video Diffusion Models are Strong Video Inpainter]** (Aug 2024) [[Paper]](https://arxiv.org/abs/2408.11402)
  - *首次有效将图像到视频扩散模型整合到视频修复任务中*

- **[Advanced Video Inpainting Using Optical Flow-Guided Efficient Diffusion]** (Dec 2024) [[Paper]](https://arxiv.org/html/2412.00857v2)
  - *光流引导的高效扩散模型视频修复*

- **[Semantically Consistent Video Inpainting with Conditional Diffusion Models]** (May 2024) [[Paper]](https://arxiv.org/abs/2405.00251)
  - *基于条件扩散模型的语义一致性视频修复*

### Specialized Applications
- **[ObjFiller-3D] Consistent Multi-view 3D Inpainting via Video Diffusion Models** (Aug 2025) [[Paper]](https://arxiv.org/html/2508.18271)
  - *基于视频扩散模型的一致多视角 3D 修复*

---

## 📊 Survey Papers

- **[A Survey on Video Diffusion Models]** (2024) [[Paper]](https://arxiv.org/abs/2310.10647) [[ACM]](https://dl.acm.org/doi/10.1145/3696415)
  - *全面的视频扩散模型调研，涵盖生成、编辑和理解任务*

- **[Diffusion Model-Based Video Editing: A Survey]** (Jul 2024) [[Paper]](https://arxiv.org/html/2407.07111v1)
  - *基于扩散模型的视频编辑技术综述*

- **[Video Diffusion Models: A Survey]** (May 2024) [[Paper]](https://arxiv.org/html/2405.03150v2)
  - *视频扩散模型调研*

---

## 🔧 Open Source Projects

### Major Open Source Models
- **[Open-Sora Plan]** [[Code]](https://github.com/hpcaitech/Open-Sora) [[Paper]](https://arxiv.org/abs/2412.00131)
  - *开源大规模视频生成模型，支持 2s~15s，144p-720p，任意宽高比*
  - *Open-Sora 2.0 (11B) 在 30 万美元预算内达到 HunyuanVideo 同等性能*

- **[CogVideoX]** [[Code]](https://github.com/zai-org/CogVideo)
  - *智谱开源的 Sora 替代方案，支持文本到视频、视频延续、图像到视频*
  - *CogVideoX-5B 可在消费级 GPU 上运行*

- **[DynamiCrafter]** (ECCV 2024 Oral) [[Code]](https://github.com/Doubiiu/DynamiCrafter)
  - *基于视频扩散先验的开放域图像动画生成*

### Specialized Tools
- **[MagicTime]** (TPAMI 2025) [[Code]](https://github.com/PKU-YuanGroup/MagicTime)
  - *时延视频生成模型作为变形模拟器，支持物理现象模拟*

- **[Video-LLaVA]** (EMNLP 2024) [[Code]](https://github.com/PKU-YuanGroup/Video-LLaVA)
  - *统一视觉表示的大规模多模态模型*

- **[StreamingT2V]** (CVPR 2025) [[Code]](https://github.com/Picsart-AI-Research/StreamingT2V)
  - *一致性、动态性和可扩展的长视频生成*

---

## 🎯 Research Directions

### Technical Trends
1. **从 U-Net 到 Transformer**: DiT 架构在视频生成中显示出更好的可扩展性和长程依赖建模能力
2. **时空建模**: 通过时空补丁处理实现更好的时序一致性
3. **零样本编辑**: 无需训练的视频编辑技术快速发展
4. **效率优化**: 金字塔流匹配等技术显著降低计算成本
5. **多模态融合**: 文本、图像、视频的统一表示学习

### Application Areas
- **长视频生成** (最长可达 2 分钟)
- **高分辨率生成** (最高 1080p)
- **物理现象模拟** (时延视频、物理变化)
- **音视频同步生成**
- **3D 一致性建模**

---

## 📈 Market Leaders (2024)

### Commercial Products
- **OpenAI Sora** - 行业标杆，最高质量
- **RunwayML Gen-3/Gen-4** - 专业级视频编辑
- **Pika Labs** - 消费级友好，创意特效

### Open Source Alternatives
- **CogVideoX** - 最佳开源替代方案
- **Open-Sora Plan** - 完全开源，性能接近商业产品
- **Pyramid Flow** - 高效计算，开源可用

---

## 📝 Key Insights for Research

### 技术优势
1. **DiT vs U-Net**: DiT 在长程依赖建模和可扩展性方面表现更优
2. **时序一致性**: 通过注意力机制和特征一致性约束实现
3. **计算效率**: 金字塔架构和动态分辨率调整显著降低成本
4. **控制精度**: 轨迹引导和多模态条件提供更精确的控制

### 研究机会
1. **DiT 视频编辑专门化**: 当前 DiT 主要专注生成，编辑应用相对较少
2. **实时编辑**: 大多数方法仍需较长处理时间
3. **细粒度控制**: 对象级和区域级精确编辑仍有提升空间
4. **物理一致性**: 复杂物理现象的建模仍需改进

---

## 🔗 Useful Resources

- **[Awesome Video Diffusion](https://github.com/showlab/Awesome-Video-Diffusion)** - 视频扩散模型资源汇总
- **[Awesome Video Diffusion Models](https://github.com/ChenHsing/Awesome-Video-Diffusion-Models)** - CSUR 调研配套资源
- **[CVPR 2024 Tutorial](https://showlab.github.io/cvpr2024-tutorial-video-diffusion-models/)** - 基于扩散的视频生成模型教程

---

*最后更新: 2025-08-29*
*调研范围: 2024-2025 年基于 DiT 的视频生成与编辑研究*