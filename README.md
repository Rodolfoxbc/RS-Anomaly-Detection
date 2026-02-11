# Unsupervised Anomaly Detection in Recommender Systems

This repository contains the implementation and experimental artifacts for the paper:

**"A Comparative Study of Unsupervised Machine Learning and Deep Learning Techniques for Anomaly Detection in Recommender Systems"**

The study evaluates classical and deep unsupervised detection models for identifying anomalous user behavior in recommender systems using the MovieLens 1M dataset.

---

## Overview

Recommender systems are vulnerable to anomalous or manipulative user behavior. 
This repository provides a reproducible framework for detecting suspicious users using:

- Isolation Forest
- One-Class Support Vector Machine
- Autoencoder-based anomaly detection
- Ensemble anomaly scoring

The evaluation is performed in a label-free setting using:
- Score distribution analysis
- Percentile-based thresholding
- Inter-model agreement (Jaccard similarity)
- Behavioral feature analysis

---

## Dataset

The experiments are based on the publicly available MovieLens 1M dataset:

https://grouplens.org/datasets/movielens/1m/

To use this repository:

1. Download the dataset from the official website.
2. Place the extracted `ml-1m` folder inside the `data/` directory.

No dataset is redistributed in this repository.

---

## Repository Structure

- `notebooks/`
  - `01_pipeline_movielens1m.ipynb` — Data preprocessing and feature extraction.
  - `02_unsupervised_detection_models.ipynb` — Isolation Forest, One-Class SVM, and Autoencoder models.
  - `03_evaluation_and_analysis.ipynb` — Thresholding, agreement analysis, and figure generation.

- `outputs/`
  - Processed feature matrices
  - Anomaly scores
  - Tables used in the paper

- `figures/`
  - Figures included in the manuscript

---

## Reproducibility

All experiments were implemented using Python and executed via Jupyter notebooks.

To install required dependencies:

```bash
pip install -r requirements.txt
