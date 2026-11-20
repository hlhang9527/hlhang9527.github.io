---
layout: archive
title: "Focus Areas"
permalink: /focus-areas/
author_profile: true
---

My work is organized around a simple question: how can AI systems help people make better decisions in complex real-world settings? The areas below describe the problems behind that question, what our teams build, and my part in it.

## Agent and Model Evaluation

Frontier LLMs and agents still fail on real software engineering and expert reasoning. At AI4Alpha, our team builds expert benchmarks to find those failures: long-horizon coding and terminal tasks across many programming languages, and multi-subject reasoning questions graded with rubrics. We also run an evaluation platform that compares closed, open, and self-deployed models, and we are extending it to computer-use and browser tasks.

I work on task design, grading, and hands-on review of model failures, which tells us what data and environments to build next.

## RL Environments and Post-Training Data

Agents learn from tasks whose results can be checked automatically. Our team turns real software repositories and databases into reproducible training environments with automatic verification, and collects agent trajectories for fine-tuning.

I work on task generation, reward design, and checks that keep tasks free of shortcuts and leaked answers. We test data quality by training smaller models on it.

## Agentic AI Products

[UCoWorker](https://ucoworker.com/) is an AI coworker on desktop, web, and cloud that answers with sources and carries out research, including on legal cases. Our team makes long-running agents better through tools and workflow rather than model training: carrying work past the context window, saving task state, connecting tools, retrieving and citing sources, and keeping a person in the loop.

I work on the agent harness behind these features.

Try our products: [AI4Alpha](https://www.ai4alpha.ca/) and [UCoWorker](https://ucoworker.com/).

## Applied ML/RL for Financial Decisions

At Protago Labs, our team builds machine learning systems for consumer lending.

- **Collection outreach:** we treat debt collection as sequential decision-making. A reinforcement learning policy decides when and through which channel to contact each customer, so that more loans are repaid without over-contacting people.
- **Fraud detection:** we look for organized fraud groups and new fraud patterns in identity-document images by comparing new applicants with past ones, and we test the system on past data in time order, as it would have run.

I work across modeling, reward design, vision-language model fine-tuning, and rollout to production.

## Spatial-Temporal Representation Learning

Forecasting models for traffic, energy, and other real systems usually see only a short recent window. My Ph.D. research gives them access to the whole history: retrieving similar past patterns at test time without extra training (kNN-MTS), and encoding long-term history for spatial-temporal graph neural networks. I also contribute to the open-source [BasicTS](https://github.com/GestaltCogTeam/BasicTS) library.

Representative publications: [TNNLS 2025](https://doi.org/10.1109/TNNLS.2024.3490603) and [TAI 2026](https://doi.org/10.1109/TAI.2025.3570676).

## Graph Learning and Safe RL for Energy and Control

With Hydro-Québec Research Institute, I worked on coordinating many buildings to cut energy cost and emissions while respecting comfort and safety limits, using graph models of how buildings affect each other and multi-agent reinforcement learning with a safety guard. Related work adapts energy-management policies to new buildings within a few episodes, reuses safety knowledge across control tasks, and models traffic with dynamic graph attention.

Representative publications: [IoTJ 2026](https://doi.org/10.1109/JIOT.2025.3645808), [EPEC 2025, Best Paper Award](https://doi.org/10.1109/EPEC65543.2025.11230430), [Information Sciences 2024](https://doi.org/10.1016/j.ins.2024.120230), and [arXiv 2023](https://arxiv.org/abs/2302.03586).
