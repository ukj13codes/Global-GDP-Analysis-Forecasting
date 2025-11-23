# 🌍 Global GDP Analysis & Forecasting

### 📘 Project Overview
This project performs an end-to-end **EDA + Machine Learning Forecasting** workflow on global GDP data. It demonstrates core skills in time-series cleaning, visual analysis, and regression modeling applied to real-world economic indicators.

---

### 🎯 Objectives
* **Trend Analysis:** Analyze long-term GDP trends across multiple countries.
* **Data Quality:** Identify missing years and inconsistent time-series values.
* **Visualization:** Visualize global GDP trajectories using interactive charts.
* **Forecasting:** Predict future GDP using regression-based models.
* **Evaluation:** Assess model performance using **RMSE** and **R² Score**.

---

### 🛠 Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn, **Plotly** (Interactive)
* **Machine Learning:** Scikit-learn (Polynomial Regression, Random Forest Regressor)
* **Environment:** Google Colab / Jupyter Notebook

---

### 🔧 Data Engineering & EDA
**1. Data Cleaning**
* Handled missing GDP values and inconsistent years.
* Reformatted dataset into a clean time-series structure suitable for modeling.
* Filtered countries with sufficient historical data for reliable forecasting.

**2. Exploratory Data Analysis**
* Plotted GDP trends for multiple countries to identify growth patterns.
* Compared growth trajectories of major economies (e.g., India vs. China).
* Used **interactive Plotly charts** to allow users to explore country-level changes dynamically.

---

### 🤖 Forecasting Models
We implemented and compared two prediction approaches:

**1️⃣ Polynomial Regression**
* *Strength:* Captures global economic growth curves effectively.
* *Performance:* Performs well for countries with steady, exponential GDP trends.

**2️⃣ Random Forest Regressor**
* *Strength:* Handles non-linear patterns and complex data structures.
* *Performance:* More flexible for fluctuating economic data but limited in extrapolating long-term future trends.

**📏 Evaluation Metrics used:**
* **RMSE** (Root Mean Squared Error)
* **R² Score**

---

### 📊 Key Insights
* **Model Suitability:** Countries with a stable upward trend were forecasted more accurately by Polynomial Regression.
* **Volatility Handling:** Tree-based models (Random Forest) excelled in cases with irregular GDP behavior but struggled with long-range forecasting.
* **Data Gaps:** The dataset showed missing years for many developing countries, highlighting the importance of data validation.
* **Forecast Limitations:** While models provide directional trends, exact future values are subject to external macroeconomic factors.

---

### 📁 Repository Contents
* `Global_GDP_Forecasting.ipynb`: Full analysis notebook.
* `gdp.csv`: Historical GDP dataset.
* `README.md`: Project documentation.

---

### ✅ Quick Summary
This project demonstrates competency in:
* **Time-Series Analysis:** Handling temporal data structures.
* **Machine Learning:** Applying Regression and Random Forest models.
* **Data Cleaning:** Assessing and fixing data quality issues.
* **Visual Storytelling:** Creating interactive economic visualizations.
