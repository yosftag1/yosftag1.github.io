---
title: "A Data Centric HitL Framework for Conducting a Systematic Error Analysis of NLP Datasets using Explainable AI"
collection: publications
category: manuscripts
permalink: /publication/2025-nature-scientific-reports
excerpt: 'A Human-in-the-Loop framework designed to debug NLP datasets using Explainable AI techniques, with a case study on emotion detection in Arabic text.'
date: 2025-08-19
venue: 'Scientific Reports'
paperurl: 'https://doi.org/10.1038/s41598-025-13452-y'
citation: 'El-Sayed, A., Nasr, A., Mohamed, Y. et al. A Data Centric HitL Framework for Conducting aSsystematic Error Analysis of NLP Datasets using Explainable AI. Sci Rep 15, 30406 (2025). https://doi.org/10.1038/s41598-025-13452-y'
---

The interest in data-centric AI has been recently growing. As opposed to model-centric AI, data-centric approaches aim at iteratively and systematically improving the data throughout the model life cycle rather than in a single pre-processing step. The merits of such an approach have not been fully explored on NLP datasets. 

**X-Deep Framework**: A Human-in-the-Loop framework designed to debug an NLP dataset using Explainable AI techniques, proposed to uncover data problems related to emotion detection tasks.

## Key Contributions

**Case Study**: Emotion detection in Arabic text using a thorough analysis that leveraged two Explainable AI techniques:
- **LIME** (Local Interpretable Model-agnostic Explanations)
- **SHAP** (SHapley Additive exPlanations)

**Analysis conducted** on misclassified instances for four classifiers:
- Naive Bayes
- Logistic Regression  
- GRU (Gated Recurrent Unit)
- MARBERT

## Results

The systematic process resulted in identifying:
- **Spurious correlation** patterns in the dataset
- **Bias patterns** affecting model performance
- **Other anomaly patterns** requiring attention

**Impact**: Appropriate mitigation strategies are suggested for an informed and improved data collection, processing and augmentation plan for performing emotion detection tasks on this dataset.

**Published**: August 19, 2025 | **Volume**: 15, Article 30406 | **DOI**: [10.1038/s41598-025-13452-y](https://doi.org/10.1038/s41598-025-13452-y)