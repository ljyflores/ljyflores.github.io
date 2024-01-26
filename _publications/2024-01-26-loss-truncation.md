---
title: "On the Benefits of Fine-Grained Loss Truncation: A Case Study on Factuality in Summarization"
collection: publications
permalink: none
date: 2024-01-26
venue: 'EACL 2024'
paperurl: 'https://openreview.net/forum?id=QFGsa3f-plp'
authors: 'Lorenzo Flores, Arman Cohan'
---

Text summarization and simplification are widely used applications of AI. However, such models are often prone to hallucination, which can result from training models on unaligned data. One of the prominent approaches to address this issue has been Loss Truncation (LT) (Kang and Hashimoto, 2020), an approach to modify the standard log loss to adaptively remove noisy examples during training. However, we find that LT alone yields a considerable number of hallucinated entities on various datasets. We study the behavior of the underlying losses between factual and non-factual examples, to understand and refine the performance of LT. We demonstrate that LT's performance is limited when the underlying assumption that noisy targets have higher NLL loss is not satisfied, and find that word-level NLL among entities provides better signal for distinguishing factuality. We then leverage this to propose a fine-grained NLL loss and fine-grained data cleaning strategies, and observe improvements in hallucination reduction across some datasets.

[Download paper here](https://openreview.net/forum?id=QFGsa3f-plp)