---
title: "A Split-then-Join Approach to Abstractive Summarization for Very Long Documents in a Low Resource Setting"
collection: publications
category: preprints
permalink: /publication/2025-05-01-a-split-then-join-approach-to-abstractive-summarization-for-very-long-documents-in-a-low-resource-setting
excerpt: "BIGBIRD-PEGASUS achieves state-of-the-art on abstractive text summarization for long documents. However it's capacity still limited to maximum of 4,096 tokens, thus caused performance degradation on summarization for very long documents. Common method to deal with the issue is to truncate the documents. In this reasearch, we'll use different approach."
date: 2025-05-01
venue: 'arXiv'
slidesurl: #'http://academicpages.github.io/files/slides2.pdf'
paperurl: #"https://doi.org/10.48550/arXiv.2505.08190"
# citation: 'L. Fazry, Mgs M Luthfi Ramadhan, and W. Jatmiko, “Improving Remote Sensing Change Detection Via Locality Induction on Feed-forward Vision Transformer”, Jurnal Ilmu Komputer dan Informasi, vol. 17, no. 1, pp. 37–48, Feb. 2024.'
---

BIGBIRD-PEGASUS achieves state-of-the-art on abstractive text summarization for long documents. However it's capacity still limited to maximum of 4,096 tokens, thus caused performance degradation on summarization for very long documents. Common method to deal with the issue is to truncate the documents. In this reasearch, we'll use different approach. We'll use the pretrained BIGBIRD-PEGASUS model by fine tuned the model on other domain dataset. First, we filter out all documents which length less than 20,000 tokens to focus on very long documents. To prevent domain shifting problem and overfitting on transfer learning due to small dataset, we augment the dataset by splitting document-summary training pair into parts, to fit the document into 4,096 tokens.

[Download paper](https://doi.org/10.48550/arXiv.2505.08190)
