# Resale Price Estimation of Flats in Singapore

## Project Overview
This project builds an end-to-end machine learning pipeline to estimate the resale price of flats in Singapore.

The objective is to support real-estate decision-making by predicting property prices based on features such as location, flat type, floor area, lease information, and other housing attributes.

---

## Dataset
The project combines two resale flat price datasets covering:
- 2015–2016
- 2017 onwards

After preprocessing and merging, the final dataset contains 206,737 rows and 11 columns.

---

## Approach
- Data collection and merging of two historical datasets
- Data cleaning and preprocessing
- Feature encoding and train/validation/test split
- Model comparison using:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Hyperparameter tuning with GridSearchCV

---

## Results
The Random Forest model achieved the best performance.

### Validation set
- MSE: 954,298,482.51
- RMSE: 30,891.72
- R²: 0.9651

### Test set
- MSE: 902,634,034.72
- RMSE: 30,043.87
- R²: 0.9673

These results show strong predictive performance and good generalization.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Repository Structure
```text
Resale-Price-Prediction/
├── README.md
├── resale_price_prediction.ipynb
