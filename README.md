# Medical Insurance Cost Prediction - Linear Regression

## Project Overview
This project implements a linear regression model to predict medical insurance charges based on patient characteristics including age, BMI, smoking status, and region.

## Dataset
Source: [Medical Insurance Dataset on Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)

Features:
- age: Age of primary beneficiary
- sex: Gender (male/female)
- bmi: Body Mass Index
- children: Number of dependents
- smoker: Smoking status
- region: Residential area
- charges: Medical costs (target variable)

## Technologies Used
- Python 3.x
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for visualization
- Scikit-learn for machine learning

## Key Findings
- Smoking status is the strongest predictor of insurance costs
- Age and BMI show significant positive correlation with charges
- Model achieves R² score of ~0.78 on test data

## Files
- `insurance_linear_regression.ipynb`: Main Jupyter notebook with complete analysis
- `insurance.csv`: Dataset file
- `README.md`: Project documentation

## How to Run
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook

## Results
The linear regression model successfully predicts insurance charges with:
- MAE: ~$4,200
- RMSE: ~$6,000
- R²: ~0.78

## Future Improvements
- Feature engineering (interaction terms)
- Advanced models (Random Forest, Gradient Boosting)
- Additional features (medical history, lifestyle factors)
