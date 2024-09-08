---
title: "NesTD-Net: Deep NESTA-Inspired Unfolding Network With Dual-Path Deblocking Structure for Image Compressive Sensing"
collection: publications
category: manuscripts
permalink: /publication/2024-03-08-TIP-NesTDNet-1
excerpt: ''
date: 2024-03-08
venue: 'IEEE Transactions on Image Processing'
# slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://ieeexplore.ieee.org/document/10460452'
citation: 'Hongping Gan, Zhen Guo and Feng Liu. NesTD-Net: Deep NESTA-Inspired Unfolding Network With Dual-Path Deblocking Structure for Image Compressive Sensing. <i>IEEE Transactions on Image Processing</i>, 33:1923-1937, 2024.'
---

Deep compressive sensing (CS) has become a prevalent technique for image acquisition and reconstruction. However, existing deep learning (DL)-based CS methods often encounter challenges such as block artifacts and information loss during iterative reconstruction, particularly at low sampling rates, resulting in a reduction of reconstructed details. To address these issues, we propose NesTD-Net, an unfoldingbased architecture inspired by the NESTA algorithm, designed for image CS. NesTD-Net integrates DL modules into NESTA iterations, forming a deep network that continuously iterates to minimize the l1-norm CS problem, ensuring high-quality image CS. Utilizing a learned sampling matrix for measurements and an initialization module for initial estimate, NesTD-Net then introduces Iteration Sub-Modules derived from the NESTA algorithm (i.e., **Y**<sub>k</sub>, **Z**<sub>k</sub>, and **X**<sub>k</sub>) during reconstruction stages  to iteratively solve the l1-norm CS reconstruction. Additionally, NesTD-Net incorporates a Dual-Path Deblocking Structure (DPDS) to facilitate feature information flow and mitigate block artifacts, enhancing image detail reconstruction. Furthermore, DPDS exhibits remarkable versatility and demonstrates seamless integration with other unfolding-based methods, offering the potential to enhance their performance in image reconstruction. Experimental results demonstrate that our proposed NesTD-Net achieves better performance compared to other state-of-the-art methods in terms of image quality metrics such as SSIM and PSNR, as well as visual perception on several public benchmark datasets.
