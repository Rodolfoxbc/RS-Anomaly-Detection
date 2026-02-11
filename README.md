# Unsupervised Anomaly Detection in Recommender Systems

This repository contains the full experimental pipeline for the paper:

**"A Comparative Study of Unsupervised Machine Learning and Deep Learning Techniques for Anomaly Detection in Recommender Systems"**

The project evaluates classical and deep unsupervised detection models for identifying anomalous user behavior using the MovieLens 1M dataset.

---

## Project Overview

Recommender systems are susceptible to anomalous or manipulative user behavior. 
This repository provides a reproducible, label-free framework for detecting suspicious users based on behavioral feature representations.

The framework includes:

- Feature engineering from raw user–item interactions
- Isolation Forest
- One-Class Support Vector Machine
- Autoencoder-based anomaly detection
- Ensemble anomaly scoring
- Threshold stability and inter-model agreement analysis

All experiments are conducted in a fully unsupervised setting.

---

## Dataset

This study uses the publicly available **MovieLens 1M dataset** from the GroupLens Research Group.

Download it from:

https://grouplens.org/datasets/movielens/1m/

After downloading, place the extracted folder as:

