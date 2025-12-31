---
title: "Explainable AI for NLP Dataset Debugging"
excerpt: "X-Deep: A Human-in-the-Loop framework using LIME and SHAP for systematic error analysis in NLP datasets - Published in Nature Scientific Reports"
collection: portfolio
header:
  teaser: "projects/xai-framework/framework-diagram.png"
---

## Project Overview

This research introduces **X-Deep**, a Human-in-the-Loop (HitL) framework for systematically debugging NLP datasets using Explainable AI (XAI) techniques. The work was **published in Nature Scientific Reports**, demonstrating the practical value of data-centric AI approaches.

![X-Deep Framework](/images/projects/xai-framework/framework-diagram.png)
*The X-Deep framework combines human expertise with XAI techniques for systematic dataset error analysis*

## Key Contributions

- **Novel Framework**: Designed a data-centric approach that iteratively improves datasets rather than just models
- **XAI Integration**: Combined LIME and SHAP to uncover patterns in model misclassifications
- **Systematic Analysis**: Identified spurious correlations, bias patterns, and other anomalies in Arabic emotion detection datasets
- **Multi-Classifier Evaluation**: Analyzed misclassifications across Naive Bayes, Logistic Regression, GRU, and MARBERT

## Explainable AI in Action

The framework uses LIME and SHAP to understand *why* models make incorrect predictions:

![LIME and SHAP Analysis](/images/projects/xai-framework/lime-shap-example.jpg)
*Example: LIME and SHAP outputs revealing how repeated words influence emotion classification*

![Spurious Pattern Detection](/images/projects/xai-framework/shap-olympics-none.png)
*Example: Detecting spurious correlations where specific words (e.g., "Olympics") trigger incorrect labels*

## Impact

- **Published** in Nature Scientific Reports (Impact Factor: 4.6)
- **Practical mitigation strategies** for informed data collection and augmentation
- **Reproducible framework** applicable to other NLP tasks beyond emotion detection

## Technical Details

| Aspect | Details |
|--------|---------|
| **XAI Methods** | LIME, SHAP |
| **Classifiers** | Naive Bayes, Logistic Regression, GRU, MARBERT |
| **Domain** | Arabic emotion detection |
| **Publication** | Nature Scientific Reports, 2025 |

## Publication

**"A Data Centric HitL Framework for Conducting a Systematic Error Analysis of NLP Datasets using Explainable AI"**  
Ahmed El-Sayed, Aly Nasr, **Youssef Mohamed**, Ahmed Alaaeldin, Mohab Ali, Omar Salah, Abdullatif Khalid & Shaimaa Lazem  
*Scientific Reports* 15, 30406 (2025) | [DOI: 10.1038/s41598-025-13452-y](https://doi.org/10.1038/s41598-025-13452-y)
