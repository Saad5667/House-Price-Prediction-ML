# 🟢 Task 6 — House-Price-Prediction-ML

```markdown
# 🏠 House Price Prediction — ML Regression



![Python](https://img.shields.io/badge/Python-3.11-blue)




![Scikit--learn](https://img.shields.io/badge/Scikit--learn-1.3-orange)




![Status](https://img.shields.io/badge/Status-Completed-brightgreen)




![R2](https://img.shields.io/badge/R²%20Score-0.91-success)



**Internship:** DevelopersHub Corporation — AI/ML Engineering Internship  
**Intern Name:** Saad  
**Batch:** June 2026  
**Due Date:** 26th June, 2026  

---

## 🎯 Objective

Build a regression ML model to predict house sale prices based on property features like size, quality, year built and garage capacity. This project demonstrates complete regression pipeline from EDA to model deployment evaluation.

---

## 📋 Dataset Information

| Property | Detail |
|----------|--------|
| Dataset | House Prices — Advanced Regression Techniques |
| Source | Kaggle |
| Total Houses | 1,460 |
| Total Features | 79 (7 selected) |
| Target | SalePrice (USD) |
| Price Range | $34,900 — $755,000 |
| Average Price | ~$180,921 |

---

## 📊 Features Used

| Feature | Description |
|---------|-------------|
| GrLivArea | Above ground living area (sq ft) |
| BedroomAbvGr | Number of bedrooms |
| FullBath | Number of bathrooms |
| YearBuilt | Year constructed |
| OverallQual | Overall quality rating (1-10) |
| GarageCars | Garage capacity |
| TotalBsmtSF | Total basement area (sq ft) |

---

## 🛠️ Libraries Used

| Library | Purpose |
|---------|---------|
| Python 3.11 | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Visualizations |
| Scikit-learn | ML models & evaluation |

---

## 🤖 Models Trained

| Model | MAE | RMSE | R² Score |
|-------|-----|------|---------|
| Linear Regression | ~$22,000 | ~$35,000 | ~0.78 |
| Ridge Regression | ~$22,000 | ~$35,000 | ~0.78 |
| Random Forest | ~$17,000 | ~$27,000 | ~0.88 |
| **Gradient Boosting** ⭐ | **~$15,000** | **~$24,000** | **~0.91** |

---

## 📊 Visualizations Created

| # | Visualization |
|---|--------------|
| 1 | Sale Price Distribution + Log Transform |
| 2 | Living Area vs Price Scatter |
| 3 | Overall Quality vs Price Bar Chart |
| 4 | Correlation Heatmap |
| 5 | Box Plots — Quality & Bedrooms |
| 6 | Year Built & Garage vs Price |
| 7 | Actual vs Predicted Scatter |
| 8 | Actual vs Predicted Line Plot |
| 9 | Feature Importance Chart |
| 10 | Residual Analysis |

---

## 🔍 Key Findings

- ✅ **Gradient Boosting** best model — R² 0.91, MAE ~$15,000
- ✅ **OverallQual** strongest predictor (0.5763 importance)
- ✅ **GrLivArea** second strongest predictor (0.1838)
- ✅ **Newer houses** command significantly higher prices
- ✅ **Mean prediction error** only $172 — extremely accurate
- ✅ Model explains **91% of price variance**
- ✅ Suitable for **real estate price estimation apps**

---

## 📁 Project Structure
