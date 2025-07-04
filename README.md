# 🌍 Country-wise GDP Prediction using Linear Regression

This project performs **country-wise GDP forecasting** using historical GDP data. The dataset contains annual GDP figures for multiple countries from 1960 to 2020. The project uses **Linear Regression** to predict GDP for the years 2021 to 2025 and visualizes both historical and predicted trends.

---

## 📌 Project Features
- Reads and processes multi-year GDP data from a CSV file.
- Filters data for each country individually.
- Removes missing or invalid entries automatically.
- Applies **Linear Regression** to forecast GDP trends.
- Visualizes each country's historical and predicted GDP.
- Saves the future GDP predictions in a structured CSV file.

---

## 🚀 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📂 Dataset Structure
Your CSV should include:
- **Country Name:** The country being analyzed.
- **Code:** Country code (optional for analysis).
- **Year columns:** GDP data for each year from 1960 to 2020.

> Example:
> | Country Name | Code | 1960 | 1961 | ... | 2020 |
> |--------------|------|------|------|-----|------|

---

## 🛠️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/gdp-prediction.git
cd gdp-prediction
