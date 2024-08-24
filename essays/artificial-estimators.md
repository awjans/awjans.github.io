---
layout: essay
type: essay
image: img/artificial_estimators/artificial_estimators-square.png
title: "Artificial Estimators"
# All dates must be YYYY-MM-DD format!
date: 2024-05-19
published: true
labels:
- Software Engineering
- Artificial Intelligence
---

Throughout the history of programming, engineers have grappled with estimating the effort needed to develop software. Achieving precision, accuracy, and confidence in these estimates has proven challenging, often resulting in either overestimating or
underestimating project timelines and costs. Software engineers' implicit and explicit biases play a significant role, causing them to miss the mark frequently.

Halkjelsvik and Jorgensen (2012) shed light on the prevailing issues within this domain, revealing that deviations exceeding one-third of the initial estimate were frequent occurrences. Many estimation models have been developed over the years, such
as COCOMO, ONSET, and FPA, with the primary aim of aiding project teams in making more accurate estimates for software development projects. Other models have provided frameworks and guidelines for estimating effort and cost at the software
development task level, which will be the focus of this study.

This study delves into the possibility of training a machine learning (ML) system using a large language model (LLM) to generate accurate and reliable estimates within a desired confidence level, thereby addressing one of the long-standing challenges
in software engineering. This study will source historical data from companies and organizations that keep records of their estimations and resulting actuals. Historical data consisting of functional specifications with estimated and actual time
train the expert system and data not used in training tests the expert system. This study will compare the resulting estimates against the original data and analyze for precision, accuracy, and confidence level.

