# Abstract

This project tackles the challenge of detecting fraudulent auto insurance claims using real-world data from an insurance company. By leveraging machine learning models and optimizing their performance through hyperparameter tuning, this project aims to identify fraudulent claims with accuracy and business relevance.

There are two datasets (Excel Files) –
1. Insurance Fraud – TRAIN-3000, and
2. Insurance Fraud – TEST-12900.

## Project Overview  
Each record in the dataset represents an insurance claim, with a binary target variable (`FRAUDFOUND`) indicating whether the claim was fraudulent. The goal is to develop interpretable and efficient models for fraud detection while ensuring practical business application.  

## Dataset Details  
### Input Variables  
Features include temporal, demographic, policy-related, and claim-specific details like:  
- `MONTH`, `WEEKOFMONTH`, `DAYOFWEEK`  
- `SEX`, `MARITALSTATUS`, `AGE`, `FAULT`  
- `POLICYTYPE`, `VEHICLECATEGORY`, `VEHICLEPRICE`  
- `POLICEREPORTFILED`, `WITNESSPRESENT`, `AGENTTYPE`, and more.  

### Output Variable  
- **FRAUDFOUND**: Indicates whether the claim was fraudulent (`Yes`/`No`).

## Methodology  
### Data Preprocessing  
- Handled missing values and encoded categorical variables.  
- Used techniques like IQR for outlier detection and SMOTE for handling class imbalance.  

### Hyperparameter Tuning  
- **Decision Tree**:  
  - Tuned parameters: `min_samples_leaf`, `max_depth`, `criterion`.  
  - Best Accuracy: ~84.85%.  
- **Random Forest**:  
  - Tuned parameters: `min_samples_leaf`, `max_depth`, `n_estimators`, `max_features`.  
  - Best Accuracy: ~80.71%.  

### Machine Learning Models  
Implemented multiple classification algorithms:  
- Decision Tree  
- Random Forest  
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Naïve Bayes  

### Performance Metrics  
Evaluated models using metrics like:  
- Accuracy  
- Precision  
- Recall  
- F1-Score  

## Results  
- Achieved high accuracy with tuned Decision Tree and Random Forest models.  
- Explored trade-offs between model interpretability and performance.  

## Repository Contents  
- `data/`: Training and testing datasets.  
- `notebooks/`: Jupyter notebooks for EDA, preprocessing, and modeling.  
- `src/`: Python scripts for automation and reproducibility.  
- `reports/`: Detailed performance reports and visualizations.  

## Conclusion  
This project demonstrates the application of machine learning and hyperparameter tuning in fraud detection. It emphasizes the importance of balancing accuracy with interpretability to ensure business applicability.  

## Video Report Explanation

https://asu.zoom.us/rec/share/wUEWEFDQVmxAkJrIvvpeMU8ZoPa1r638VBuCzrIOWYpJZR9zzzqu9DNVsJ7fzj4T.mdWQ0dc4x_StZPAs?startTime=1731298535000

Passcode: iTD#Y.7=
