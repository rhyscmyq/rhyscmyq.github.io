---
title: Can Agentic Trading Systems Pay for Their Own Intelligence?
date: 2026-10-07
external_link: https://arxiv.org/abs/2607.10286
tags:
  - LLM
  - FinTech
  - Agent
  - Trading
  - Evaluation
links:
  - name: Paper
    url: 'https://arxiv.org/abs/2607.10286'
    icon: file-lines
  - name: Code
    url: 'https://github.com/ParadooxAI/TradeLens'
    icon: github
---

Most agentic-trading benchmarks ask how well a model trades. TradeLens asks a question that gets skipped instead: does the agent actually earn back what it costs to run? Every reasoning step, tool call, and decision an LLM trading agent makes has a real cost, but evaluations rarely check whether that cost turns into profit.

TradeLens is a diagnostic toolkit we built to answer that: it reconstructs trading trajectories from logs, runtime traces, and deployment configs, then attributes profit and cost back to the specific decisions behind them, rather than reporting a single aggregate return. Running it across different models, capital scales, and trading frequencies, we found that viability comes down to how well a model converts intelligence into profit - some models fail by picking the wrong assets, others by timing trades badly. The paper was accepted to Findings of EMNLP 2026.

<!--more-->