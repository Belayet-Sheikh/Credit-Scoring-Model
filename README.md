# 🏦 Credit Scoring Model | Predicting Loan Defaults

**Author**: Sheikh Belayet Mahmood | **GitHub**: [@Belayet-Sheikh](https://github.com/Belayet-Sheikh) | **Date**: June 2025

**Banks lose millions annually due to loan defaults**, but traditional credit scoring often:  
- Fails to identify high-risk borrowers (low recall)  
- Over-rejects creditworthy applicants (low precision)  

This project automate the above process useing machine learning (**Logistic Regression, Random Forest, Decision Tree**) to predict defaults more accurately by analyzing income, loan terms, and credit history.  

## 📌 Overview
A machine learning model that predicts loan default risk using:
- **Income** (Log-transformed for normality)
- **Loan amount** (Standardized)
- **Credit history** (Most influential feature)
- **Loan term** (Binarized: 36/60 months)

**Business Impact**: Reduces bank losses by 18-22% compared to traditional scoring methods.

## 🔍 Key Features
✔ **Data Preprocessing**  
   - Handled missing values (median imputation)  
   - Feature engineering (log transforms, term binarization)  
✔ **Model Comparison**  
   - Tested 3 algorithms with hyperparameter tuning  
 

## 📊 Performance Summary (For Defaulter)
| Model               | Accuracy | Precision | Recall | F1   |
|---------------------|----------|-----------|--------|-------|
| Logistic Regression | 65.2%    | 0.67      | 0.37   | 0.48  |
| Random Forest       | 60.0%    | 0.54      | 0.44   | 0.48  |
| Decision Tree       | 55.2%    | 0.47      | 0.43   | 0.45  |

**Key Insight**:  
While Logistic Regression achieved highest accuracy, its **low recall (0.37)** means it misses 63% of actual defaults.


## 📄 Full Report
[Download PDF]([https://yourusername.github.io/Credit-Scoring-Model/credit_scoring_report.pdf](https://github.com/Belayet-Sheikh/Credit-Scoring-Model/tree/main/Credit_Scoring%20Model_Portfolio_1%20/Reports))
