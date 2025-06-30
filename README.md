# house-price-analysis
🔗 Also available in [Українська](README_ua.md)

This project is aimed at predicting house prices using a publicly available dataset from Kaggle. The goal is to build a simple but effective regression model with basic data preprocessing.

## 📁 Project Structure

```
├── data/ → Training dataset (CSV)
├── notebooks/ → Jupyter Notebook with code and analysis
├── README.md → Main project description (this file)
├── README_ua.md → Ukrainian version of README
```

## ✅ Current Progress

- Basic EDA for available numeric features
- Handling of missing values
- Encoding of categorical variables
- LightGBMRegressor model trained on the dataset
- Feature importance visualization
- RMSE calculated on training-validation split

⚠️ At this stage only one model (LGBM) is used. Further model tuning and validation on test data planned in later stages.

## 📦 Libraries Used

- pandas
- numpy
- scikit-learn
- lightgbm
- matplotlib / seaborn (light usage)

## 📚 Dataset

Data: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

Only the training dataset is used. Evaluation on test data is not included due to lack of target values.

---

> 🛠️ Work in progress – planning to add model comparison, parameter tuning, and predictions evaluation in the future.
```
