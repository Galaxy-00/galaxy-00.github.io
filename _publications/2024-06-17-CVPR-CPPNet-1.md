---
title: "CPP-Net: Embracing Multi-Scale Feature Fusion into Deep Unfolding CP-PPA Network for Compressive Sensin"
collection: publications
category: conferences
permalink: /publication/2024-06-17-CVPR-CPPNet-1
excerpt: ''
date: 2024-06-17
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2024/html/Guo_CPP-Net_Embracing_Multi-Scale_Feature_Fusion_into_Deep_Unfolding_CP-PPA_Network_CVPR_2024_paper.html'
citation: '<font face=Times New Roman>Zhen Guo and Hongping Gan. CPP-Net: Embracing Multi-Scale Feature Fusion into Deep Unfolding CP-PPA Network for Compressive Sensing. In <i> Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)</i>, 2024, pp. 25086-25095.</font>'
---

<font face=Times New Roman>In the domain of compressive sensing (CS), deep unfolding networks (DUNs) have garnered attention for their good performance and certain degree of interpretability rooted in CS domain, achieved by marrying traditional optimization solvers with deep networks. However, current DUNs are ill-suited for the intricate task of capturing fine-grained image details, leading to perceptible distortions and blurriness in reconstructed images, particularly at low CS ratios, e.g., 0.10 and below. In this paper, we propose CPP-Net, a novel deep unfolding CS framework, inspired by the primaldual hybrid strategy of the Chambolle and Pock Proximal Point Algorithm (CP-PPA). First, we derive three iteration submodules, X<sup>(k)</sup>, V<sup>(k)</sup> and Y<sup>(k)</sup>, by incorporating customized deep learning modules to solve the sparse basis related proximal operator within CP-PPA. Second, we design the Dual Path Fusion Block (DPFB) to adeptly extract and fuse multi-scale feature information, enhancing sensitivity to feature information at different scales and improving detail reconstruction. Third, we introduce the Iteration Fusion Strategy (IFS) to effectively weight the fusion of outputs from diverse reconstruction stages, maximizing the utilization of feature information and mitigating the information loss during reconstruction stages. Extensive experiments demonstrate that CPP-Net effectively reduces distortion and blurriness while preserving richer image details, outperforming current state-of-the-art methods. Codes are available at https://github.com/ICSResearch/CPP-Net.</font><br>

<!-- The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font. -->
