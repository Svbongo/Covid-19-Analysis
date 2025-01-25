# 🦠 COVID-19 Analysis and Forecasting

## 📊 Project Overview

This project, **"Future Predictions of COVID-19,"** was conducted as part of a Data Science competition during my studies at **NMIMS Mukesh Patel School of Technology Management & Engineering.** The project aimed to analyze COVID-19 trends in India and predict future cases using **Python, Power BI, and the SARIMA model** for time-series forecasting.

---

## 👥 Team Members

- **Soham Vasudeo**
- **Ritika Shetty**

---

## 🎯 Goal / Problem Statement

The objective of this project was to leverage knowledge from **Python Programming, Business Visualization, and Statistics & Analytics** to analyze COVID-19 data and forecast future cases using the **SARIMA (Seasonal Auto Regressive Integrated Moving Average)** model.

---

## 🗂 Dataset Details

The datasets used include COVID-19 statistics for India covering:

1. **COVID-19 Cases Data**
   - States/Union Territories
   - Dates and times
   - Confirmed cases (Indian and Foreign Nationals)
   - Cured cases
   - Deaths

2. **COVID-19 Vaccination Data**
   - Total doses administered
   - First and second dose distribution
   - Gender-wise breakdown (Male, Female, Transgender)
   - Vaccine types: Covaxin, Covishield, Sputnik V
   - Age-group analysis (18-44, 45-60, 60+ years)
   - Adverse Events Following Immunization (AEFI)

---

## 🔍 Data Analysis Steps

1. **Data Cleaning & Preprocessing**
   - Removal of missing values and inconsistencies.
   - Conversion of date columns to proper datetime format.
   - Duplicate record handling and standardization.

2. **Exploratory Data Analysis (EDA)**
   - Calculated growth rates of cases for each state.
   - Mortality and recovery rates computation.
   - Created various visualizations, including:
     - Geo Maps for state-wise analysis.
     - Time-series plots of cases over time.
     - Scatter plots for mortality and recovery rate comparison.

3. **Modeling Approach**
   - Used the **SARIMA** model to forecast COVID-19 cases.
   - Steps included:
     - Autocorrelation and Partial Autocorrelation analysis.
     - Grid search for optimal ARIMA parameters.
     - Model fitting and evaluation.

---

## 📈 Dashboards

We developed two interactive dashboards using **Power BI:**

### **1. COVID Cases Dashboard**
- **Summary:**  
  - Overview of active cases, confirmed cases, recovered cases, deaths, and total doses administered.  
- **Map-based Analytics:**  
  - Visual representation of active cases across states with hover tooltips.  
- **Recovery and Mortality Rates:**  
  - Line charts showing mortality and recovery trends over time.

### **2. COVID Vaccination Dashboard**
- **Gender-wise Analysis:**  
  - Donut chart representation of vaccine doses administered across genders.  
- **Total Dose vs AEFI:**  
  - Bar chart for total dose distribution with adverse event tracking.  
- **Doses Administered Analysis:**  
  - Comparison of first vs second doses in top-performing states.  
- **Age-wise Analysis:**  
  - Pie chart breakdown for different age groups.  
- **Date Filters:**  
  - Filter data based on year and month to analyze trends over time.

---

## 🛠 Tools & Technologies Used

- **Python (Pandas, NumPy, Statsmodels, Matplotlib, Seaborn)**
- **Power BI for Dashboard Visualization**
- **Time-Series Forecasting with SARIMA Model**

---

## 🚀 Key Insights and Results

- **Mortality Trends:** Mortality rate peaked at **3.14%** during early 2020 and declined to **1.32%** by mid-2021.
- **Recovery Trends:** Recovery rate improved to **97%** after the first vaccination wave.
- **Vaccination Impact:** States with higher vaccination rates showed lower case growth and improved recovery trends.
- **AEFI Observations:** Adverse events were minimal compared to total doses administered.

---

## 📂 Project Structure

```
.
├── data/
│   ├── covid_19_india.csv
│   ├── covid_analysis.csv
│   ├── covid_vaccine_statewise.xlsx
│   ├── StatewiseTestingDetails.csv
│   ├── Covid Analysis - NMIMS.xlsx
│
├── dashboards/
│   ├── Covid Analysis - NMIMS.pbix
│
├── README.md
```

---

## 📊 Visuals

![image](https://github.com/user-attachments/assets/7b1a7fe5-6637-4a8a-bf19-37b9780a6a51)

![image](https://github.com/user-attachments/assets/8d8ef647-ff72-4c0b-b86d-f5df9f720603)

---

## 🏆 Achievements

- Successfully conducted in-depth data analysis and forecasting using real-world COVID-19 data.
- Developed interactive dashboards to assist policymakers in better decision-making.
- Improved forecasting accuracy by fine-tuning SARIMA parameters.
