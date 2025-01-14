---
layout: archive
title: "AutoAOI"
permalink: /autoaoi/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
# 关于AOI  
<details>
<summary>
[点击展开]
</summary>

# 什么是机器视觉  
机器视觉是人工智能的基础应用技术之一，通过模拟人类视觉系统赋予机器“看”和“认知”的能力。
机器视觉作为智能机器视觉能够在多种场景下替代人眼实现多种功能，主要包括识别、测量、定位和检测。
机器视觉作为现代工业与技术的核心驱动力，在提升生产效率保障作业安全、推动智能制造及产业升级方面展现出了非凡的重要性和无限潜力。  

<center>
  <img src="https://ray3572.github.io/images/autoaoi/typical_aoi_system.png">
</center>

# 什么是AOI  
自动光学检查（英语：Automated Optical Inspection，简称AOI），为高速高精度光学影像检测系统，运用机器视觉做为检测标准技术，
作为改良传统上以人力使用光学仪器进行检测的缺点，应用层面包括从高科技产业之研发、制造品管，以至国防、民生、医疗、环保、电力…等领域。
自动光学检查是工业制程中常见的代表性手法，利用光学仪器取得成品的表面状态，再以电脑影像处理技术来检出异物或图案异常等瑕疵，
因为是非接触式检查，所以可在中间工程检查半成品。高精度光学影像检测系统，包含量测镜头技术、光学照明技术、定位量测技术、电子电路测试技术、
影像处理技术及自动化技术应用等领域，其开发应用不但符合高科技产业发展需求，其技术层面更可扩展至国防军事工业，举凡兵工武器制造、夜视作战系统、
战略地形形貌之分析与研判等，都与此影像技术息息相关。  

——from wikipedia

</details>

## V0.5版本预计2025年一季度以论文形式公开

# AutoAOI简介
## AutoAOI服务于AOI机器视觉系统交付过程，致力于交付成本优化。
<details>
<summary>
[点击展开]
</summary>

### 如图所示，AOI产品交付往往包括以下几个步骤：
<center>
  <img src="\images\/autoaoi\/AOI_deployment.png">
</center>  

### 其中，光学方案设计是检测算法适配的上游。良好的光学方案能够有效降低算法研发的难度、提升算法精度，从而节约开发时间。光学方案的设计效率对缩短产品交付周期、降低交付成本、提升利润起着关键作用。光学方案可调参数较多，包括光源分布、光源入射角度、光照强度、光源色温等。在AOI设备的交付过程中，光学方案设计往往消耗大量人工，带来巨大的成本。
<center>
  <img src="\images\/autoaoi\/light_params.png">
</center>  

### 光学方案设计阶段的自动化允许更少的人工参与，同时因为数据采集与初步算法验证并行，单次设计验证的时间周期也大大缩短。不仅仅是人力成本的优化，还包括差旅、配套人员成本的降低、客户满意度的提升

<center>
  <img src="\images\/autoaoi\/decrease_deployment_cost.png">
</center>

</details>

## AutoAOI设计思路：借助 光学方案-检测算法 一体化，降低光学方案设计成本 
<details>
<summary>
[点击展开]
</summary>  

### 采用机器主观量化的方法而非人类主观量化的原因主要在于提高检测的一致性、效率和可重复性。人类主观评估受到个体差异等因素的影响，导致结果不稳定和难以量化。相比之下，机器主观量化方法通过自动化的图像处理和客观的算法来评估图像质量，能够提供更精确和可重复的测量结果。此外，机器量化方法可以快速处理大量数据，适合于大规模生产环境中的实时检测需求。
</details>

<center>
  <img src="\images\/autoaoi\/machine_human.png">
</center> 
<center>
  <img src="\images\/autoaoi\/autiaoi_vs_human.png">
</center>
<center>
  <img src="\images\/autoaoi\/overview.png">
</center>



## 效果展示
### 硬件设置如图所示
<center>
  <img src="\images\/autoaoi\/devices.png">
</center> 

### 晶圆缺陷打光过程
<center>
  <img src="\images\/autoaoi\/bilibili.png">
</center>  

[播放链接](https://www.bilibili.com/video/BV1t4rPYKEBJ/)

### 最新版本性能更加优秀   
<center>
  <img src="\images\/autoaoi\/version_comparison.png">
</center> 








