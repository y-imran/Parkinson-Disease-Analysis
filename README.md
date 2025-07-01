# Parkinson's Disease Data Analysis

This repository contains exploratory data analysis (EDA) of a dataset related to **Parkinson's Disease**. The goal of this project is to uncover meaningful patterns, statistical insights, and relationships among various voice-related features that can help distinguish between healthy individuals and those affected by Parkinson’s Disease.

## 🧠 About the Dataset

The dataset includes biomedical voice measurements from people with and without Parkinson’s Disease. It was originally compiled to aid in the diagnosis of Parkinson’s using vocal features.

- **Number of Instances:** 195
- **Number of Attributes:** 24
- **Target Variable:** `status` (1 = Parkinson's, 0 = Healthy)

## 📊 Analysis Performed

- **Data Cleaning**
  - Checked for null/missing values

- **Exploratory Data Analysis (EDA)**
  - Summary statistics of key features
  - Distribution plots of features like jitter, shimmer, HNR, etc.
  - Boxplots to compare distributions based on `status`
  - Heatmap of correlation matrix
  - Identification of highly correlated features

## 🛠️ Tools & Libraries

- Python
- pandas, numpy
- seaborn, matplotlib
- Jupyter Notebook

