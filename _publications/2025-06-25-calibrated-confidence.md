---
title: "Improving the Calibration of Confidence Scores in Text Generation Using the Output Distribution’s Characteristics"
collection: publications
permalink: /publication/2025-06-25-calibrated-confidence
date: 2025-06-25
venue: 'ACL Main 2025'
paperurl: 'https://arxiv.org/pdf/2506.00637'
authors: 'Lorenzo Jaime Yu Flores, Ori Ernst, Jackie Chi Kit Cheung'
---

Well-calibrated model confidence scores can improve the usefulness of text generation models. For example, users can be prompted to review predictions with low confidence scores, to prevent models from returning bad or potentially dangerous predictions. However, confidence metrics are not always well calibrated in text generation. One reason is that in generation, there can be many valid answers, which previous methods do not always account for. Hence, a confident model could distribute its output probability among multiple sequences because they are all valid. We propose task-agnostic confidence metrics suited to generation, which rely solely on the probabilities associated with the model outputs without the need for further fine-tuning or heuristics. Using these, we are able to improve the calibration of BART and Flan-T5 on summarization, translation, and QA datasets.