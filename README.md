# 多模态医学影像癌症生存预测 - 文献综述

> 持续更新多模态医学影像与癌症生存预测相关论文

---

## 病理图像 + CT/影像融合

| 论文 | 年份 | 作者 | 核心内容 |
|------|------|------|----------|
| **Handling Missing Modalities in Multimodal Survival Prediction** | 2026 | Ruffini et al. | CT + WSI +临床数据的融合，首次实现中间层融合，在CT缺失时自动降权 |
| **CrossFusion: Multi-Scale Cross-Attention Fusion** | 2025 | Soraki et al. | 多尺度WSI特征融合，跨放大倍数信息交互 |
| **Opportunistic Screening for Pancreatic Cancer** | 2025 | Le et al. | CT + 影像报告融合预测胰腺癌生存风险 |

---

## 病理图像 + 基因组学融合

| 论文 | 年份 | 作者 | 核心内容 |
|------|------|------|----------|
| **Pathomic Fusion** | 2019 | Chen et al. | 经典工作！病理图像+基因组融合，使用Kronecker product + attention |
| **MoME: Mixture of Multimodal Experts** | 2024 | Xiong et al. | 双向渐进编码(BPE) + 多模态专家选择 |
| **PGHG: Pathology-Genome Heterogeneous Graph** | 2024 | Zhang et al. | 异构图神经网络融合病理与转录组 |
| **TTMFN: Two-stream Transformer** | 2023 | Ge et al. | 双流Transformer + 模态内/间注意力 |
| **Cross-modality Attention** | 2023 | Deng et al. | NSCLC病理图像+RNA-seq融合，c-index 0.6587 |

---

## 推荐阅读

### 入门必读：Pathomic Fusion
- **arXiv**: [1912.08937](https://arxiv.org/abs/1912.08937)
- 这是该方向的奠基性工作
- 提出了使用Kronecker product进行特征交互
- 引入门控注意力机制控制各模态的表达能力

### 最新SOTA：MoME
- **arXiv**: [2406.09696](https://arxiv.org/abs/2406.09696)
- 2024年最新方法
- 双向渐进编码解决模态异质性
- 动态选择专家适应不同场景

---

## 更新日志

- **2026-03-27**: 初始化仓库，添加初始文献列表