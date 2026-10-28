---
title: "Can Agentic Trading Systems Pay for Their Own Intelligence?"
authors:
  - admin
  - Li, Changlun
  - Wang, Chen
  - Zhang, Fan
  - Wang, Mengxiang
  - Miao, Dayi
  - Ma, Peixian
  - Yan, Jiangpeng
  - Chen, Liyuan
  - Liu, Shuoling
  - Nakov, Preslav
  - Luo, Yuyu
  - Tang, Nan
date: "2026-10-07T00:00:00Z"

# Publication type.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Findings of the Association for Computational Linguistics: EMNLP 2026"
publication_short: "Findings of EMNLP 2026"

abstract: |
  A project asking a simple but overlooked question: can LLM-based trading agents actually pay for their own intelligence? Agentic trading systems incur real costs from reasoning, tool calls, and frequent decisions, yet existing evaluations focus on performance metrics and rarely check whether these costs turn into incremental profit. To address this, we introduce TradeLens, a diagnostic toolkit that uses trading records, runtime traces, and deployment configurations to reconstruct trading trajectories, attribute profit and cost to specific evidence, and diagnose whether and why an agent pays for itself.

  We find that viability hinges on intelligence-to-profit conversion: different models fail in different ways (e.g., poor asset selection versus negative timing), and capital scale, trading frequency, and architecture matter mainly through their effect on decision-attributed timing value. These results suggest that LLM trading agents should be evaluated through trace-grounded diagnosis rather than capability-based performance rankings.

tags:
  - LLM
  - FinTech
  - Agent
  - Trading
  - Evaluation

featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2607.10286
url_pdf: ''
url_code: 'https://github.com/ParadooxAI/TradeLens'
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
  - 2026TradeLens
---
