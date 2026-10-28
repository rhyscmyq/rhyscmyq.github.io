---
title: "TuneAhead: Predicting Fine-tuning Performance Before Full Training Begins"
authors:
  - Luo, Yuxiang
  - Long, Haonan
  - Wang, Chen
  - admin
  - Lin, Xiaotian
  - Xu, Yanwei
  - Luo, Yuyu
  - Yang, Weikai
  - Tang, Nan
date: "2026-06-16T00:00:00Z"

# Publication type.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Machine Learning (ICML 2026)"
publication_short: "ICML 2026"

abstract: |
  Fine-tuning large language models is expensive, and its outcome depends heavily on dataset quality and training configuration, yet practitioners usually only find out whether a run worked after paying for the full training job. TuneAhead is a lightweight framework that predicts fine-tuning performance before committing to full training, combining static dataset descriptors with dynamic features collected from a short, standardized probe run. A gradient-boosted predictor maps these features to an expected outcome, with SHAP-based attributions explaining which factors are driving the prediction.

  Evaluated on more than 1,300 fine-tuning runs of Qwen2.5-7B-Instruct, TuneAhead outperforms baselines such as Early-Stop Extrapolation and ProxyLM, reaching an RMSE of 1.47 points on a held-out set of 370 runs and placing the large majority of predictions within a few points of the true score. The approach lets researchers screen configurations for likely success or failure before paying for full training, cutting unnecessary compute cost.

tags:
  - Machine Learning
  - LLM Fine-tuning
  - Performance Prediction

featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2606.17660
- name: ICML
  url: https://icml.cc/virtual/2026/poster/64847
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects
projects:
  - 2026TuneAhead
---
