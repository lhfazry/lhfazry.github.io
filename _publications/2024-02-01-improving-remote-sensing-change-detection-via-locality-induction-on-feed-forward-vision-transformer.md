---
title: "Improving Remote Sensing Change Detection Via Locality Induction on Feed-forward Vision Transformer"
collection: publications
category: manuscripts
permalink: /publication/2024-02-01-improving-remote-sensing-change-detection-via-locality-induction-on-feed-forward-vision-transformer
excerpt: 'LocalCD enhances change detection in remote sensing by integrating locality mechanisms into Vision Transformers through depth-wise convolutions, achieving superior F1-scores of 0.9548 (CDD) and 0.9243 (LEVIR-CD) while reducing segmentation artifacts.'
date: 2024-02-01
venue: 'Jurnal Ilmu Komputer dan Informasi (JIKI)'
slidesurl: #'http://academicpages.github.io/files/slides2.pdf'
paperurl: #'https://jiki.cs.ui.ac.id/index.php/jiki/article/view/1188'
# citation: 'L. Fazry, Mgs M Luthfi Ramadhan, and W. Jatmiko, “Improving Remote Sensing Change Detection Via Locality Induction on Feed-forward Vision Transformer”, Jurnal Ilmu Komputer dan Informasi, vol. 17, no. 1, pp. 37–48, Feb. 2024.'
---

The main objective of Change Detection (CD) is to gather change information from bi-temporal remote sensing images. The recent development of the CD method makes use of the recently proposed Vision Transformer (ViT) backbone. Despite ViT being superior to Convolutional Neural Networks (CNN) at modeling long-range dependencies, ViT lacks a locality mechanism, a critical property of pixels that comprise natural images, including remote sensing images. This issue leads to segmentation artifacts such as imperfect changed region boundaries on the predicted change map. To address this problem, we propose LocalCD, a novel CD method that imposes the locality mechanism into the Transformer encoder. Particularly, it replaces the Transformer's feed-forward network using an efficient depth-wise convolution between two $1 \times 1$ convolutions. LocalCD outperforms ChangeFormer by a significant margin. Specifically, it achieves an F1-score of 0.9548 and 0.9243 on CDD and LEVIR-CD datasets.

[Download paper](https://jiki.cs.ui.ac.id/index.php/jiki/article/view/1188)
