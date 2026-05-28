SVM Classification with SMOTE

This repository contains a machine learning classification project using Support Vector Machine (SVM) with SMOTE (Synthetic Minority Oversampling Technique). The goal of this project is to handle imbalanced classification data and improve model performance through proper preprocessing and oversampling techniques.

Project Description

Class imbalance is a common issue in machine learning where some classes have significantly fewer samples than others. This project applies SMOTE to balance the dataset before training an SVM classifier.

The notebook performs:

Data Cleaning and Preprocessing
Feature Scaling
Handling Imbalanced Data using SMOTE
SVM Model Training
Model Evaluation and Performance Analysis
Visualization using Seaborn and Matplotlib

Files Included

svm-with-smote.ipynb: Kaggle Notebook containing preprocessing, SMOTE implementation, model training, and evaluation
README.md: Project overview and documentation

Key Insights

SMOTE helped improve classification performance on imbalanced data.
Feature scaling improved SVM training efficiency and prediction quality.
The model demonstrated better balance between precision and recall after oversampling.

Libraries Used

pandas
numpy
scikit-learn
imblearn
matplotlib
seaborn
