# Deepfake Detection Experiments

This repository contains a series of experiments evaluating the performance of lightweight Vision Transformers, Convolutional Neural Networks, and hybrid models for deepfake detection in resource-constrained environments. Each experiment investigates different aspects of model accuracy, efficiency, and robustness.

## Experiment Details

Experiment 1: Accuracy of Lightweight Vision Transformers vs. CNNs

- Dataset: FaceForensics++ (C40 compression)

- Models: Lightweight Vision Transformers, CNNs

- Training: Standardized preprocessing and training pipeline

- Evaluation Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

Experiment 2: Impact of Media Compression on Detection Accuracy

- Dataset: FaceForensics++ (C23 vs. C40 compression levels)

- Models: Lightweight Vision Transformers, CNNs, Hybrid Models

- Training: Models trained on C23 and tested on C40

- Evaluation Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

Experiment 3: Trade-Offs Between Accuracy and Computational Efficiency

- Dataset: FaceForensics++ (C40 compression)

- Models: Lightweight Vision Transformers, CNNs, Hybrid Models

- Training: Standardized hyperparameters for fair comparison

- Evaluation Metrics: Accuracy, Inference Time (CPU & GPU), Memory Usage, Model Size

Experiment 4: Robustness to Real-World Variations

- Dataset: FaceForensics++ (C40 compression with augmentations)

- Models: Lightweight Vision Transformers, CNNs, Hybrid Models

- Training: Models trained on clean data and tested with noise, cropping, and lighting variations

- Evaluation Metrics: Accuracy degradation under augmented conditions
