# Lung Cancer Early Prediction using Machine Learning

## Project Overview

This repository contains an end-to-end MSc Data Science project
developed for the module 7PAM2002 at the Department of Physics,
Astronomy and Mathematics, University of Hertfordshire. The project
builds non-invasive machine learning models for early lung cancer
prediction using routinely collected tabular patient data rather than
imaging.

## Research Aim

To design and evaluate supervised machine learning models capable of
predicting lung cancer in its initial stages while minimising false
negatives, a critical requirement in healthcare diagnostics.

## Dataset

-   Source: Kaggle Lung Cancer Prediction Dataset\
-   Records: 5,000 patients\
-   Features: 18 demographic, lifestyle, and clinical symptom variables\
-   Fully anonymised secondary dataset\
-   No human participants were used

## Methodology Pipeline

1.  Exploratory Data Analysis (EDA)\
2.  Data Cleaning & Handling Missing Values\
3.  Categorical Encoding\
4.  Feature Scaling and Normalisation\
5.  Train--Test Split\
6.  Supervised Model Development\
7.  Evaluation using Accuracy, Precision, Recall, F1-score and Confusion
    Matrices

## Implemented Models

-   Logistic Regression (Baseline)\
-   Decision Tree\
-   Support Vector Machine (RBF Kernel)\
-   Random Forest

## Key Results

  Model                 Accuracy     Precision    Recall       F1-Score
  --------------------- ------------ ------------ ------------ ------------
  Logistic Regression   \~0.77       \~0.67       \~0.70       \~0.69
  Decision Tree         \~0.78       **\~0.70**   \~0.75       \~0.73
  SVM (RBF)             \~0.74       \~0.62       \~0.70       \~0.65
  Random Forest         **\~0.80**   \~0.69       **\~0.88**   **\~0.77**

Random Forest demonstrated the most reliable overall performance due to
its ensemble structure, capturing non-linear relationships and reducing
false negative predictions.

## Ethics Statement

-   Public secondary dataset only\
-   No personal identifiers\
-   No intervention with human participants\
-   Full adherence to University of Hertfordshire academic integrity
    standards


