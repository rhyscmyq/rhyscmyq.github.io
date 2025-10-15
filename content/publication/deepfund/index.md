---
title: "Time Travel is Cheating: Going Live with DeepFund for Real-Time Fund Investment Benchmarking"
authors:
  - Li, Changlun
  - Shi, Yao
  - Wang, Chen
  - admin
  - Ruan, Runke
  - Huang, Weijie
  - Long, Haonan
  - Huang, Lijun
  - Luo, Yuyu
  - Tang, Nan
date: "2025-01-01T00:00:00Z"

# Publication type.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: "arXiv"

abstract: |
  Large Language Models (LLMs) have demonstrated notable capabilities across financial tasks, including financial report summarization, earnings call transcript analysis, and asset classification. However, their real-world effectiveness in managing complex fund investment remains inadequately assessed. A fundamental limitation of existing benchmarks for evaluating LLM-driven trading strategies is their reliance on historical back-testing, inadvertently enabling LLMs to "time travel"-leveraging future information embedded in their training corpora, thus resulting in possible information leakage and overly optimistic performance estimates. To address this issue, we introduce DeepFund, a live fund benchmark tool designed to rigorously evaluate LLM in real-time market conditions. Utilizing a multi-agent architecture, DeepFund connects directly with real-time stock market data-specifically data published after each model pretraining cutoff-to ensure fair and leakage-free evaluations. Empirical tests on nine flagship LLMs from leading global institutions across multiple investment dimensions-including ticker-level analysis, investment decision-making, portfolio management, and risk control-reveal significant practical challenges. Notably, even cutting-edge models such as DeepSeek-V3 and Claude-3.7-Sonnet incur net trading losses within DeepFund real-time evaluation environment, underscoring the present limitations of LLMs for active fund management. Our code is available at https://github.com/HKUSTDial/DeepFund.

tags:
  - LLM
  - FinTech
  - Agent
  - Investment

featured: true

links:
- name: arXiv
  url: https://arxiv.org/pdf/2505.11065
url_pdf: ''
url_code: 'https://github.com/HKUSTDial/DeepFund'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects
projects:
  - DeepFund
---
