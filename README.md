# Healthcare-Capacity-Analytics
End-to-End Healthcare Capacity Analytics using Python, Pandas, NumPy and Matplotlib with Healthcare KPIs, Forecasting and Business Intelligence.

# 🏥 Healthcare Capacity Analytics: Monitoring & Forecasting the HHS Unaccompanied Alien Children (UAC) Care System (2023–2025)

# 📌 Project Overview
Healthcare organizations require continuous monitoring of operational capacity to ensure efficient resource utilization and timely care delivery. This project analyzes historical operational data from the **HHS Unaccompanied Alien Children (UAC) Program** to monitor healthcare capacity, evaluate system performance, identify operational stress, and perform basic forecasting.

Using **Python**, **Pandas**, **NumPy**, and **Matplotlib**, this project transforms raw operational data into meaningful business insights through data cleaning, feature engineering, exploratory data analysis (EDA), KPI development, advanced analytics, and forecasting.

The notebook is designed as an end-to-end Data Analyst portfolio project that follows industry-standard analytical practices.

---

# 🎯 Problem Statement

Although daily operational data is collected, the HHS currently lacks a centralized analytical framework to continuously assess:

- Total healthcare system load
- Capacity utilization
- Balance between intake and discharge
- Capacity stress periods
- Sustainability of care delivery

Without structured analytics, decision-making becomes reactive, increasing the risk of overcrowding, delayed care, and strain on healthcare infrastructure.

---

# 🎯 Business Objectives

## Primary Objectives

- Quantify daily healthcare system load
- Compare CBP and HHS operational responsibility
- Monitor transfers and discharges
- Detect periods of capacity strain
- Measure backlog accumulation
- Forecast future healthcare demand

## Secondary Objectives

- Support healthcare staffing decisions
- Improve shelter planning
- Enable data-driven policymaking
- Enhance humanitarian response monitoring

---

# 📂 Dataset Description

The dataset contains daily operational information for the HHS Unaccompanied Alien Children Program.

### Key Variables

- Date
- Children Apprehended by CBP
- Children in CBP Custody
- Children Transferred to HHS
- Children in HHS Care
- Children Discharged from HHS

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# 🔄 Project Workflow

```
Raw Dataset
      │
      ▼
Data Loading
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Advanced Analytics
      │
      ▼
Healthcare KPI Development
      │
      ▼
Forecasting
      │
      ▼
Business Insights
      │
      ▼
Recommendations


---



# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Imported required libraries
- Loaded dataset
- Checked data types
- Identified missing values
- Removed duplicate records
- Converted date column into datetime format
- Renamed columns
- Converted numeric columns into appropriate data types

---

# ⚙️ Feature Engineering

The following features were created:

- Total System Load
- Net Daily Intake
- Daily Growth Rate
- 7-Day Rolling Average
- 14-Day Rolling Average
- Backlog Status
- Capacity Ratio
- Transfer Efficiency
- Discharge Offset Ratio
- Year
- Month
- Quarter
- Week Number
- Day Name

---

# 📊 Exploratory Data Analysis (EDA)

The project includes extensive exploratory data analysis covering:

### Univariate Analysis

- Histogram
- Box Plot
- Pie Chart

### Bivariate Analysis

- Line Chart
- Multiple Line Plot
- Scatter Plot
- Bar Chart
- Horizontal Bar Chart

### Multivariate Analysis

- Area Chart
- Rolling Average Analysis
- Growth Rate Trend
- Transfer Efficiency Trend
- Discharge Ratio Trend

---

# 📈 Healthcare KPIs

The following Key Performance Indicators (KPIs) were calculated:

- Total System Load
- Average Daily Load
- Peak Healthcare Load
- Average Net Intake
- Capacity Ratio
- Transfer Efficiency
- Discharge Offset Ratio
- Backlog Indicator
- Growth Rate
- Rolling Average

---

# 📉 Advanced Analysis

Advanced analytical techniques include:

- GroupBy Analysis
- Sorting
- Filtering
- Aggregation
- Pivot Tables
- Value Counts
- NumPy Statistical Analysis
- Capacity Stress Analysis

---

# 🤖 AI/ML Basics

A simple forecasting model was developed using NumPy-based Linear Regression.

The forecasting process includes:

- Data preparation
- Train-Test Split
- Linear Regression using NumPy
- Future prediction
- Forecast visualization
- Model evaluation

Performance Metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

# 📊 Key Visualizations

The notebook contains 15+ professional visualizations including:

- Histogram
- Line Chart
- Multiple Line Plot
- Bar Chart
- Horizontal Bar Chart
- Pie Chart
- Scatter Plot
- Box Plot
- Area Chart
- Rolling Average Trend
- Growth Rate Analysis
- Capacity Stress Trend
- Monthly Trend
- Forecast Plot

---

# 💡 Key Business Insights

Some major insights include:

- Healthcare demand fluctuates significantly over time.
- HHS manages the majority of children under care.
- Positive Net Intake contributes to backlog accumulation.
- Rolling averages effectively identify prolonged high-load periods.
- Transfer efficiency directly impacts operational performance.
- Higher discharge ratios reduce system pressure.
- Seasonal trends influence healthcare demand.
- Forecasting provides valuable support for proactive planning.

---

# 📋 Business Recommendations

Based on the analysis:

- Improve healthcare capacity planning.
- Increase staffing during high-demand periods.
- Enhance transfer coordination between CBP and HHS.
- Monitor Net Intake as an early warning KPI.
- Improve discharge planning.
- Implement real-time operational dashboards.
- Automate KPI reporting.
- Improve data quality validation.

---

# 🚀 Future Scope

Future enhancements include:

- Time-series forecasting models
- Machine learning algorithms
- Streamlit dashboard
- Power BI dashboard
- API integration
- Real-time analytics
- Automated anomaly detection
- Cloud deployment

---

# 📷 Sample Output

Include screenshots of:

- Data Cleaning
- Feature Engineering
- Line Chart
- Rolling Average
- Forecast
- KPIs

---

# 📌 Learning Outcomes

This project demonstrates practical skills in:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Data Visualization
- Statistical Analysis
- KPI Development
- Forecasting
- Business Intelligence
- Healthcare Analytics

---

# 👨‍💻 Author

**Shivang Sharma**

Aspiring Data Analyst

### Skills

- Python
- SQL
- Power BI
- Excel
- Pandas
- NumPy
- Matplotlib
- Data Analysis
- Jupyter Notebook

---

# ⭐ If you found this project useful

Please consider giving this repository a ⭐ on GitHub.
