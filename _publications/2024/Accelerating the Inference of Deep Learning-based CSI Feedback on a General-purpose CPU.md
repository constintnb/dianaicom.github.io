---
title:          "Accelerating the Inference of Deep Learning-based CSI Feedback on a General-purpose CPU"
date:           2024-08-07
selected:       false                        # 设置为 true 会在首页“精选论文”中显示
pub:            "IEEE/CIC International Conference on Communications in China (ICCC2024)"
pub_date:       "2024"                      # 显示在会议名后面的年份
#pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>' # 可选：添加徽章 (Oral, Spotlight, Best Paper)

# 引用计数 (可选)
#semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776

# 摘要 (支持 HTML 和 LaTeX 公式)
abstract: >-
  Abstract—Artificial Intelligence (AI) and Machine Learning
  (ML) are transforming industries worldwide and the telecom
  industry is no exception. Nowadays, AI/ML technologies have
  been applied in 5G systems, mostly in network automation and
  non-real-time functionalities such as energy savings, load balanc-
  ing, and mobility optimization. For future radio access networks,
  it is even more critical to investigate AI/ML applications in
  real-time processing, where the AI/ML-assisted channel state
  information (CSI) feedback has been one of the 3GPP Rel-18 rec-
  ommended use cases for AI-native radio access networks (RAN).
  In this paper, we investigate the feasibility and performance
  of a Transformer-based CSI feedback scheme on a general-
  purpose CPU platform. We also propose acceleration schemes for
  this Transformer model. Our experiment results show that our
  proposed optimization techniques such as operator fusion, weight
  pre-packing, and automatic precision conversion, together with
  the advanced matrix extension (AMX) hardware accelerator, can
  significantly reduce the inference latency by 46.8%. Our study
  also demonstrates that a general-purpose x86 CPU platform can
  support the real-time inference of AI models in 5G vRAN. In
  comparison to the GPU platform, we demonstrate that the CPU
  platform with hardware accelerator and software optimizations
  can achieve comparable AI/ML inference performance; in small
  batch size scenarios, the CPU platform can even outperform
  GPU.
  Index Terms—CSI feedback, AI/ML, Transformer, General-
  purpose CPU, vRAN.

# 封面图片 (可选)
cover:          

# 作者列表 (支持特殊标记)
authors:
  - Jieting Xiao
  - Yilun Jiang
  - Pengpeng Song
  - Xiaojun Hei


# 链接按钮 (自动生成对应的按钮)
links:
  Paper: https://www.overleaf.com/project/67ac832acec90268eb9109ca
---