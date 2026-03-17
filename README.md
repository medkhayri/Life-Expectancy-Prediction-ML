# Global Life Expectancy Prediction Analysis 🌍📊

This project explores the determinants of human longevity using **Machine Learning** techniques. Based on data from the World Health Organization (WHO), the study models the interactions between economic, social, and health factors to predict life expectancy across different countries.

## 🚀 Project Overview
The goal of this project is to build a predictive model that estimates life expectancy with high accuracy. We navigated through the entire Data Science lifecycle, from raw data cleaning to advanced model optimization.

## 🛠️ Technologies Used
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Tools:** Jupyter Notebook, Ipywidgets (for interactive UI)

## 📊 Key Methodology
1. **Data Preprocessing:** Handled missing values (imputation) and analyzed the impact of outliers using IQR.
2. **Exploratory Data Analysis (EDA):** Visualized correlations between health indicators (GDP, Schooling, Mortality) and life expectancy.
3. **Model Development:** Compared three different scenarios:
    * Linear Regression (Baseline)
    * K-Nearest Neighbors (KNN) - Optimized with K-tuning
    * **Decision Tree Regressor (Champion Model)**

## 🏆 Results
The **Decision Tree** model emerged as the champion, achieving:
* **R² Score:** 0.9268 (92.6% accuracy)
* **RMSE:** 2.5186 years (Average error)

## 💻 Interactive Dashboard
The project includes an interactive prediction interface where users can input specific country metrics (GDP, Mortality, etc.) to get an instant life expectancy prediction.

---
*Developed by **Mohamed KHAYRI** as part of the AI Module Project.*
