# 📊Awesome-Multi-View-Representation-Learning✨
This repo aggregates state-of-the-art papers, code implementations, benchmark datasets, surveys, and tools to facilitate research, development, and education in Multi-view Representation Learning.  

According to key learning paradigms and data characteristics, these methods are further categorized into several directions:
- 🔥Unsupervised/Self-supervised Multi-view Representation Learning (e.g., cross-view alignment, contrastive learning for unified embeddings)
- 🏛️Supervised/Weakly-supervised Multi-view Representation Learning (e.g., label-guided cross-modal fusion, multi-source feature aggregation)
- 🐾Multi-modal Representation Learning (e.g., vision-text, audio-visual, sensor-data fusion)

🖖We warmly welcome other participants to share their related papers and codes. 🌟If you are interested or have any questions about the listed resources, please feel free to contact us at pengyuanli@bjtu.edu.cn.🚀
If you find this repository useful for your research or work, we would greatly appreciate it if you could star this repository.⭐ 


## Catalogue
- 🏊[What's Multi-view Representation Learning?](#jump1) 
- 📑[Surveys](#jump2) 
- 📚[Papers & Codes & Notes](#jump3)
- 📁[Datasets](#jump4)
- 🏷️[Citation](#jump5)

--------------

## <span id="jump1">🏊What's Multi-view Representation Learning?</span>
Multi-view Representation Learning aims to capture the potential correlations, complementarity, and consistency among multiple features or modalities, and finally learn unified, robust representations through diverse learning strategies (e.g., supervised, unsupervised, self-supervised) combined with models like deep neural networks, which can support downstream tasks such as classification, clustering, and prediction.


## <span id="jump2">📑Surveys</span>
> ⚠️ Important Note ⚠️
> The impact factors and literature sources in the "Notes" are likely to contain errors due to personal limitations in information collection and collation. These details are provided for reference ONLY and must NOT be used directly for academic citations, formal research, or any critical applications. Please verify all data independently before relying on it.

| Year | Title | Abbreviation | Conference/Journal | Paper | Code | Note |
|------|------|------|-----------|----------|----------|------|
| 2025 | **LLM-DAMVC：A Large Language Model Assisted Dynamic Agent for Multi-View Clustering** | **LLM-DAMVC** | NeurIPS | [![](https://img.shields.io/badge/-paper-blue)](https://openreview.net/attachment?id=xgiMK8FtSI&name=pdf) | - | [![](https://img.shields.io/badge/-note-green)](./Notes/LLM-DAMVC.pdf) |
| 2025 | **Federated Incomplete Multi-view Clustering with Globally Fused Graph Guidance** | **FIMCFG** | ICML | [![](https://img.shields.io/badge/-paper-blue)](https://openreview.net/pdf?id=7qvYLnJDRd) | [![](https://img.shields.io/badge/-code-red)](https://github.com/PaddiHunter/FIMCFG) | - |
| 2025 | **PROTOCOL: Partial Optimal Transport-enhanced Contrastive Learning for Imbalanced Multi-view Clustering** | **PROTOCOL** | ICML | [![](https://img.shields.io/badge/-paper-blue)](https://openreview.net/pdf?id=Pm8LUCx6Mb) | [![](https://img.shields.io/badge/-code-red)](https://github.com/Scarlett125/PROTOCOL) | - |
| 2025 | **A Hubness Perspective on Representation Learning for Graph-Based Multi-View Clustering** | **hubREP** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](https://openaccess.thecvf.com/content/CVPR2025/![](https://img.shields.io/badge/-paper-blue)s/Xu_A_Hubness_Perspective_on_Representation_Learning_for_Graph-Based_Multi-View_Clustering_CVPR_2025_![](https://img.shields.io/badge/-paper-blue).pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/zmxu196/hubREP) | [![](https://img.shields.io/badge/-note-green)](./Notes/hubREP.pdf) |
| 2025 | **ROLL: Robust Noisy Pseudo-label Learning for Multi-View Clustering with Noisy Correspondence** | **ROLL** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](https://openaccess.thecvf.com/content/CVPR2025/![](https://img.shields.io/badge/-paper-blue)s/Sun_ROLL_Robust_Noisy_Pseudo-label_Learning_for_Multi-View_Clustering_with_Noisy_CVPR_2025_![](https://img.shields.io/badge/-paper-blue).pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/sunyuan-cs/2025-CVPR-ROLL) | - |
| 2025 | **DFL-Net: Disentangled Feature Learning Network for Multi-view Clustering** | **DFL-Net** | TKDE | [![](https://img.shields.io/badge/-paper-blue)](https://ieeexplore.ieee.org/abstract/document/11034651/) | [![](https://img.shields.io/badge/-code-red)](https://github.com/chenzhe207/DFL-NET) | - |
| 2025 | **Multigranularity Information Fused Contrastive Learning With Multiview Clustering** | **MGCMVC** | TNNLS | [![](https://img.shields.io/badge/-paper-blue)](https://ieeexplore.ieee.org/abstract/document/11030281/) | [![](https://img.shields.io/badge/-code-red)](https://github.com/Luyangabc/MGCMVC) | [![](https://img.shields.io/badge/-note-green)](./Notes/MGCMVC.pdf) |
| 2025 | **MASTER: A Multi-granularity Invariant Structure Clustering Scheme for Multi-view Clustering** | **MASTER** | IJCAI | [![](https://img.shields.io/badge/-paper-blue)](https://ijcai-preprints.s3.us-west-1.amazonaws.com/2025/4274.pdf) | - | - |
| 2025 | **Multi-aspect Self-guided Deep Information Bottleneck for Multi-modal Clustering** | **MSDIB** | AAAI | [![](https://img.shields.io/badge/-paper-blue)](https://ojs.aaai.org/index.php/AAAI/article/view/33903/36058) | [![](https://img.shields.io/badge/-code-red)](https://github.com/ShizheHu/AAAI25_![](https://img.shields.io/badge/-code-red)_MSDIB) | - |
| 2025 | **Multi-view Granular-ball Contrastive Clustering** | **MGBCC** | AAAI | [![](https://img.shields.io/badge/-paper-blue)](https://ojs.aaai.org/index.php/AAAI/article/view/34274) | [![](https://img.shields.io/badge/-code-red)](https://github.com/Duo-laimi/mgbcc_main) | - |
| 2025 | **Selective Contrastive Learning for Unpaired Multi-View Clustering** | **scl-UMC** | TNNLS | [![](https://img.shields.io/badge/-paper-blue)](https://ieeexplore.ieee.org/document/10327758/) | - | - |
| 2025 | **Learning Uniform Latent Representation via Alternating Adversarial Network for Multi-View Clustering** | **Deep-A2MC** | TETCI | [![](https://img.shields.io/badge/-paper-blue)](https://ieeexplore.ieee.org/document/10909256/) | - | - |
| 2025 | **Imputation-free and Alignment-free: Incomplete Multi-view Clustering Driven by Consensus Semantic Learning** | **FreeCSL** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](https://openaccess.thecvf.com/content/CVPR2025/![](https://img.shields.io/badge/-paper-blue)s/Dai_Imputation-free_and_Alignment-free_Incomplete_Multi-view_Clustering_Driven_by_Consensus_Semantic_CVPR_2025_![](https://img.shields.io/badge/-paper-blue).pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/zoyadai/2025_CVPR_FreeCSL) | - |
| 2025 | **Selective Cross-view Topology for Deep Incomplete Multi-view Clustering** | **SCVT** | TIP | [![](https://img.shields.io/badge/-paper-blue)](https://ieeexplore.ieee.org/abstract/document/11091516/) | [![](https://img.shields.io/badge/-code-red)](https://github.com/dzboop/SCVT) | - |
| 2024 | **Bridging Gaps: Federated Multi-View Clustering in Heterogeneous Hybrid Views** | **FMCSC** | NeurIPS | [![](https://img.shields.io/badge/-paper-blue)](https://arxiv.org/pdf/2410.09484) | [![](https://img.shields.io/badge/-code-red)](https://github.com/5Martina5/FMCSC) | ![](https://img.shields.io/badge/-note-green)](./Notes/FMCSC.pdf) |
| 2024 | **Robust Contrastive Multi-view Clustering against Dual Noisy Correspondence** | **CANDY** | NeurIPS | [![](https://img.shields.io/badge/-paper-blue)](https://openreview.net/pdf?id=6OvTbDClUn) | [![](https://img.shields.io/badge/-code-red)](https://github.com/XLearning-SCU/2024-NeurIPS-CANDY) | - |
| 2024 | **Rethinking Multi-view Representation Learning via Distilled Disentangling** | **MRDD** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](https://arxiv.org/abs/2403.10897) | [![](https://img.shields.io/badge/-code-red)](https://github.com/Guanzhou-Ke/MRDD) | - |
| 2024 | **Differentiable Information Bottleneck for Deterministic Multi-view Clustering** | **DIB** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](https://arxiv.org/abs/2403.15681) | - | - |
| 2024 | **Learning Common Semantics via Optimal Transport for Contrastive Multi-view Clustering** | **CSOT** | TIP | [![](https://img.shields.io/badge/-paper-blue)](https://research.edgehill.ac.uk/files/93038512/TIP_MVC_Final.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/vsislab/CSOT_MVC) | - |
| 2024 | **Dual Contrast-Driven Deep Multi-View Clustering** | **DCMVC** | TIP | [![](https://img.shields.io/badge/-paper-blue)](https://ieeexplore.ieee.org/abstract/document/10648641/) | [![](https://img.shields.io/badge/-code-red)](https://github.com/tweety1028/DCMVC) | - |
| 2024 | **Simple Contrastive Multi-View Clustering with Data-Level Fusion** | **SCM** | IJCAI | [![](https://img.shields.io/badge/-paper-blue)](https://www.ijcai.org/proceedings/2024/0519.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/SubmissionsIn/SCM) | - |
| 2024 | **SURER: Structure-Adaptive Unified Graph Neural Network for Multi-View Clustering** | **SURER** | AAAI | [![](https://img.shields.io/badge/-paper-blue)](https://ojs.aaai.org/index.php/AAAI/article/view/29478/30785) | [![](https://img.shields.io/badge/-code-red)](https://github.com/Wjing-bjtu/SURER) | - |
| 2024 | **Heterogeneity-Aware Federated Deep Multi-View Clustering towards Diverse Feature Representations** | **HFMVC** | ACM MM | [![](https://img.shields.io/badge/-paper-blue)](https://openreview.net/pdf?id=3fgY4qOhoO) | [![](https://img.shields.io/badge/-code-red)](https://github.com/xiaorui-jiang/HFMVC) | - |
| 2024 | **Learning Dual Enhanced Representation for Contrastive Multi-view Clustering** | **LUCE-CMC** | ACM MM | [![](https://img.shields.io/badge/-paper-blue)](https://openreview.net/pdf?id=8uTMi4dQFK) | [![](https://img.shields.io/badge/-code-red)](https://github.com/ShizheHu/ACMMM24_![](https://img.shields.io/badge/-code-red)_LUCE-CMC) | - |
| 2024 | **Robust Variational Contrastive Learning for Partially View-unaligned Clustering** | **VITAL** | ACM MM | [![](https://img.shields.io/badge/-paper-blue)](https://openreview.net/pdf?id=eZpm234cw2) | [![](https://img.shields.io/badge/-code-red)](https://github.com/He-Changhao/2024-MM-VITAL) | - |
| 2024 | **Self-Weighted Contrastive Fusion for Deep Multi-View Clustering** | **SCMVC** | TMM | [![](https://img.shields.io/badge/-paper-blue)](https://ieeexplore.ieee.org/abstract/document/10499831/) | [![](https://img.shields.io/badge/-code-red)](https://github.com/SongwuJob/SCMVC) | - |
| 2024 | **Incomplete Contrastive Multi-View Clustering with High-Confidence Guiding** | **ICMVC** | AAAI | [![](https://img.shields.io/badge/-paper-blue)](https://ojs.aaai.org/index.php/AAAI/article/download/29000/29899) | [![](https://img.shields.io/badge/-code-red)](https://github.com/hannaiiyanggit/MCMVC?tab=readme-ov-file#view-labels-are-important-a-multifacet-complementarity-study-of-deep-multi-view-clustering) | - |
| 2024 | **Decoupled Contrastive Multi-view Clustering with High-order Random Walks** | **DIVIDE** | AAAI | [![](https://img.shields.io/badge/-paper-blue)](https://ojs.aaai.org/index.php/AAAI/article/download/29330/30509) | [![](https://img.shields.io/badge/-code-red)](https://github.com/XLearning-SCU/2024-AAAI-DIVIDE) | [![](https://img.shields.io/badge/-note-green)](./Notes/DIVIDE.pdf) |
| 2024 | **Robust Prototype Completion for Incomplete Multi-view Clustering** | **RPCIC** | ACM MM | [![](https://img.shields.io/badge/-paper-blue)](https://openreview.net/pdf?id=4BrIZo3Ave) | [![](https://img.shields.io/badge/-code-red)](https://github.com/hl-yuan/RPCIC) | - |
| 2024 | **A novel Federated Multi-view Clustering Method for Unaligned and Incomplete Data Fusion** | **FUCIF** | IF | [![](https://img.shields.io/badge/-paper-blue)](https://www.sciencedirect.com/science/article/pii/S1566253524001350) | [![](https://img.shields.io/badge/-code-red)](https://github.com/5Martina5/FCUIF) | - |
| 2023 | **Triple-granularity contrastive learning for deep multi-view subspace clustering** | **TRUST** | ACM MM | [![](https://img.shields.io/badge/-paper-blue)](https://dl.acm.org/doi/10.1145/3581783.3611844) | - | - |
| 2023 | **Self-Weighted Contrastive Learning among Multiple Views for Mitigating Representation Degeneration** | **SEM** | NeurIPS | [![](https://img.shields.io/badge/-paper-blue)](https://proceedings.neurips.cc/![](https://img.shields.io/badge/-paper-blue)_files/![](https://img.shields.io/badge/-paper-blue)/2023/file/03b13b0db740b95cb741e007178ef5e5-![](https://img.shields.io/badge/-paper-blue)-Conference.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/SubmissionsIn/SEM/archive/refs/heads/main.zip) | - |
| 2023 | **Cross-view Topology Based Consistent and Complementary Information for Deep Multi-view Clustering** | **CTCC** | ICCV | [![](https://img.shields.io/badge/-paper-blue)](https://openaccess.thecvf.com/content/ICCV2023/![](https://img.shields.io/badge/-paper-blue)s/Dong_Cross-view_Topology_Based_Consistent_and_Complementary_Information_for_Deep_Multi-view_ICCV_2023_![](https://img.shields.io/badge/-paper-blue).pdf) | - | [![](https://img.shields.io/badge/-note-green)](./Notes/CTCC.pdf) |
| 2023 | **Deep Multiview Clustering by Contrasting Cluster Assignments** | **CVCL** | ICCV | [![](https://img.shields.io/badge/-paper-blue)](https://arxiv.org/pdf/2304.10769) | [![](https://img.shields.io/badge/-code-red)](https://github.com/chenjie20/CVCL/) | [![](https://img.shields.io/badge/-note-green)](./Notes/CVCL.pdf) |
| 2023 | **DealMVC: Dual Contrastive Calibration for Multi-view Clustering** | **DealMVC** | ACM MM | [![](https://img.shields.io/badge/-paper-blue)](https://arxiv.org/pdf/2308.09000) | [![](https://img.shields.io/badge/-code-red)](https://github.com/xihongyang1999/DealMVC) | [![](https://img.shields.io/badge/-note-green)](./Notes/DealMVC.pdf) |
| 2023 | **On the Effects of Self-supervision and Contrastive Alignment in Deep Multi-view Clustering** | **DeepMVC** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](http://openaccess.thecvf.com/content/CVPR2023/![](https://img.shields.io/badge/-paper-blue)s/Trosten_On_the_Effects_of_Self-Supervision_and_Contrastive_Alignment_in_Deep_CVPR_2023_![](https://img.shields.io/badge/-paper-blue).pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/DanielTrosten/DeepMVC) | - |
| 2023 | **GCFAgg：Global and Cross-view Feature Aggregation for Multi-view Clustering** | **GCFAgg** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](https://openaccess.thecvf.com/content/CVPR2023/![](https://img.shields.io/badge/-paper-blue)s/Yan_GCFAgg_Global_and_Cross-View_Feature_Aggregation_for_Multi-View_Clustering_CVPR_2023_![](https://img.shields.io/badge/-paper-blue).pdf) | - | [![](https://img.shields.io/badge/-note-green)](./Notes/GCFAgg.pdf) |
| 2023 | **Federated Deep Multi-View Clustering with Global Self-Supervision** | **FedDMVC** | ACM MM | [![](https://img.shields.io/badge/-paper-blue)](https://arxiv.org/pdf/2309.13697) | - | - |
| 2023 | **Semantic Invariant Multi-View Clustering With Fully Incomplete Information** | **SMILE** | TPAMI | [![](https://img.shields.io/badge/-paper-blue)](https://ieeexplore.ieee.org/abstract/document/10319403/) | [![](https://img.shields.io/badge/-code-red)](https://github.com/PengxinZeng/2023-TPAMI-SMILE) | - |
| 2023 | **Deep Incomplete Multi-view Clustering with Cross-view Partial Sample and Prototype Alignment** | **CPSPAN** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](http://openaccess.thecvf.com/content/CVPR2023/![](https://img.shields.io/badge/-paper-blue)s/Jin_Deep_Incomplete_Multi-View_Clustering_With_Cross-View_Partial_Sample_and_Prototype_CVPR_2023_![](https://img.shields.io/badge/-paper-blue).pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/jinjiaqi1998/CPSPAN) | - |
| 2023 | **Incomplete Multi-view Clustering via Prototype-based Imputation** | **ProImp** | IJCAI | [![](https://img.shields.io/badge/-paper-blue)](https://arxiv.org/pdf/2301.11045) | [![](https://img.shields.io/badge/-code-red)](https://github.com/XLearning-SCU/2023-IJCAI-ProImp) | [![](https://img.shields.io/badge/-note-green)](./Notes/ProImp.pdf) |
| 2022 | **Deep Safe Multi-View Clustering：Reducing the Risk of Clustering Performance Degradation Caused by View Increase** | **DSMVC** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](https://openaccess.thecvf.com/content/CVPR2022/![](https://img.shields.io/badge/-paper-blue)s/Tang_Deep_Safe_Multi-View_Clustering_Reducing_the_Risk_of_Clustering_Performance_CVPR_2022_![](https://img.shields.io/badge/-paper-blue).pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/Gasteinh/DSMVC) | - |
| 2022 | **Multi-level Feature Learning for Contrastive Multi-view Clustering** | **MFLVC** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](https://openaccess.thecvf.com/content/CVPR2022/![](https://img.shields.io/badge/-paper-blue)s/Xu_Multi-Level_Feature_Learning_for_Contrastive_Multi-View_Clustering_CVPR_2022_![](https://img.shields.io/badge/-paper-blue).pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/SubmissionsIn/MFLVC) | - |
| 2022 | **Stationary Diffusion State Neural Estimation for Multiview Clustering** | **SDSNE** | AAAI | [![](https://img.shields.io/badge/-paper-blue)](https://www.aaai.org/AAAI22![](https://img.shields.io/badge/-paper-blue)s/AAAI-184.LiuC.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/kunzhan/SDSNE) | - |
| 2022 | **Robust Multi-view Clustering with Incomplete Information** | **SURE** | TPAMI | [![](https://img.shields.io/badge/-paper-blue)](https://ieeexplore.ieee.org/abstract/document/9723577/) | [![](https://img.shields.io/badge/-code-red)](https://github.com/XLearning-SCU/2022-TPAMI-SURE) | - |
| 2022 | **Dual Contrastive Prediction for Incomplete Multi-view Representation Learning** | **DCP** | TPAMI | [![](https://img.shields.io/badge/-paper-blue)](http://pengxi.me/wp-content/uploads/2022/08/DCP.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/XLearning-SCU/2021-CVPR-Completer) | - |
| 2022 | **Deep Safe Incomplete Multi-view Clustering: Theorem and Algorithm** | **DSIMVC** | ICML | [![](https://img.shields.io/badge/-paper-blue)](https://proceedings.mlr.press/v162/tang22c/tang22c.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/Gasteinh/DSIMVC) | - |
| 2022 | **Deep Incomplete Multi-view Clustering via Mining Cluster Complementarity** | **DIMVC** | AAAI | [![](https://img.shields.io/badge/-paper-blue)](https://ojs.aaai.org/index.php/AAAI/article/download/20856/20615) | [![](https://img.shields.io/badge/-code-red)](https://github.com/SubmissionsIn/DIMVC) | - |
| 2021 | **Reconsidering Representation Alignment for Multi-view Clustering** | **SiMVC&CoMVC** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](https://openaccess.thecvf.com/content/CVPR2021/![](https://img.shields.io/badge/-paper-blue)s/Trosten_Reconsidering_Representation_Alignment_for_Multi-View_Clustering_CVPR_2021_![](https://img.shields.io/badge/-paper-blue).pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/AllenWrong/mvc) | - |
| 2021 | **Multi-VAE: Learning Disentangled View-common and View-peculiar Visual Representations for Multi-view Clustering** | **Multi-VAE** | ICCV | [![](https://img.shields.io/badge/-paper-blue)](https://openaccess.thecvf.com/content/ICCV2021/![](https://img.shields.io/badge/-paper-blue)s/Xu_Multi-VAE_Learning_Disentangled_View-Common_and_View-Peculiar_Visual_Representations_for_Multi-View_ICCV_2021_![](https://img.shields.io/badge/-paper-blue).pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/SubmissionsIn/Multi-VAE) | - |
| 2021 | **Multi-view Contrastive Graph Clustering** | **MCGC** | NeurIPS | [![](https://img.shields.io/badge/-paper-blue)](https://proceedings.neurips.cc/![](https://img.shields.io/badge/-paper-blue)/2021/file/10c66082c124f8afe3df4886f5e516e0-![](https://img.shields.io/badge/-paper-blue).pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/panern/mcgc) | - |
| 2021 | **Self-supervised Discriminative Feature Learning for Deep Multi-view Clustering** | **SDMVC** | TKDE | [![](https://img.shields.io/badge/-paper-blue)](https://arxiv.org/pdf/2103.15069.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/SubmissionsIn/SDMVC) | - |
| 2021 | **Deep Multi-view Subspace Clustering with Unified and Discriminative Learning** | **DMSC-UDL** | TMM | [![](https://img.shields.io/badge/-paper-blue)](https://ieeexplore.ieee.org/abstract/document/9204408/) | [![](https://img.shields.io/badge/-code-red)](https://github.com/IMKBLE/DMSC-UDL) | [![](https://img.shields.io/badge/-note-green)](./Notes/DMSC-UDL.pdf) |
| 2021 | **COMPLETER: Incomplete Multi-view Clustering via Contrastive Prediction** | **COMPLETER** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](http://pengxi.me/wp-content/uploads/2021/03/2021CVPR-completer.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/XLearning-SCU/2021-CVPR-Completer) | - |
| 2020 | **End-to-End Adversarial-Attention Network for Multi-Modal Clustering** | **EAMC** | CVPR | [![](https://img.shields.io/badge/-paper-blue)](https://openaccess.thecvf.com/content_CVPR_2020/![](https://img.shields.io/badge/-paper-blue)s/Zhou_End-to-End_Adversarial-Attention_Network_for_Multi-Modal_Clustering_CVPR_2020_![](https://img.shields.io/badge/-paper-blue).pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/AllenWrong/mvc) | - |
| 2020 | **Multi-View Attribute Graph Convolution Networks for Clustering** | **MAGCN** | IJCAI | [![](https://img.shields.io/badge/-paper-blue)](https://www.ijcai.org/proceedings/2020/0411.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/IMKBLE/MAGCN) | - |
| 2020 | **Deep Embedded Multi-view Clustering with Collaborative Training** | **DEMVC** | IS | [![](https://img.shields.io/badge/-paper-blue)](https://arxiv.org/pdf/2007.13067.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/SubmissionsIn/DEMVC) | - |
| 2020 | **One2Multi Graph Autoen![](https://img.shields.io/badge/-code-red)r for Multi-view Graph Clustering** | **O2MVC** | WWW | [![](https://img.shields.io/badge/-paper-blue)](http://shichuan.org/doc/83.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/googlebaba/WWW2020-O2MAC) | - |
| 2020 | **DIMC-net：Deep Incomplete Multi-view Clustering Network** | **DIMC-net** | ACM MM | [![](https://img.shields.io/badge/-paper-blue)](https://dl.acm.org/doi/10.1145/3394171.3413807) | - | - |
| 2019 | **COMIC: Multi-view Clustering Without Parameter Selection** | **COMIC** | ICML | [![](https://img.shields.io/badge/-paper-blue)](http://proceedings.mlr.press/v97/peng19a/peng19a.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/limit-scu/2019-ICML-COMIC) | - |
| 2019 | **Deep Adversarial Multi-view Clustering Network** | **DAMC** | IJCAI | [![](https://img.shields.io/badge/-paper-blue)](https://www.researchgate.net/publication/334844473_Deep_Adversarial_Multi-view_Clustering_Network) | [![](https://img.shields.io/badge/-code-red)](https://github.com/IMKBLE/DAMC) | - |
| 2019 | **Multi-view Spectral Clustering Network** | **MvSCN** | IJCAI | [![](https://img.shields.io/badge/-paper-blue)](https://www.ijcai.org/Proceedings/2019/0356.pdf) | [![](https://img.shields.io/badge/-code-red)](https://github.com/limit-scu/2019-IJCAI-MvSCN) | - |
| 2018 | **Generalized Latent Multi-View Subspace Clustering** | **gLMSC** | TPAMI | [![](https://img.shields.io/badge/-paper-blue)](http://cic.tju.edu.cn/faculty/huqinghua/pdf/GeneralizedLatentMulti-ViewSubspaceClustering.pdf) | [![](https://img.shields.io/badge/-code-red)](http://cic.tju.edu.cn/faculty/zhangchangqing/![](https://img.shields.io/badge/-code-red).html) | - |
| 2018 | **Partial Multi-View Clustering via Consistent GAN** | **PVC-GAN** | ICDM | [![](https://img.shields.io/badge/-paper-blue)](https://drive.google.com/file/d/1RrVeq_FHkLSgltNd1bVfyaHhtIclV5ZG/view) | [![](https://img.shields.io/badge/-code-red)](https://github.com/IMKBLE/PVC-GAN) | - |



## <span id="jump4">📁Datasets</span>
Here's what we've got cooking in the data kitchen:
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px;'>100leaves.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>3sources.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>ALOI.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>ALOI100.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>Animal.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>AWA.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>BBC4view.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>BBCSport.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>Cifar10.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>Cifar100.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>CUB.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>COIL20.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>Caltech101-7.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>Caltech101-20.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>Caltech101.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>Citeseer.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>Flower17.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>MSRCV1.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>FMNIST.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>NGs.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>ORL.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>Prokaryotic.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>UCI-Digit.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>Handwritten.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>100Leaves.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>WebKB.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>MNIST-USPS.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>Scene15.mat</div></a>
- <a href='#'><div style='background-color: #00CED1; color: #ffffff; border-radius: 8px; padding: 12px 16px; width: 36px;'>LandUse-21.mat</div></a>





## <span id="jump5">🏷️Citation</span>
```
@inproceedings{li2025aemvc,
  author = {Li, Pengyuan and Liu, Man and Chang, Dongxia and Wang, Yiming and Kong, Zisen and Zhao, Yao},
  title = {AEMVC: Mitigate Imbalanced Embedding Space in Multi-view Clustering},
  year = {2025},
  isbn = {9798400720352},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3746027.3754697},
  doi = {10.1145/3746027.3754697},
  booktitle = {Proceedings of the 33rd ACM International Conference on Multimedia},
  pages = {6461–6470},
  numpages = {10},
  keywords = {deep multi-view clustering, feature activation, multi-view representation learning, redundancy},
  location = {Dublin, Ireland},
  series = {MM '25}
}

@article{li2025dcmvc,
  title={DCMVC: Dual contrastive multi-view clustering},
  author={Li, Pengyuan and Chang, Dongxia and Kong, Zisen and Wang, Yiming and Zhao, Yao},
  journal={Neurocomputing},
  volume={635},
  pages={129889},
  year={2025},
  publisher={Elsevier}
}
```



