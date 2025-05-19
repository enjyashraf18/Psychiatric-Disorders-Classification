# Psychiatric Disorders Classification
EEG-Based Machine Learning for Psychiatric Disorder Classification
Accurate psychiatric diagnosis is often hindered by overlapping symptoms and a lack of objective biomarkers. This project leverages resting-state EEG features—including power spectral density and functional connectivity—combined with machine learning to classify six major psychiatric conditions and healthy controls.

We compare Random Forest and LightGBM ensemble classifiers on a large, labeled dataset. The Random Forest model achieved 91.86% accuracy, significantly outperforming LightGBM (74.80%), and showed strong performance across precision, recall, and F1-score.

Key Features:

EEG-based biomarkers for multi-class psychiatric classification

Feature extraction from PSD and FC matrices

Ensemble model comparison: Random Forest vs. LightGBM

Evaluation aligned with the RDoC neurobiological framework

Goal: Develop objective, neurobiologically-informed tools for mental health diagnostics using EEG and ML.
