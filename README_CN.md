[![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)]()
[![Ask Me Anything !](https://img.shields.io/badge/Ask me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama)
[![Awesome](https://raw.githubusercontent.com/1438802682/picgo_image/main/badge.svg)](https://awesome.re)

# NeRF 研究分类仓库

欢迎来到 NeRF 研究分类仓库！本仓库致力于分类和总结神经辐射场(NeRF)领域中日益增长的文献。目标是创建一个结构化且易于导航的路线图，以帮助研究人员、学生和爱好者轻松深入 NeRF 相关研究。

## 仓库结构

![](https://github.com/1438802682/NeRF-Research-Atlas/blob/main/NeRF%20Research%20Classification%20(NeRF%E7%A0%94%E7%A9%B6%E5%88%86%E7%B1%BB).png)

- **基本原理(Fundamentals):** 深入探讨 NeRF 的核心原理，包括基于 mip-NeRF 的方法、基于变形的技术，以及深度/点云监督。
- **速度优化(Speed Optimization):** 探索旨在提高 NeRF 算法速度的各种方法，包括非预计算(non-baked)、预计算(baked)和无多层感知机(MLP-less)方法。
- **稀疏视图合成(Sparse View Synthesis):** 通过代价体积方法等发现 NeRF 中的稀疏视图合成技术。
- **条件 NeRF(Conditional NeRF):** 揭示使用 GAN/VAE 方法和全局局部优化(Global Local Optimization)的条件 NeRF 技术。
- **组合技术(Composition Techniques):** 了解 NeRF 中的前景/背景分离和语义/对象组合。
- **姿态估计(Pose Estimation):** 深入研究 NeRF 中的姿态估计技术，包括基于 SLAM 的方法和束调整(Bundle Adjustment)。
- **应用(Applications):** 探索 NeRF 在城市环境、图像处理和三维重建中的多样化应用。
- **以人为中心的 NeRF(Human-centric NeRF):** 探索 NeRF 在面部和身体建模以及运动和姿态估计方面的人本应用。

本仓库中的每个类别都提供了经过策划的论文列表，以及简要描述，以提供对研究重点和贡献的 insight。我们欢迎贡献和建议，以便使此仓库与 NeRF 领域的最新进展保持同步。

## 1. Fundamentals (基本原理)

- 1.1 mip-NeRF Based (基于mip-NeRF)
  - 介绍和探讨基于多级金字塔(mip)的NeRF方法，以及如何通过使用这种技术来改进NeRF的性能和效果。
- 1.2 Deformation-based Methods (基于变形的方法)
  - 研究和分析NeRF中的变形技术，包括如何利用变形来改善三维重建和视图合成。
- 1.3 Depth and Point Cloud Supervision (深度和点云监督)
  - 探讨如何通过深度信息和点云数据来监督和优化NeRF的训练过程。
- 1.4 Miscellaneous Methods (其他方法)
  - 包括其他不属于上述类别但与NeRF基本原理相关的研究方法和技术。
- 1.5 Hybrid Methods (混合方法)
  - 探讨结合多种技术（如基于变形的方法和深度监督）来改善NeRF性能的方法。

## 2. Speed Optimization (速度优化)

- 2.1 Non-baked Methods (非预计算方法)
  - 研究和分析非预计算或实时NeRF技术，以及如何通过不使用预计算来优化速度。
- 2.2 Baked Methods (预计算方法)
  - 探讨通过预计算数据来加速NeRF的方法和技术。
- 2.3 MLP-less Methods (无多层感知机方法)
  - 探讨在不使用多层感知机（MLP）的情况下优化NeRF速度的方法。
- 2.4 Hardware Acceleration (硬件加速)
  - 分析利用GPU, TPU等硬件资源来加速NeRF计算的方法和技术。

## 3. Sparse View Synthesis (稀疏视图合成)

- 3.1 Cost Volume Approaches (代价体积方法)
  - 通过代价体积来解决NeRF中的稀疏视图合成问题的方法。
- 3.2 Other Techniques (其他技术)
  - 介绍其他稀疏视图合成的技术和方法。
- 3.3 Domain Adaptation (领域适应)
  - 探讨如何通过领域适应技术来提高NeRF在稀疏视图合成中的性能。

## 4. Conditional NeRF (条件NeRF)

- 4.1 GAN and VAE Methods (GAN和VAE方法)
  - 利用生成对抗网络(GAN)和变分自编码器(VAE)来实现条件NeRF的方法。
- 4.2 Global Local Optimization (GLO) (全局局部优化)
  - 探讨通过全局局部优化来改善NeRF性能的技术。
- 4.3 Conditional Training Techniques (条件训练技术)
  - 探讨如何利用条件训练技术来优化NeRF模型的学习过程。

## 5. Composition Techniques (组合技术)

- 5.1 Foreground and Background Separation (前景和背景分离)
  - 研究和分析如何在NeRF中实现前景和背景的分离和组合。
- 5.2 Semantic and Object Composition (语义和对象组合)
  - 探讨如何通过语义和对象级的组合来改善NeRF的表现。
- 5.3 Multi-Modal Composition (多模态组合)
  - 探讨如何利用多模态数据（如图像和语义信息）来改善NeRF的组合技术。

## 6. Pose Estimation (姿态估计)

- 6.1 SLAM-based Methods (基于SLAM的方法)
  - 介绍利用SLAM技术来进行姿态估计的NeRF方法。
- 6.2 Bundle Adjustment (BA) and Other Techniques (束调整及其他技术)
  - 探讨通过束调整和其他技术来优化NeRF中的姿态估计。
- 6.3 Multi-View Geometry (多视几何)
  - 研究多视几何技术如何应用于NeRF中的姿态估计。

## 7. Applications (应用)

- 7.1 Urban Environments (城市环境)
  - 7.1.1 Street Level (街道层面)
    - 探讨NeRF在街道层面的应用，例如三维重建和视图合成等。
  - 7.1.2 Remote Sensing and Aerial Imaging (遥感和航空成像)
    - 研究和分析NeRF在遥感和航空成像领域的应用。
- 7.2 Image Processing (图像处理)
  - 7.2.1 Editing (编辑)
    - 探讨利用NeRF进行图像编辑的方法和技术。
  - 7.2.2 Labeling (标注)
    - 介绍通过NeRF来实现图像和三维数据的标注技术。
  - 7.2.3 Fundamental Operations (基本操作)
    - 探讨NeRF在图像处理的基本操作，例如滤波和增强等。
- 7.3 3D Reconstruction (三维重建)
  - 7.3.1 Signed Distance Functions (SDF) (有符号距离函数)
    - 介绍利用有符号距离函数来实现三维重建的NeRF方法。
  - 7.3.2 Occupancy Methods (占用方法)
    - 探讨通过占用信息来实现三维重建的NeRF技术。
- 7.4 Virtual and Augmented Reality (虚拟和增强现实)
  - 7.4.1 Real-time Rendering (实时渲染)
    - 探讨NeRF在实时渲染方面的应用，包括在VR/AR环境中的表现。

## 8. Human-centric NeRF (以人为中心的NeRF)

- 8.1 Facial Modeling (面部建模)
  - 研究和分析NeRF在面部建模方面的应用。
- 8.2 Body Modeling (身体建模)
  - 探讨利用NeRF进行身体建模的技术和方法。
- 8.3 Motion and Pose Estimation (运动和姿态估计)
  - 介绍利用NeRF进行运动和姿态估计的方法。
- 8.4 Interaction and Animation (交互和动画)
  - 研究和分析利用NeRF创建交互式和动态3D模型的方法和技术。

## 贡献

我们鼓励来自社区的贡献。无论您想添加新论文、类别还是改进现有分类，都可以随时发起拉取请求。

## 联系

如有任何疑问或建议，请开放问题。

