---
title: "GLAD: Generalizable Tuning for Vision-Language Models"
collection: publications
category: conferences
permalink: /publication/GLAD
excerpt: 
date: 2025-7-17
venue: 'ICCV Workshop 2025'
paperurl: 'https://openaccess.thecvf.com/content/ICCV2025W/MMFM/html/Peng_GLAD_Generalizable_Tuning_for_Vision-Language_Models_ICCVW_2025_paper.html'
codeurl: 'https://github.com/YuqiPeng77/GLAD'
slidesurl: 
videourl: 
author: '<strong>Yuqi Peng</strong>, Pengfei Wang, Jianzhuang Liu, Shifeng Chen'
---
Pre-trained vision-language models, such as CLIP, show impressive zero-shot recognition ability and adaptability to new tasks via prompt tuning, even with limited training data. However, existing prompt tuning methods face two main challenges: (1) In few-shot scenarios, data scarcity often leads to overfitting, which limits domain generalization. (2) To mitigate overfitting, these methods typically rely on complex task-specific model architectures and sensitive hyper-parameter tuning, severely restricting their general applicability. To address these issues, we propose a simpler and more general framework called GLAD (Generalizable LoRA tuning with Regularized Gradient). We show that merely applying LoRA achieves performance comparable to current state-of-the-art prompt-based methods. While LoRA is effective, it remains susceptible to overfitting in few-shot learning scenarios. This vulnerability arises because LoRA, optimized on limited training data, is sensitive to the shifts in data distribution. To mitigate the risk of overfitting, we introduce a gradient-based regularization technique. This technique effectively steers the optimization trajectory, encouraging the model to find more stable parameter region, which improves robustness to variations in data distribution. Through extensive experiments conducted on 15 benchmark datasets, we demonstrate that GLAD outperforms previous prompt tuning approaches in terms of base-to-novel generalization, domain generalization, and cross-dataset generalization.
