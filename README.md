# 🏠 Analysis and Model Deployment on Key Factors That Influence US Home Prices

This repository contains a comprehensive data science project aimed at understanding the **impact of macroeconomic and demographic factors** on **US home prices**. The project involves **data collection, cleaning, analysis, modeling, and evaluation** using various machine learning models.

---

## 📁 Project Structure

- **`Data_Preparation.ipynb`**:  
  This notebook performs **ETL operations** to collect and prepare data from multiple sources, primarily the [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/). The monthly data is cleaned, interpolated, and merged to form a unified dataset for modeling.

- **`Analysis and model deployoment.ipynb`**:  
  This notebook performs **exploratory data analysis (EDA)**, feature correlation, model training, and evaluation. Several regression models are applied and compared based on **R² Score** and **Mean Squared Error**.

---

## 📊 Features Considered

The study evaluates how the following factors influence home prices:

- Unemployment Rate
- Employment Rate
- Per Capita GDP
- Median Household Income
- Construction Prices
- Consumer Price Index (CPI)
- Interest Rates (Federal Funds Rate)
- Working Population
- Urban Population
- Housing Subsidies
- Number of Households

Home prices are represented using the **S&P/Case-Shiller U.S. National Home Price Index (CSUSHPISA)**.

---

## 🛠️ Tools and Technologies

- Python (pandas, numpy, seaborn, matplotlib)
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📈 Models Used

The following models were trained and evaluated:

- **Linear Regression**
- **ElasticNet**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **Support Vector Regressor (SVR)**

Each model's performance was measured using:
- **R² Score**
- **Mean Squared Error (MSE)**

---

## 📌 Key Highlights

- Efficient **data integration and preprocessing** from heterogeneous sources.
- Comprehensive **EDA** including correlation analysis.
- Application of multiple regression models to identify the **most influential variables**.
- **Random Forest** and **Gradient Boosting** emerged as the top performers with the highest accuracy.

---

## 📂 Data Source

Most of the data used in this project is publicly available from:
👉 [https://fred.stlouisfed.org/](https://fred.stlouisfed.org/)

---

## 📬 Contact

For questions or collaborations, feel free to reach out to:
mauryaadarsh975@gmail.com

---

⭐️ Don’t forget to **star** this repo if you found it helpful!
