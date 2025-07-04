# GHG Emission Prediction

**Author:** Neyanta Rai  
**Student ID:** STU67ece4362af921743578166  

## 🔍 Project Overview

This project aims to build a machine learning model to predict greenhouse gas (GHG) emission factors across various industries and commodities in the US. It leverages multi-year data and multiple environmental and economic indicators to ensure accurate and scalable predictions.

---

## 🎯 Learning Objectives

- Understand greenhouse gas emission factors across industries and commodities.
- Learn how to preprocess and analyze multi-year emissions data.
- Apply machine learning techniques to predict emissions based on various features.
- Evaluate model performance using regression metrics.

---

## 🎯 Goal

Build an accurate predictive model to estimate **Supply Chain Emission Factors with Margins** using relevant features like substance type, units, source, and quality metrics.

---

## 🛠 Tools and Technologies Used

- **Languages & Libraries**: Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn
- **ML Algorithms**: Random Forest Regressor, Linear Regression
- **Visualization**: Count plots, Histograms, Correlation Heatmaps
- **Other Tools**: Jupyter Notebook, Excel

---

## 🧪 Methodology

### 1. **Data Collection**
- Collected emission factor data from Excel sheets (2010–2016).
- Data covers both **commodities** and **industries**.

### 2. **Preprocessing**
- Merged yearly sheets into a single DataFrame.
- Dropped unused or null columns (e.g., `Unnamed: 7`).
- Encoded categorical features (`Substance`, `Unit`, `Source`) as integers.

### 3. **Exploratory Data Analysis**
- Analyzed the distribution of the target variable.
- Identified top 10 emitting sectors.
- Generated correlation heatmaps to identify relationships.

### 4. **Model Building**
- Scaled features using `StandardScaler`.
- Trained a **RandomForestRegressor**.
- Compared performance with **LinearRegression**.

---

## ❓ Problem Statement

There is a critical need to **quantify and predict GHG emission factors** across various economic sectors to support sustainable decision-making. However, inconsistent datasets and complex interactions make it difficult to build accurate prediction models.

---

## ✅ Solution

- Aggregated and standardized multi-year emissions data.
- Applied feature engineering using Data Quality (DQ) metrics.
- Built and trained a **Random Forest model**:
  - 📉 **RMSE**: `0.0060`
  - 📈 **R² Score**: `0.9993` (very high accuracy)
- Compared results with a **Linear Regression** baseline model.

---

## 📸 Screenshot of Output

> *(Include relevant visualizations here, such as:)*  
> - Correlation heatmap  
> - Top 10 emitting industries bar chart  
> - Count plots for Substances/Units  
> - Prediction output sample

---

## 📌 Conclusion

- Random Forest model achieved **excellent accuracy** in predicting emission factors.
- **Feature engineering and data scaling** significantly improved performance.
- This solution is **scalable** and suitable for real-time emissions monitoring and policy planning.

---

## 🔗 GitHub Repository

[Click here to view the GitHub project](https://github.com/Neyanta-Rai/GHG_Emission_Pridiction.git)

