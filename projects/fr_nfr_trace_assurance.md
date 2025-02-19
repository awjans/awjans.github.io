---
layout: project
type: project
image: img/artificial_estimators/artificial_estimators-square.png
title: "FR-NFR Trace Assurance"
date: 2025-02-01
published: true
labels:
  - Python
  - Requirements Traceability
  - Large Language Models
  - Software Quality Assurance
  - Requirements Engineering (RE)
  - Semantic Processing
summary: "A a research project with Dr. Port on using an LLM to generate the requirements traceability matrix (RTM)."
---

![Code](../img/artificial_estimators/artificial_estimators-banner.png "FR NFR Trace Assurance")

Requirements assurance increases confidence in software engineering decision-making through independent audits and reviews. One critical and effort-intensive activity is the assurance of the requirements traceability matrix (RTM), a labor-intensive
and error-prone task that does not scale well with system size. In this, determining the correctness and completeness of the many-to-many relationships between functional requirements (FR) and non-functional requirements (NFRs) is a particularly
critical but tedious and error-prone activity for assurance personnel to perform manually. This has been exasperated by the increasing use of machine-learning tools that partially automate the generation of RTMs. This study proposes an update to a
semi-supervised latent semantic analysis (LSA) dual-model similarity/dissimilarity framework utilizing large language models (LLMs) for semantic processing of requirements traceability matrices (RTMs) to generate investigation sets that can be
efficiently analyzed by assurance personnel. This approach reduces effort, complexity, and risk from errors of omission and commission in assuring traces of FR to NFR requirements for large systems. The key challenges addressed include the difficulty
in identifying conceptual relationships, managing complexity in large systems, the subjective nature of NFRs, and the risk of missing traces critical to the development of the system. The method was validated using data on critical systems at NASA’s
Jet Propulsion Laboratory data and publicly available data from the PROMISE repository to enable reproducibility of results. The results demonstrate the approach's ability to outperform traditional manual techniques while ensuring high confidence in
assurance. By incorporating techniques such as retrieval-augmented generation (RAG) and adaptive thresholds, the study demonstrates the transformative potential of LLMs in automating and scaling requirements engineering processes. This research
highlights how a dual-model system that calculates similarity and dissimilarity scores separately provides a more nuanced understanding of traceability relationships that are valuable for assurance practice. These findings highlight the potential of
AI-driven traceability solutions to enhance quality assurance, mitigate risks, and streamline software development in complex, high-risk environments suitable for immediate integration into existing assurance processes.


Source: [awjans/FR-NFR-Trace-Assurance](https://github.com/awjans/FR-NFR-Trace-Assurance)
