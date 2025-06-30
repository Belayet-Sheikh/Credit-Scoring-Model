# 🏦 Credit Scoring Model | Predicting Loan Defaults

**Author**: Sheikh Belayet Mahmood | **GitHub**: [link] |

## 📌 Overview
A machine learning model to predict loan defaults using:
- Income
- Loan amount  
- Credit history  
- Loan term  

**Goal**: Help banks assess risk and reduce financial losses.

## 🔍 Key Features
- Data preprocessing (missing value imputation, log transforms).
- Explored correlations (credit history has -0.26 correlation with defaults).
- Tested 3 models: **Logistic Regression**, **Random Forest**, **Decision Tree**.

## 📊 Results Summary
| Model               | Accuracy | Precision (Default=1) | Recall (Default=1) |
|---------------------|----------|-----------------------|--------------------|
| Logistic Regression | 65.2%    | 0.67                  | 0.37               |
| Random Forest       | 60.0%    | 0.54                  | 0.44               |
| Decision Tree       | 55.2%    | 0.47                  | 0.43               |

**Best Model**: Logistic Regression (65.2% accuracy), but needs recall improvement.

## 🛠 Installation & Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/credit-scoring-model.git