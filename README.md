# Recreational Running Psychology ERP

This repository contains the code and reproducibility materials for my MSc Data Science Extended Research Project at The University of Manchester.

## Project Title

**How do psychological challenges differ across recreational runners with different experience levels and running frequency?**

## Project Overview

This project investigates psychological experiences among recreational runners with different levels of running experience and weekly running frequency.

The study combines statistical analysis with Natural Language Processing (NLP) to examine both quantitative survey responses and open-ended text responses.

The main analyses include:

- Descriptive statistics
- Kruskal–Wallis tests
- Dunn's post-hoc tests with Bonferroni correction
- Holm multiple-testing correction
- LDA topic modelling
- Sentence-BERT embeddings
- K-Means clustering
- Chi-square tests
- NLP robustness and sensitivity analyses
- Cross-method comparison using NMI and ARI

## Data

The main quantitative dataset contains responses from 593 recreational runners.

A total of 320 usable open-ended responses were included in the NLP analysis after preprocessing.

The original participant-level survey dataset is not included in this public repository due to data governance and confidentiality considerations.

The repository contains the code and supporting outputs required to reproduce the analyses reported in the dissertation.

## Repository Structure

```text
recreational-running-psychology-erp/
│
├── README.md
├── requirements.txt
│
├── code/
│   ├── data_preprocessing.py
│   ├── statistical_analysis.py
│   ├── lda_analysis.py
│   ├── sentence_bert_analysis.py
│   └── robustness_analysis.py
│
├── results/
│   ├── statistical_results.csv
│   ├── lda_results.csv
│   └── nlp_robustness_results.xlsx
│
└── figures/
    ├── lda_coherence.png
    ├── bert_silhouette.png
    └── topic_frequency.png
