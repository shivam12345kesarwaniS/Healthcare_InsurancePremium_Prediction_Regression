# Insurance Premium Prediction Project

This project aims to predict the annual premium amount for insurance customers using various features, such as age, employment status, income level, and medical history. By leveraging machine learning techniques, the goal is to create a model that accurately predicts premium amounts.

## Project Overview
- **Objective**: The goal is to predict the annual insurance premium for customers based on demographic, financial, and medical data.
- **Datasets**:
  - `customers.csv`: Contains customer demographic information such as age, employment status, and income.
  - `medical_history.csv`: Provides customer medical history, including any pre-existing conditions.
  - `insurance_plans.csv`: Details about the insurance plans, including the plan type (Bronze, Silver, Gold) and the corresponding premium amounts.

## Key Highlights
- **Predictive Model Development**: Developed a predictive model to estimate health insurance premiums using regression techniques, achieving an **R-squared (R²) of 98%** and **RMSE of 1250** after tuning the best parameters with **Grid Search CV** in the XGBoost model.
  
## Feature Engineering
- **Health Data Processing**: Performed feature engineering on health data, calculated risk scores, encoded text columns, and conducted feature selection based on a **correlation matrix** and **Variance Inflation Factor (VIF)** to remove multicollinearity.
  
## Model Building and Optimization
- **Regression Models**: Implemented multiple regression algorithms including **Linear Regression**, **Ridge**, and **XGBoost** to predict premiums.
- **Hyperparameter Tuning**: Applied **Grid Search CV** and **cross-validation** to tune hyperparameters for optimal model performance, ensuring better accuracy and generalization.

## Model Evaluation
- Achieved **R-squared (R²): 98%** and **RMSE: 1250** for the best model using XGBoost with tuned parameters.
  
## Tools and Techniques Used
- **Pandas**: For data manipulation and cleaning.
- **Scikit-learn**: For building and evaluating regression models.
- **XGBoost**: For optimizing premium predictions.
- **Grid Search CV**: For hyperparameter tuning.
- **Matplotlib/Seaborn**: For visualizing data distributions and relationships.

# Healthcare_InsurancePremium_Prediction_Regression
