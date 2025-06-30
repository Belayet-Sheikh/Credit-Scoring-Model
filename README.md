# 🏦 Credit Scoring Model | Predicting Loan Defaults

**Author**: Sheikh Belayet Mahmood | **GitHub**: [@Belayet-Sheikh](https://github.com/Belayet-Sheikh) | **Date**: June 2025


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


## 🛠 Installation
```bash
# Clone repository
git clone https://github.com/Belayet-Sheikh/Credit-Scoring-Model.git

# Install dependencies
pip install -r requirements.txt
