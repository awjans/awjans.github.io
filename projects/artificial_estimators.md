---
layout: project
type: project
image: img/artificial_estimators/artificial_estimators-square.png
title: "Artificial Estimators"
date: 2024-05-01
published: true
labels:
  - Python
  - Haystack
  - Hugging Face
  - LLM
summary: "A Study in Training Systems for Expert Estimating Software Development Task Efforts."
---

![Code](../img/artificial_estimators/artificial_estimators-banner.png "Artificial Estimators")

Effort estimation in software engineering has long been a persistent challenge, with traditional expert-based and algorithmic approaches often producing inaccurate and inconsistent results. This research investigates whether large language models (LLMs), specifically when combined with Generative Pretrained Transformers (GPT) and Retrieval-Augmented Generation (RAG), can provide reliable estimates of the effort required for software development tasks. A mixed-methods research design was used: historical project data was collected, standardized, and used to fine-tune an open-source LLM, which was then tested against untrained configurations, with and without RAG. Thirty feature requests were used as test cases in multiple runs to evaluate performance. The results indicate that while LLMs can generate effort estimates, their outputs are highly inconsistent. The research suggests that, despite their potential, current LLM-based systems cannot yet replace expert judgment in estimating software projects. Instead, they highlight the need for further refinement, the integration of domain-specific training, and standardized data practices to harness LLMs as supportive—rather than standalone—tools for estimating software engineering efforts.

Paper: [Artifical Estimators](../img/artificial_estimators/Artificial_Estimators.pdf)
Source: [artificialexperts/estimators](https://github.com/artificialexperts/estimators)
