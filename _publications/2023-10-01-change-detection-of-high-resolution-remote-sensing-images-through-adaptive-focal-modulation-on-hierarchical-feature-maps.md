---
title: "Change Detection of High-Resolution Remote Sensing Images Through Adaptive Focal Modulation on Hierarchical Feature Maps"
collection: publications
category: manuscripts
permalink: /publication/2023-10-01-change-detection-of-high-resolution-remote-sensing-images-through-adaptive-focal-modulation-on-hierarchical-feature-maps
excerpt: 'FocalCD introduces an efficient focal modulation-based change detection method that outperforms CNN and Transformer approaches by capturing multi-scale interactions with lower computational complexity, achieving state-of-the-art results on major CD datasets.'
date: 2023-10-01
venue: 'IEEE Access'
paperurl: #'https://ieeexplore.ieee.org/document/10173482/'
bibtexurl: #'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'L. Fazry, M. M. L. Ramadhan and W. Jatmiko, "Change Detection of High-Resolution Remote Sensing Images Through Adaptive Focal Modulation on Hierarchical Feature Maps," in IEEE Access, vol. 11, pp. 69072-69090, 2023, doi: 10.1109/ACCESS.2023.3292531'
---
One of the major challenges in the change detection (CD) of high-resolution remote sensing images is the high requirement for computational resources. Besides, to get the best change detection result, it must spot only the important changes while omitting unimportant ones, which requires learning complex interactions between multi-scale objects on the images. Despite Convolution Neural Network (CNN) efficiently extracting features from such images, it has a limited receptive field resulting in sub-optimal representation. On the other hand, Vision Transformer (ViT) can capture long-range dependencies. Still, it suffers from quadratic complexity concerning the number of image patches, especially for high-resolution images. Furthermore, both approach can not model the interactions among multi-scale image patches, which is essential for a model to fully understand the natural images. We propose FocalCD, a CD method based on a recently proposed focal modulation architecture capable of learning short and long dependencies to solve this problem. It is attention-free and does not suffer from quadratic complexity. Also, it supports learning multi-scale interaction by adaptively selecting the discriminator regions from multi-scale levels. Besides the efficient yet powerful encoder, FocalCD has an effective multi-scale feature fusion and pyramidal decoder network. FocalCD achieves strong empirical results on various CD datasets, including CDD, LEVIR-CD, and WHU-CD. It reaches F1 scores of 0.9851, 0.952, and 0.9616 on datasets CDD, LEVIR-CD, and WHU-CD outperforming state-of-the-art CD methods while having comparable or even lower computation complexity.

[Download paper](https://ieeexplore.ieee.org/document/10173482)
