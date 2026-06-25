# House Price Prediction — ML Regression

**Internship:** DevelopersHub Corporation — AI/ML Engineering Internship
**Intern Name:** Saad
**Batch:** June 2026
**Due Date:** 26th June, 2026

---

## Objective

Build a regression ML model to predict house sale prices based on property features like size, quality, year built and garage capacity.

---

## Dataset Information

- **Dataset:** House Prices Advanced Regression Techniques
- **Source:** Kaggle
- **Total Houses:** 1,460
- **Features Used:** 7
- **Target:** SalePrice in USD
- **Price Range:** $34,900 to $755,000
- **Average Price:** $180,921

---

## Features Used

- GrLivArea — Above ground living area
- BedroomAbvGr — Number of bedrooms
- FullBath — Number of bathrooms
- YearBuilt — Year constructed
- OverallQual — Overall quality rating
- GarageCars — Garage capacity
- TotalBsmtSF — Total basement area

---

## Libraries Used

- Python 3.11
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Models Trained

- Linear Regression — R2: 0.78
- Ridge Regression — R2: 0.78
- Random Forest — R2: 0.88
- Gradient Boosting — R2: 0.91 (Best Model)

---

## Visualizations Created

1. Sale Price Distribution and Log Transform
2. Living Area vs Price Scatter Plot
3. Overall Quality vs Price Bar Chart
4. Correlation Heatmap
5. Box Plots — Quality and Bedrooms
6. Year Built and Garage vs Price
7. Actual vs Predicted Scatter Plot
8. Actual vs Predicted Line Plot
9. Feature Importance Chart
10. Residual Analysis

---

## Key Findings

- Gradient Boosting best model with R2 score 0.91
- OverallQual is strongest predictor with 0.5763 importance
- GrLivArea is second strongest predictor
- Newer houses command higher prices
- Mean prediction error only $172
- Model explains 91% of price variance

---

## How to Run

pip install pandas numpy matplotlib seaborn scikit-learn

jupyter notebook task6_house_price_prediction.ipynb

---

## Project Structure

- task6_house_price_prediction.ipynb
- train.csv
- README.md

---

DevelopersHub Corporation — AI/ML Engineering Internship 2026
