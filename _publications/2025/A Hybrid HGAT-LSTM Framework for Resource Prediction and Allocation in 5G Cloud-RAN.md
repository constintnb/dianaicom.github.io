---
title:          "A Hybrid HGAT-LSTM Framework for Resource Prediction and Allocation in 5G Cloud-RAN"
date:           2025-11-26
selected:       true                        # 设置为 true 会在首页“精选论文”中显示
pub:            "Asia-Pacific Conference on Communications (APCC2025)"
pub_date:       "2025"                      # 显示在会议名后面的年份
#pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>' # 可选：添加徽章 (Oral, Spotlight, Best Paper)

# 引用计数 (可选)
#semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776

# 摘要 (支持 HTML 和 LaTeX 公式)
abstract: >-
  Abstract—In the 5G Cloud-RAN (C-RAN), efficient allocationof computing 
  resources across data centers and edge computingenvironments has become a 
  critical challenge for optimizingnetwork performance. Traditional strategies 
  fail to adapt tothe dynamic resource demands of the wireless network nodes,resulting 
  in low resource utilization, load imbalance, and energywaste. In this paper, we propose 
  a dynamic resource predictionand allocation framework based on a deep integration 
  ofHeterogeneous Graph Attention Network (HGAT) and LongShort-Term Memory (LSTM) networks. 
  The framework firstemploys an HGAT to model the topological dependencies amongheterogeneous 
  nodes in C-RAN, capturing spatial structuralcharacteristics. Subsequently, we integrate 
  node-type-specificLSTM modules to model long-term temporal evolution trends.Experimental 
  results demonstrate that, across local cloud, edgecloud, and central cloud C-RAN deployment 
  scenarios, theproposed framework significantly outperforms traditional staticallocation 
  strategies and existing AI-based approaches. Specifically, it achieves higher resource 
  prediction accuracy acrossvarious test scenarios; enhanced load balancing, evidenced 
  by a 6.8%–57.8% reduction in CPU utilization variance; hightraining efficiency, converging 
  in as few as 5 iterations with fewerthan 100 samples; superior inference efficiency relative 
  to othercomposite models, maintaining stable latency across differentnetwork scales; 
  and lower energy consumption, with reductionsranging from 19% to 25%. Moreover, by 
  leveraging theseaccurate predictions, our framework further enhances systemthroughput 
  by 7.5%–14.5%. This study may provide a feasible,accurate, and efficient framework for 
  resource prediction andbalanced scheduling in dynamic 5G C-RAN environments.
  Index Terms—5G; C-RAN; Graph Neural Networks; LongShort-term Memory Networks; Computing Resource Allocation

# 封面图片 (可选)
cover:          /assets/images/covers/paper1.jpg

# 作者列表 (支持特殊标记)
authors:
  - Leyu Zhao
  - Yuehan Liu
  - Di Liu
  - Xiaojun Hei


# 链接按钮 (自动生成对应的按钮)
links:
  Paper: https://hustdian.feishu.cn/file/TRp2b9VLWo3U1ixAyftcSKQfnPd
---