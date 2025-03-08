# 🏠 Housing Price Prediction

Predicting housing prices using machine learning models like Linear Regression, Random Forest, and XGBoost.

## 📌 Project Overview

This project aims to predict house prices based on various features such as square footage, number of bedrooms, location, and more. The dataset is preprocessed, and multiple regression models are evaluated to determine the best-performing model.

## 📂 Dataset

- **Dataset Name:** Housing Price Dataset
- **Number of Records:** 50,000 rows, 15 columns
- **Features:** Square footage, location, number of rooms, year built, etc.
- **Target Variable:** Price

## 🛠 Technologies Used

- Python
- Pandas, NumPy (Data Manipulation)
- Matplotlib, Seaborn (Visualization)
- Scikit-learn, XGBoost (Modeling)
- GridSearchCV (Hyperparameter Tuning)

## 📊 Modeling Approach

1. **Data Preprocessing:** Handling missing values, outliers, feature scaling.
2. **Exploratory Data Analysis (EDA):** Correlation heatmaps, distributions.
3. **Feature Engineering:** Transforming and selecting features.
4. **Model Training & Evaluation:**
   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor
5. **Hyperparameter Tuning:** GridSearchCV to optimize model performance.
6. **Performance Metrics:**
   - R² Score
   - RMSE (Root Mean Squared Error)
   - MAE (Mean Absolute Error)

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/Lintojoseph01/Housing-Price-Prediction-.git
   cd Housing-Price-Prediction-
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or script to train and evaluate the models.

## 🔥 Results

| Model            | R² Score | RMSE  | MAE  |
|-----------------|---------|------|------|
| Linear Regression | 0.75    | 45.12 | 30.55 |
| Random Forest    | 0.88    | 30.43 | 22.18 |
| XGBoost         | 0.91    | 25.67 | 19.87 |

**Best-performing model:** XGBoost Regressor

## 🌟 Future Improvements

- Experiment with feature selection techniques.
- Try advanced hyperparameter tuning (Bayesian Optimization, Random Search).
- Include additional features such as neighborhood rating, school proximity, etc.

## 📖 Author
**Linto Joseph**

👥 **Contributors:** Open for contributions! Feel free to fork and create pull requests.

🛠️ **License:** MIT

