---
title: "论文阅读汇报 | 丰田工业大学：基于视觉语言模型增强的时序群组关联图动态群组检测 | 2025.11.24"
reportor: zengzeshan.md
tags: activity
---

 本次论文汇报工作由曾泽山进行，汇报的文章-基于视觉语言模型增强的时序群组关联图动态群组检测，由丰田工业大学2025年发布于国际计算机视觉大会。

## 文章概述

本文提出了一种视频中动态人类群组检测方法。在检测复杂群组时，不仅群组内成员的局部外观特征十分重要，场景的全局上下文同样关键。在本文方法中，我们利用为群组检测任务优化的视觉语言模型（Vision-Language Model, VLM），提取视频每帧中的局部与全局外观特征。为进一步提升性能，群组结构需在时间维度上保持一致性。以往方法通常假设视频中的群组结构固定不变，以此实现检测结果的稳定，但本文方法通过全局优化策略突破了这一限制 —— 我们利用基于群组关联增强的 CLIP 特征，估计所有帧的人员对群组关联概率，并构建图结构，最终实现对动态变化群组的检测。实验结果表明，该方法在公开数据集上的性能优于当前最先进的群组检测方法。

### 论文信息
- 文章标题: Dynamic Group Detection using VLM-augmented Temporal Groupness Graph
- 作者团队: Kaname Yokoyama, Chihiro Nakatani, Norimichi Ukita
- 作者机构: 丰田工业大学（Toyota Technological Institute）
- 文章地址: arxiv.org/abs/2509.04758
- 会议信息: ICCV 2025