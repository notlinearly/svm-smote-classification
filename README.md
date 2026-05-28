# SVM Classification with SMOTE

This repository contains a machine learning classification project using **Support Vector Machine (SVM)** with **SMOTE (Synthetic Minority Oversampling Technique)** to handle imbalanced datasets. The goal of this project is to improve classification performance by balancing minority classes and training an optimized SVM model.

## Project Description

Class imbalance is a common challenge in machine learning where some classes contain significantly fewer samples than others. This project applies SMOTE to generate synthetic samples for minority classes before training the model.

The notebook performs:

* Data Cleaning and Preprocessing
* Feature Scaling
* Handling Imbalanced Data using SMOTE
* SVM Model Training
* Model Evaluation and Performance Analysis
* Visualization using Seaborn and Matplotlib

## Files Included

* `svm-with-smote.ipynb`: Kaggle Notebook containing preprocessing, SMOTE implementation, model training, and evaluation
* `README.md`: Project overview and documentation

## Key Insights

* SMOTE improved classification performance on imbalanced data.
* Feature scaling enhanced SVM model efficiency and prediction quality.
* The trained model achieved better balance between precision and recall after oversampling.

## Libraries Used

```bash
pandas
numpy
scikit-learn
imblearn
matplotlib
seaborn
```
