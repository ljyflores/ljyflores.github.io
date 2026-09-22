---
title: "Testing the Assumptions of Active Learning for Translation Tasks with Few Samples"
collection: publications
permalink: /publication/2026-09-21-active-learning
date: 2026-09-21
venue: 'EMNLP 2026 Multilingual Representation Learning Workshop'
paperurl: 'https://arxiv.org/abs/2604.08977v1'
authors: 'Lorenzo Jaime Yu Flores, Cesare Spinoso di-Piano, Ori Ernst, David Ifeoluwa Adelani, Jackie Chi Kit Cheung'
---

Active learning (AL) is a training paradigm for selecting unlabeled samples for annotation to improve model performance on a test set, which is useful when only a limited number of samples can be annotated. These algorithms often work by optimizing for the informativeness and diversity of the training data to be annotated. Recent work found that AL strategies fail to outperform random sampling on various language generation tasks when using 100-500 samples. To understand AL's poor performance when only using few samples, we investigate whether the core assumptions underlying AL strategies hold. We find that neither the informativeness nor diversity of the training data, which AL strategies optimize for, are correlated with test set performance. Instead, factors like the ordering of the training samples and interactions with pre-training data have a larger impact on performance. This suggests that future AL methods must take these factors into account in order to work with very few samples.
