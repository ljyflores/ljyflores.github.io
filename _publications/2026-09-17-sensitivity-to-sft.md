---
title: "Confident in a Confidence Score: Investigating the Sensitivity of Confidence Scores to Supervised Fine-Tuning"
collection: publications
permalink: /publication/2026-09-17-sensitivity-to-sft
date: 2026-09-17
venue: 'EMNLP 2026 UncertaiNLP Workshop'
paperurl: 'https://arxiv.org/abs/2604.08974'
authors: 'Lorenzo Jaime Yu Flores, Cesare Spinoso di-Piano, Jackie Chi Kit Cheung'
---

Uncertainty quantification techniques measure confidence in language model outputs to support critical applications like hallucination detection and selective prediction. While prior work has developed various confidence metrics and demonstrated their calibration for classification tasks or using verbalized confidence, the robustness of probability-based and self-consistency-based UQ metrics for natural language generation remains underexplored particularly under model adaptation. Since practitioners routinely apply supervised fine-tuning to adapt models to new tasks, a key question arises: do confidence metrics maintain their calibration when models are fine-tuned? We investigate this question across NLG tasks including translation, question answering, and mathematical reasoning. We find that calibration shifts substantially after SFT: across 216 configurations, it degrades in 112 cases and improves in 104, with confidence scores shifting due to factors beyond output quality, such as proximity to the training distribution. Degradation is therefore neither universal nor rare, and its direction cannot be anticipated from the pre-SFT model. Through a downstream task evaluation, we show that this miscalibration substantially reduces the practical utility of confidence scores for identifying correct answers. Our findings reveal that existing confidence metrics for NLG cannot be reliably deployed off-the-shelf after fine-tuning, highlighting the need for calibration-robust UQ methods under model adaptation.
