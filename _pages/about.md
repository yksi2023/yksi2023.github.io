---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am Yikai Si.

I am an undergraduate student in the **Zhiyuan Honors Program (Physics Track)** at **Shanghai Jiao Tong University**, currently exploring computational neuroscience under the supervision of Prof. Shanshan Qin[Shanshan Qin](mailto:qinss@sjtu.edu.cn).

## Research Interest

I have broad interests in computational neuroscience, especially representation, learning, and dynamics in neural systems; and applying machine learning tools to characterize and model these processes.

## Education

* **Shanghai Jiao Tong University** (2023 - 2027, Expected)
  * B.S. in Physics
  * [Zhiyuan Honors Program](https://en.zhiyuan.sjtu.edu.cn/en/about/overview) (top 10% selective honors program)
  * Tsung-Dao Lee Elite Class
  * **GPA:** 3.92/4.30 ; **Average Score:** 91.0/100

## Research Experience

* **Representational Drift of Artificial Neural Networks under Continual Learning**
  * *Undergraduate Research Assistant, Computational Neuroscience Group* | Supervisor: Shanshan Qin
  * *2025.6 -- Present*
  * [[GitHub](https://github.com/yksi2023/Representational-Drift-In-Deep-Continual-Learning)]
  * (Active since 2025.10) Built a 20-task class-incremental benchmark on TinyImageNet with pretrained ResNet-18 (froze early stages; fine-tuned layer3--4 and classifier) in PyTorch.
  * Implemented continual-learning baselines (fine-tuning, experience replay, EWC) under TIL/CIL evaluation; organized reproducible experiments with config-driven scripts and version control (Git).
  * Developed layer-wise drift metrics on a fixed probe set (mean cosine distance and mean $L_2$ distance) and computed model--model / sample--sample similarity matrices; visualized results with Matplotlib.
  * Preliminary results: replay/EWC reduce forgetting on earlier tasks, while late-layer representations still exhibit measurable drift across tasks.

* **DCI-LLM: Multimodal Few-Shot Prediction for Double Cone Ignition Laser Fusion**
  * *Supervisor: Xiaohui Yuan, Jie Zhang*
  * *2025.10 - 2026.1*
  * Built an experimental-data-driven multimodal model to predict peak plasma density timing under extremely few shots.
  * Fused laser power time series, diagnostic images, and text metadata; compressed sequences into tokens (Signal Digestor) for LLM-based reasoning.
  * Introduced cross-modal attention to align temporal tokens with frozen vision features.
  * Outperformed Transformer/LSTM baselines and image-free ablations on real experiments (report MAE in ns).

## Honors and Awards

* **Zhiyuan Honors Scholarship** (2023, 2024, 2025)
  * Zhiyuan College, Shanghai Jiao Tong University
  * Awarded to students in the Honors Program with outstanding academic achievement.
