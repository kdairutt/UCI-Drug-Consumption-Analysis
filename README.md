# Drug Consumption Classification — Data Mining Term Project

This repository contains a Data Mining term project focused on the **Drug Consumption (Quantified)** dataset from the UCI Machine Learning Repository.

The primary objective is to analyze behavioral and demographic patterns related to drug usage and evaluate the performance of different feature selection and classification algorithms.

---

## Project Objectives

- Perform Exploratory Data Analysis (EDA)
- Preprocess dataset (encoding, normalization, class transformation)
- Apply **3 Feature Selection Techniques**
  - Relief
  - Information Gain (Entropy-based)
  - Min-Max Normalization
- Train and evaluate **3 Classification Algorithms**
- Compare models based on performance metrics
- Interpret results and derive insights about drug usage patterns

---

## Dataset Information

- **Name:** Drug Consumption (Quantified)
- **Source:** UCI Machine Learning Repository  
- **Samples:** 1,885 individuals  
- **Features:** Demographic + Psychological traits
- **Target:** Binary drug usage classification (User / Non-User)

Dataset link:  
https://archive.ics.uci.edu/dataset/373/drug+consumption+quantified

---

## Methods & Techniques

## Feature Selection
| Method | Description |
|--------|------------|
| Relief | Feature weight estimation based on near-hit & near-miss samples |
| Information Gain | Entropy & information theory-based selection |
| Min-Max Normalization | Scaling baseline and dimensional effect control |

## Classification Models
| Model | Purpose |
|-------|--------|
| Logistic Regression | Baseline linear classifier |
| Random Forest | Ensemble model for robust prediction |
| SVM | Non-linear decision boundary |


---

## Evaluation Metrics

| Metric | Purpose |
|--------|--------|
Accuracy | Overall correctness |
Precision | How many predicted users were actually users |
Recall | How many real users were detected |
F1-Score | Precision-Recall balance |
Confusion Matrix | Detailed prediction breakdown |
ROC-AUC | Probabilistic model discrimination power |

---

Project Flow

1️ Dataset loading  
2️ Data preprocessing  
3️ Feature selection  
4️ Model training  
5️ Performance evaluation  
6️ Comparison & interpretation  
7️ Final discussion & conclusions  
