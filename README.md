# CS4082_DetectionOfParkinsonsDiseases_EarlyDetectionOfDisease
Early Parkinson’s disease detection using machine learning, comparing multiple models and improving performance with preprocessing, tuning, and ensemble methods.
# Early Detection of Parkinson’s Disease Using Machine Learning

## Project Description
This project applies machine learning techniques for early detection of Parkinson’s disease using two datasets: the UCI Parkinson’s voice dataset and selected clinical datasets from PPMI. The project focuses on supervised classification under challenging data conditions such as class imbalance and label noise.

The main goal is to compare multiple machine learning models and identify the most reliable model for Parkinson’s detection using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.

## Datasets
- UCI Parkinson’s Dataset: voice-based biomedical measurements.
- PPMI Dataset: clinical Parkinson’s data including patient status and motor assessments.

## Machine Learning Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors
- Naive Bayes
- Gradient Boosting
- Voting Ensemble

## Final Model
Gradient Boosting was selected as the final model because it achieved the strongest overall performance, including high F1-score and AUC-ROC.

## Project Pipeline
1. Data loading
2. Exploratory Data Analysis
3. Data preprocessing
4. Class imbalance handling using SMOTE
5. Label noise simulation
6. Baseline model training
7. Hyperparameter tuning
8. Ensemble model comparison
9. Final evaluation and limitations analysis

## Installation Instructions

Clone this repository:

```bash
git clone https://github.com/YOUR-USERNAME/CS4082-Parkinsons-Detection.git
cd CS4082-Parkinsons-Detection
