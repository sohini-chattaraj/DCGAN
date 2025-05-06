# ECG Signal Analysis for Anomaly Detection

## Project Overview

This repository contains a comprehensive approach for ECG signal analysis, focusing on anomaly detection and performance evaluation of classification models. The main goal of this project is to develop a machine learning-based system capable of detecting abnormalities in ECG signals, such as arrhythmias, using various performance evaluation metrics like ROC curves, precision, sensitivity, and more.

The project involves:

- **ECG Signal Generation & Preprocessing**: Simulating ECG-like signals, adding noise, and applying bandpass filters.
- **Anomaly Detection**: Using machine learning classifiers to detect abnormal ECG signals.
- **Performance Evaluation**: Evaluating the classifier's performance using metrics like ROC curves, precision, recall, F1 score, and AUC (Area Under the Curve).
- **Threshold Optimization**: Visualizing trade-offs between sensitivity and specificity to select optimal thresholds.

---

## Key Features

- **ECG Signal Simulation**: Generate ECG-like signals with added noise for realistic analysis.
- **Bandpass Filtering**: Filter ECG signals to remove noise and enhance the quality of the signal.
- **Machine Learning Classification**: Implement and evaluate binary classification models for detecting abnormal ECG signals.
- **ROC Curve & AUC Evaluation**: Visualize the performance of the classification models using ROC curves and calculate the AUC.
- **Evaluation Metrics**: Provide various metrics such as sensitivity, specificity, precision, and F1 score for comprehensive model evaluation.
- **Model Performance Visualization**: Display ROC curves, confusion matrices, and other relevant plots for model analysis.

---

## Technologies Used

- **Python**: The core programming language used for data preprocessing, model training, and evaluation.
- **NumPy**: For numerical computations and handling of ECG signals.
- **Matplotlib**: For visualizing the ECG signals, ROC curves, and other evaluation metrics.
- **SciPy**: Used for signal processing and filtering ECG data.
- **Scikit-learn**: For implementing machine learning models and calculating evaluation metrics.

---

