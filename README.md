# qce26_poster

This repository supports the QCE26 poster submission, **"A Small-Scale QCNN Benchmark for Multi-Class Synthetic Image Classification."** The repository contains dataset generation, QCNN training, and classical baseline notebooks.

## Notebooks

1. `generate_4x4_qcnn_dataset.ipynb`
Generates the custom 4×4 synthetic image dataset with four classes: cross, square, triangle, and X.

2. `qcnn_4x4_multiclass_experiment.ipynb`
Trains a shared-parameter 16-qubit QCNN using Qiskit Machine Learning.

3. `classical_baselines_4x4_dataset.ipynb`
Trains classical baselines, including Logistic Regression and a small MLP, using the same 16 input features.

## Project Summary

The project compares a shared-parameter QCNN with classical baselines on a small four-class synthetic image classification task. The goal is not to claim quantum advantage, but to study the feasibility and limitations of tutorial-scale QCNNs.

## Citation

Citation information will be added after the poster is accepted and the final conference record is available.
