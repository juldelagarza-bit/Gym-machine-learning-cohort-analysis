# Gym Customer Churn Analysis & Prediction
Data science Randomforest  regressions to messure churn rates in gym customers

**A comprehensive data science portfolio project demonstrating end-to-end ML for business retention strategy.**

## 📋 Project Overview

This project analyzes customer data from a fitness chain to **predict churn** and **segment customers** for targeted retention strategies. Using classification models, clustering, and exploratory data analysis, we uncover key drivers of customer cancellation and provide actionable business recommendations.

**Business Impact**: 
- Identify at-risk customers early
- Optimize marketing spend on high-retention segments
- Potential churn reduction of 20-30% through data-driven interventions

<img width="1143" height="1049" alt="1d809069-c45c-4bf0-9bc5-b1420c6b14c6" src="https://github.com/user-attachments/assets/88a34dd0-8cb3-4002-b17a-a1790a0562a1" />

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

<img width="999" height="705" alt="9688cf42-cdac-4cf0-a202-7a5c5739d68a" src="https://github.com/user-attachments/assets/c89d19c0-6f49-4105-9055-dd27f6165d4c" />


## 📁 Repository Structure
gym-churn-analysis/
├── gym_churn_us.csv                  # Raw dataset
├── gym_churn_analysis.ipynb          # Main Jupyter Notebook (improved version)
├── README.md                         # This file
└── requirements.txt                  # Depend
