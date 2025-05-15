---
title: "Master Thesis: Urban Change Detection from Satellite Imagery using Wavelet Transformer (in Bahasa)"
collection: publications
category: books
permalink: /publication/2023-05-01-urban-change-detection-from-satellite-imagery-using-wavelet-transformer
excerpt: "Change detection is a remote sensing task for detecting a change from two satellite imagery in the same area while being taken at different times. Change detection is one of the most difficult remote sensing tasks because the change to be detected (real-change) is mixed with apparent changes (pseudo-change) due to differences in the two images, such as brightness, humidity, seasonal differences, etc."
date: 2023-05-01
venue: 'Faculty of Computer Science, University of Indonesia, 2023'
slidesurl: #'http://academicpages.github.io/files/slides2.pdf'
paperurl: #"https://lontar.ui.ac.id/detail?id=9999920532709"
# citation: 'L. Fazry, Mgs M Luthfi Ramadhan, and W. Jatmiko, “Improving Remote Sensing Change Detection Via Locality Induction on Feed-forward Vision Transformer”, Jurnal Ilmu Komputer dan Informasi, vol. 17, no. 1, pp. 37–48, Feb. 2024.'
---

Change detection is a remote sensing task for detecting a change from two satellite imagery in the same area while being taken at different times. Change detection is one of the most difficult remote sensing tasks because the change to be detected (real-change) is mixed with apparent changes (pseudo-change) due to differences in the two images, such as brightness, humidity, seasonal differences, etc. The emergence of a Vision Transformer (ViT) as a new standard in Computer Vision, replacing Convolutional Neural Network (CNN), also shifts the role of CNN in the field of DP. Although ViT can capture long-range interactions between image patches, its computational complexity increases the number of patches quadratically. One solution to reduce the computational complexity in ViT is to reduce the Key (K) and Values (V) matrices in the Self-Attention(SA) mechanism. However, this reduction also reduces the effectiveness of ViT due to missing information, resulting in a trade-off between the effectiveness and efficiency of the method. To solve the problem, we developed a new change detection method called WaveCD. WaveCD uses Wave Attention (WA) instead of SA. WA uses the Discrete Wavelet Transform (DWT) decomposition to reduce the K and V matrices. Besides reducing the data, DWT decomposition also serves to extract important features that represent images so that the initial data can be approximated through the Inverse Discrete Wavelet Transform (IDWT) process. On the CDD dataset, WaveCD outperforms the stateof-the-art CD method, SwinSUNet, by 14.7% on IoU and 8% on F1-score. While on the LEVIR-CD dataset, WaveCD outperforms SwinSUNet by 4% on IoU and 2% on F1-score.

[Download paper](https://lontar.ui.ac.id/detail?id=9999920532709)
