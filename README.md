# Online-shopper-behavior-ml-analysis
*Predictive Modeling · User Segmentation · Behavioral Insights*

## Overview
This project applies machine learning techniques to analyze online shopper behavior and predict user purchasing intention.  
Using a combination of supervised classification, regression modeling, and unsupervised clustering, the analysis explores:

- Behavioral features associated with purchase intention  
- Predictive models to identify high-likelihood buyers  
- Differences between linear and nonlinear modeling approaches  
- Natural user segments based on engagement patterns  
- Actionable insights to support targeted marketing strategies  

The project is implemented in Python using scikit-learn, pandas, and related toolkits.

---

## Objectives
- Build a supervised ML pipeline for predicting purchasing intention  
- Compare linear and nonlinear regression models for value-related signals  
- Segment users using clustering algorithms  
- Visualize behavioral trends and model results for interpretability  

---

## Data

- **Dataset:** `online_shopper_intention.csv` (UCI)
- **Format:** Tabular data with behavioral features (page views, time, bounce rate, etc.)
- **Scope:** ~12,000 user sessions with binary purchase labels and continuous value features

---

## Methods & Models Used

### **Supervised Classification**
- Logistic Regression  
- Decision Trees  

### **Regression Modeling** 
- Ridge Regression  
- XGBoost Regression 

### **Unsupervised Clustering**
- Principal Component Analysis (PCA)
- K-Means Clustering  
- Gaussian Mixture Models (GMM)

### **Visualization**
- Heatmaps  
- Confusion matrix  
- Feature importance charts  
- Cluster distribution plots  

---

## Key Results (Placeholders — replace with actual values if needed)
- Achieved **~90%+ accuracy** predicting potential buyers using Logistic Regression  
- Nonlinear regression models provided stronger explanatory power  
- Clustering revealed **three meaningful behavioral groups** (low-, medium-, high-engagement)  
- Visualizations supported clear interpretation of shopper patterns and model performance

## Notebook
- **`project.ipynb`** — Complete workflow including data loading, preprocessing, classification, regression, and clustering analysis.


## Environment Setup

- OS: macOS (Apple Silicon, M1/M2/M3)
- Python: 3.10
  
The following packages were used in this project:
```bash
- numpy == 1.23.5
- pandas == 1.5.3
- scikit-learn == 1.2.2
- scipy == 1.10.1
- matplotlib
- seaborn
- tensorflow-macos == 2.12
- scikeras == 0.12.0
- xgboost == 1.7.6
- ucimlrepo
- statsmodels
```

## How to Run

```bash
git clone https://github.com/Sean-tsy/online-shopper-behavior-ml-analysis.git
cd online-shopper-behavior-ml-analysis
