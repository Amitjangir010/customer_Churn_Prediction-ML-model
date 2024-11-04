# 🏦 Customer Churn Prediction Model

An intelligent machine learning model that predicts whether a bank customer will leave (churn) or stay with the bank based on various customer attributes and behaviors.

## 📊 Project Overview

This project uses machine learning to help banks identify customers who are likely to leave their services. By analyzing patterns in customer data like age, balance, credit score etc., the model can predict customer churn with 85.15% accuracy using Gradient Boosting.

## 🎯 Key Features

- **High Accuracy**: Achieves 85.15% prediction accuracy using Gradient Boosting
- **Multiple Models Tested**: Compared performance of 5 different ML algorithms
- **Data Analysis**: Comprehensive EDA with visualizations
- **Easy to Use**: Simple interface for making predictions
- **Production Ready**: Includes data preprocessing and model evaluation

## 🔍 Model Comparison Results

| Model | Accuracy |
|-------|----------|
| Gradient Boosting | 85.15% |
| SVM | 82.90% |
| Random Forest | 82.10% |
| Logistic Regression | 79.45% |
| Decision Tree | 79.35% |

## 📈 Key Insights

- Age and Account Balance are strong predictors of churn
- Credit Score shows no significant correlation with churn
- Geography plays a role in customer retention
- Salary level does not impact churn significantly

## 🛠️ Technologies Used

- **Python 3.9+**
- **Key Libraries**: 
  - Pandas & NumPy for data manipulation
  - Scikit-learn for machine learning
  - Seaborn & Matplotlib for visualization
  - Jupyter Notebook for development

## 📋 Dataset Features

- **Customer Info**: Age, Gender, Geography
- **Account Details**: Balance, NumOfProducts
- **Status**: Credit Score, HasCrCard, IsActiveMember
- **Target Variable**: Exited (0=Stay, 1=Leave)

## 🔄 Model Pipeline

1. Data Preprocessing
   - Handle missing values
   - Feature encoding
   - Feature scaling

2. Model Training
   - Train-test split (80-20)
   - Model selection
   - Hyperparameter tuning

3. Evaluation
   - Accuracy scoring
   - Model comparison
   - Performance validation

## 🎯 Future Improvements

- [ ] Add feature importance analysis
- [ ] Implement cross-validation
- [ ] Deploy as web application
- [ ] Add more evaluation metrics
- [ ] Include cost-benefit analysis

## 🙏 Acknowledgments

- Dataset from Kaggle
- Inspired by real banking industry challenges
---
Made with ❤️ by Amit Jangir
