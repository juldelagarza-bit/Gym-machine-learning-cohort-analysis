# Gym Customer Churn Analysis & Prediction
Data science Randomforest  regressions to messure churn rates in gym customers

**A comprehensive data science portfolio project demonstrating end-to-end ML for business retention strategy.**

## 📋 Project Overview

This project analyzes customer data from a fitness chain to **predict churn** and **segment customers** for targeted retention strategies. Using classification models, clustering, and exploratory data analysis, we uncover key drivers of customer cancellation and provide actionable business recommendations.

**Business Impact**: 
- Identify at-risk customers early
- Optimize marketing spend on high-retention segments
- Potential churn reduction of 20-30% through data-driven interventions

## 📊 Dataset

- **Source**: `gym_churn_us.csv` (4,000 records)
- **Target**: `Churn` (binary: 1 = cancelled, 0 = active)
- **Features**: Demographics, contract details, usage metrics (e.g., class frequency, lifetime, additional charges)

## 🛠️ Techniques Used

- **EDA**: Correlation analysis, distribution plots, group comparisons
- **Preprocessing**: Scaling, train/test split
- **Modeling**:
  - Logistic Regression & Random Forest for churn prediction
  - K-Means & Hierarchical Clustering for customer segmentation
- **Evaluation**: Accuracy, ROC-AUC, classification reports, silhouette scores

## 📁 Repository Structure
gym-churn-analysis/
├── gym_churn_us.csv                  # Raw dataset
├── gym_churn_analysis.ipynb          # Main Jupyter Notebook (improved version)
├── README.md                         # This file
└── requirements.txt                  # Depend
