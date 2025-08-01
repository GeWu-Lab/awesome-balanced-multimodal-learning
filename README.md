# Balanced Multimodal Learning
A curated list of balanced multimodal learning methods.

# News
We have a discussion group about balanced multimodal learning. Anyone who may be interested is welcome! If the QR code expires, please add us on WeChat (ID: weike0409) and include a note saying “BML community.”
 
<img src="IMG_0918.JPG"  width="200" />

You are also welcome to join our Slack workspace: https://join.slack.com/t/balancedmulti-mhs9373/shared_invite/zt-3aj46comq-CNWrkqqGI9Z2kNn64aU9FQ

# Table of contents
- [Balanced Multimodal Learning](#balanced-multimodal-learning)
- [News](#news)
- [Table of contents](#table-of-contents)
  - [GeWu-Lab paper](#gewu-lab-paper)
  - [Other balanced multimodal learning methods](#other-balanced-multimodal-learning-methods)
  - [Methodology Classification (Refer to the paper BalanceBenchmark)](#methodology-classification-refer-to-the-paper-balancebenchmark)
    - [Data](#data)
    - [Feed-forward](#feed-forward)
    - [Objective](#objective)
    - [Optimization](#optimization)



## GeWu-Lab paper
**[CVPR-2022]**
<br>
[Balanced Multimodal Learning via On-the-fly Gradient Modulation](https://openaccess.thecvf.com/content/CVPR2022/papers/Peng_Balanced_Multimodal_Learning_via_On-the-Fly_Gradient_Modulation_CVPR_2022_paper.pdf) 
<br>
**[Code](https://github.com/GeWu-Lab/OGM-GE_CVPR2022)**

**[ICASSP-2023]**
<br>
[MMCosine: Multi-Modal Cosine Loss Towards Balanced Audio-Visual Fine-Grained Learning](https://arxiv.org/abs/2303.05338) 
<br>
**[Code](https://github.com/GeWu-Lab/MMCosine_ICASSP23)**

**[ICLR-2024]**
<br>
[Quantifying and Enhancing Multi-modal Robustness with Modality Preference](https://arxiv.org/abs/2402.06244) 
<br>
**[Code](https://github.com/GeWu-Lab/Certifiable-Robust-Multi-modal-Training)**

**[CVPR-2024]**
<br>
[Enhancing Multimodal Cooperation via Sample-level Modality Valuation](https://arxiv.org/abs/2309.06255) 
<br>
**[Code](https://github.com/GeWu-Lab/Valuate-and-Enhance-Multimodal-Cooperation)**

**[ICML-2024]**
<br>
[MMPareto: Boosting Multimodal Learning with Innocent Unimodal Assistance](https://arxiv.org/abs/2405.17730) 
<br>
**[Code](https://github.com/GeWu-Lab/MMPareto_ICML2024)**


**[ECCV-2024]**
<br>
[Diagnosing and Re-learning for Balanced Multimodal Learning](https://arxiv.org/abs/2407.09705) 
<br>
**[Code](https://github.com/GeWu-Lab/Diagnosing_Relearning_ECCV2024)**

**[CVPR-2025]**
<br>
[Adaptive Unimodal Regulation for Balanced Multimodal Information Acquisition](https://arxiv.org/abs/2503.18595) 
<br>
**[Code](https://github.com/GeWu-Lab/InfoReg_CVPR2025)**


## Other balanced multimodal learning methods

- [What Makes Training Multi-Modal Classification Networks Hard?](https://arxiv.org/abs/1905.12681) [CVPR 2020]
- [Learning to Balance the Learning Rates between Various Modalities via Adaptive Tracking Factor](https://ieeexplore.ieee.org/document/9503315) [IEEE Signal Processing Letters  2021]
- [Audiovisual SlowFast Networks for Video Recognition](https://arxiv.org/abs/2001.08740) [arXiv 2020]
- [Joint Audio-Visual Deepfake Detection](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_Joint_Audio-Visual_Deepfake_Detection_ICCV_2021_paper.pdf) [ICCV 2021]
- [Delving into Deep Imbalanced Regression](https://arxiv.org/abs/2102.09554) \[ICML2021]
- [Characterizing and Overcoming the Greedy Nature of Learning in Multi-modal Deep Neural Networks](https://proceedings.mlr.press/v162/wu22d/wu22d.pdf) [ICML 2022]
- [MCL: A Contrastive Learning Method for Multimodal Data Fusion in Violence Detection](https://ieeexplore.ieee.org/document/9976192) [IEEE Signal Processing Letters 2022]
- [Balanced MSE for Imbalanced Visual Regression](https://openaccess.thecvf.com/content/CVPR2022/html/Ren_Balanced_MSE_for_Imbalanced_Visual_Regression_CVPR_2022_paper.html)[CVPR2022]
- [On Uni-Modal Feature Learning in Supervised Multi-Modal Learning](https://proceedings.mlr.press/v202/du23e/du23e.pdf) [ICML 2023]
- [Calibrating Multimodal Learning](https://proceedings.mlr.press/v202/ma23i.html) [ICML 2023]
- [Multimodal Pre-Training with Self-Distillation for Product Understanding in E-Commerce](https://dl.acm.org/doi/10.1145/3539597.3570423) [WSDM 2023]
- [PMR: Prototypical Modal Rebalance for Multimodal Learning](https://openaccess.thecvf.com/content/CVPR2023/papers/Fan_PMR_Prototypical_Modal_Rebalance_for_Multimodal_Learning_CVPR_2023_paper.pdf) [CVPR 2023]
- [Graph Interactive Network with Adaptive Gradient for Multi-Modal Rumor Detection](https://dl.acm.org/doi/abs/10.1145/3591106.3592250) [ICMR 2023]
- [Multimodal Imbalance-Aware Gradient Modulation for Weakly-supervised Audio-Visual Video Parsing](https://arxiv.org/abs/2307.02041) [IEEE Transactions on Circuits and Systems for Video Technology 2023]
- [Multimodal Temporal Attention in Sentiment Analysis](https://dl.acm.org/doi/10.1145/3551876.3554811) [MuSe 2023]
- [Utilizing Greedy Nature for Multimodal Conditional Image Synthesis in Transformers](https://ieeexplore.ieee.org/document/10184483) [TMM 2023]
- [Variational Probabilistic Fusion Network for RGB-T Semantic Segmentation](https://arxiv.org/abs/2307.08536) [arXiv 2023]
- [Boosting Multi-modal Model Performance with Adaptive Gradient Modulation](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Boosting_Multi-modal_Model_Performance_with_Adaptive_Gradient_Modulation_ICCV_2023_paper.html) [ICCV 2023]
- [Adaptive Mask Co-Optimization for Modal Dependence in Multimodal Learning](https://ieeexplore.ieee.org/document/10096641) [ICASSP 2024]
- [Improving Multimodal Learning with Multi-Loss Gradient Modulation](https://arxiv.org/abs/2405.07930) [arXiv 2024]
- [Learning to Rebalance Multi-Modal Optimization by Adaptively Masking Subnetworks](https://arxiv.org/abs/2404.08347) [arXiv 2024]
- [Suppress and Rebalance: Towards Generalized Multi-Modal Face Anti-Spoofing](https://openaccess.thecvf.com/content/CVPR2024/html/Lin_Suppress_and_Rebalance_Towards_Generalized_Multi-Modal_Face_Anti-Spoofing_CVPR_2024_paper.html) [CVPR 2024]
- [C2KD: Bridging the Modality Gap for Cross-Modal Knowledge Distillation](https://openaccess.thecvf.com/content/CVPR2024/html/Huo_C2KD_Bridging_the_Modality_Gap_for_Cross-Modal_Knowledge_Distillation_CVPR_2024_paper.html) [CVPR 2024]
 - [Multimodal Representation Learning by Alternating Unimodal Adaptation](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_Multimodal_Representation_Learning_by_Alternating_Unimodal_Adaptation_CVPR_2024_paper.html) [CVPR 2024]
- [Balanced Multi-modal Federated Learning via Cross-Modal Infiltration](https://arxiv.org/abs/2401.00894) [arXiv 2024]
- [Balancing Multimodal Learning via Online Logit Modulation](#) [IJCAI 2024]
- [Enhancing Unimodal Features Matters: A Multimodal Framework for Building Extraction](https://ieeexplore.ieee.org/abstract/document/10507075?casa_token=av_OHUr3Bf8AAAAA:C2AQ5u6QzAVsapGKcq2xdhykxnCpZea9dByuwkgdc1eHJSap8MQp5RYv2fD1Mdw7H4HZrKMhAXI) [TGRS 2024]
- [Suppress and Rebalance: Towards Generalized Multi-Modal Face Anti-Spoofing](https://openaccess.thecvf.com/content/CVPR2024/html/Lin_Suppress_and_Rebalance_Towards_Generalized_Multi-Modal_Face_Anti-Spoofing_CVPR_2024_paper.html) \[CVPR 2024]
- [Understanding Unimodal Bias in Multimodal Deep Linear Networks](https://arxiv.org/abs/2312.00935) \[ICML 2024]
- [Facilitating Multimodal Classification via Dynamically Learning Modality Gap](https://proceedings.neurips.cc/paper_files/paper/2024/hash/71b17f00017da0d73823ccf7fbce2d4f-Abstract-Conference.html) \[NIPS 2024]
- [Ada2I: Enhancing Modality Balance for Multimodal Conversational Emotion Recognition](https://arxiv.org/abs/2408.12895) \[ACM MM 2024]
- [Modality-Balanced Learning for Multimedia Recommendation](https://arxiv.org/abs/2408.06360) \[ACM MM 2024]
- [ReconBoost: Boosting Can Achieve Modality Reconcilement.](https://arxiv.org/pdf/2405.09321) \[ICML 2024]
- [Classifier-guided Gradient Modulation for Enhanced Multimodal Learning](https://arxiv.org/abs/2411.01409) \[arXiv 2024]
- [DynCIM: Dynamic Curriculum for Imbalanced Multimodal Learning](http://arxiv.org/abs/2503.06456) \[arXiv 2025]
- [Rethinking Multimodal Learning from the Perspective of Mitigating Classification Ability Disproportion](https://arxiv.org/abs/2502.20120) \[arXiv 2025]

## Methodology Classification (Refer to the paper [BalanceBenchmark](https://arxiv.org/abs/2502.10816))

### Data  
---
- [Enhancing Multimodal Cooperation via Sample-level Modality Valuation](https://arxiv.org/abs/2309.06255) [CVPR 2024]

### Feed-forward
---
- [Multimodal Representation Learning by Alternating Unimodal Adaptation](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_Multimodal_Representation_Learning_by_Alternating_Unimodal_Adaptation_CVPR_2024_paper.html) [CVPR 2024]
- [Characterizing and Overcoming the Greedy Nature of Learning in Multi-modal Deep Neural Networks](https://proceedings.mlr.press/v162/wu22d/wu22d.pdf) [ICML 2022]
- [Adaptive Mask Co-Optimization for Modal Dependence in Multimodal Learning](https://ieeexplore.ieee.org/document/10096641) [ICASSP 2024]


### Objective
---
- [MMCosine: Multi-Modal Cosine Loss Towards Balanced Audio-Visual Fine-Grained Learning](https://arxiv.org/abs/2303.05338) [ICASSP 2023]
- [On Uni-Modal Feature Learning in Supervised Multi-Modal Learning](https://proceedings.mlr.press/v202/du23e/du23e.pdf) [ICML 2023]
- [Multimodal Pre-Training with Self-Distillation for Product Understanding in E-Commerce](https://dl.acm.org/doi/10.1145/3539597.3570423) [WSDM 2023]
- [Calibrating Multimodal Learning](https://proceedings.mlr.press/v202/ma23i.html) [ICML 2023]
- [MMPareto: Boosting Multimodal Learning with Innocent Unimodal Assistance](https://arxiv.org/abs/2405.17730) [ICML 2024]
- [What Makes Training Multi-Modal Classification Networks Hard?](https://arxiv.org/abs/1905.12681) [CVPR 2020]
- [Facilitating Multimodal Classification via Dynamically Learning Modality Gap](https://proceedings.neurips.cc/paper_files/paper/2024/hash/71b17f00017da0d73823ccf7fbce2d4f-Abstract-Conference.html) \[NIPS 2024]


### Optimization
---
- [Balanced Multimodal Learning via On-the-fly Gradient Modulation](https://openaccess.thecvf.com/content/CVPR2022/papers/Peng_Balanced_Multimodal_Learning_via_On-the-Fly_Gradient_Modulation_CVPR_2022_paper.pdf) [CVPR2022]
- [Boosting Multi-modal Model Performance with Adaptive Gradient Modulation](https://openaccess.thecvf.com/content/ICCV2023/html/Li_Boosting_Multi-modal_Model_Performance_with_Adaptive_Gradient_Modulation_ICCV_2023_paper.html) [ICCV 2023]
- [PMR: Prototypical Modal Rebalance for Multimodal Learning](https://openaccess.thecvf.com/content/CVPR2023/papers/Fan_PMR_Prototypical_Modal_Rebalance_for_Multimodal_Learning_CVPR_2023_paper.pdf) [CVPR 2023]
- [Diagnosing and Re-learning for Balanced Multimodal Learning](https://arxiv.org/abs/2407.09705) [ECCV2024]
- [ReconBoost: Boosting Can Achieve Modality Reconcilement.](https://arxiv.org/pdf/2405.09321) \[ICML 2024]




