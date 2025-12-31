---
title: "EEG-Based Alzheimer's Disease Classification"
excerpt: "A novel graph-based transformer framework achieving 99.1% accuracy for Alzheimer's Disease classification — 7-18 percentage points above state-of-the-art"
collection: portfolio
header:
  teaser: "projects/alzheimer/model-architecture.png"
gallery:
  - url: projects/alzheimer/eeg-heatmap.png
    image_path: projects/alzheimer/eeg-heatmap.png
    alt: "EEG Brain Heatmap"
    title: "Power spectral density (PSD) heatmap comparison"
  - url: projects/alzheimer/psd-comparison.png
    image_path: projects/alzheimer/psd-comparison.png
    alt: "PSD Comparison"
    title: "Spectral analysis showing differences between groups"
---

## Project Overview

<figure class="align-right" style="width: 300px; margin-top: -30px;">
  <img src="/images/projects/alzheimer/pipeline.png" alt="Project Pipeline">
  <figcaption>End-to-end pipeline from EEG signal acquisition to disease classification</figcaption>
</figure>

This project presents a **novel graph-based transformer architecture** for the classification of Alzheimer's Disease and Frontotemporal Dementia using EEG signals. Developed as my Bachelor's thesis, this work **achieved 99.1% accuracy**, significantly surpassing existing state-of-the-art methods by **7-18 percentage points**.


<div style="clear: both;"></div>

## Key Achievements

| Metric | Result |
|--------|--------|
| **Classification Accuracy** | 99.1% |
| **Improvement over SOTA** | 7-18 percentage points |
| **Classes** | Healthy, Alzheimer's, Frontotemporal Dementia |
| **Status** | Under review at Journal of Neural Engineering |

## Model Architecture

<figure class="align-right" style="width: 250px; margin-top: -20px;">
  <img src="/images/projects/alzheimer/model-architecture.png" alt="Model Architecture">
  <figcaption>Graph-based transformer architecture integrating spatial–temporal EEG features</figcaption>
</figure>

The framework integrates spatial and temporal EEG features using a custom graph-transformer design:

<div style="clear: both;"></div>

## EEG Feature Visualization

Our approach leverages power spectral density (PSD) features across EEG frequency bands:

{% include gallery caption="Left: Power spectral density (PSD) heatmap across brain regions. Right: Spectral analysis showing differences between healthy controls, Alzheimer's, and FTD patients." %}

The analysis highlights distinct biomarkers distinguishing the three groups. The spatial heatmaps reveal localized changes in brain activity intensity, while the spectral plots demonstrate clear separation in power distribution frequencies—specifically showing how Alzheimer's pathology alters lower-frequency band power compared to healthy controls.

## Technical Implementation

- **Graph Neural Networks**: Custom graph transformer leveraging electrode spatial relationships
- **Feature Engineering**: Relative band power, spectral coherence across EEG frequency bands
- **Signal Processing**: Comprehensive EEG preprocessing and artifact removal
- **Benchmarking**: Systematic comparison of classical ML vs. deep learning approaches

### Technologies Used
- Python, PyTorch, PyTorch Geometric
- scikit-learn, MNE-Python
- Signal processing: FFT, spectral analysis

## Research Impact

This work demonstrates the potential of **graph-based deep learning** for biomedical signal processing. The significant improvement over existing methods suggests new directions for non-invasive Alzheimer's diagnostics using routine EEG recordings.

## Publication Status

**Under Review** at IOP Journal of Neural Engineering  
*First author* — responsible for design, analysis, and drafting

## Code Repository

[github.com/yosftag1/eeg-alzheimer-classification](https://github.com/yosftag1/eeg-alzheimer-classification)

## Project Timeline

**September 2023 – June 2024** (Bachelor's Thesis Project)  
Supervised by: Dr. A. Eltrass, Dr. H. Farag