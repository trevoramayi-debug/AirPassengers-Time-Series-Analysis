# ✈️ AirPassengers Time Series Analysis

A comprehensive time series analysis project using the classic **AirPassengers** dataset. This project explores historical airline passenger traffic, evaluates stationarity, and prepares the data for future forecasting models using statistical techniques commonly employed in demand forecasting.

---

## 📌 Project Overview

Accurate passenger demand forecasting is critical in the airline industry for:

- Flight scheduling
- Revenue management
- Dynamic ticket pricing
- Fleet and crew planning
- Resource allocation

This project demonstrates the complete exploratory phase of a time series forecasting workflow by identifying trends, seasonality, and stationarity before building predictive models.

---

## 📂 Dataset

**Dataset:** AirPassengers

The dataset contains monthly totals of international airline passengers from **1949 to 1960**.

| Column | Description |
|----------|-------------|
| Month | Observation date |
| Passengers | Monthly passenger count |

---

## 🎯 Objectives

- Convert raw data into a proper time series format
- Explore long-term trends
- Visualize passenger growth over time
- Calculate rolling statistics
- Perform stationarity testing using the Augmented Dickey-Fuller (ADF) Test
- Apply logarithmic transformation
- Apply first-order differencing
- Re-evaluate stationarity after transformation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading

- Import dataset
- Inspect structure
- Verify data quality

---

### 2. Time Series Preparation

- Convert dates into datetime format
- Set Month as index
- Rename passenger column

---

### 3. Exploratory Data Analysis

Visualize passenger traffic over time to identify:

- Trend
- Growth
- Seasonal behavior

---

### 4. Rolling Statistics

Compute:

- 12-Month Rolling Mean
- 12-Month Rolling Standard Deviation

These statistics help determine whether the series has a constant mean and variance over time.

---

### 5. Stationarity Test

The Augmented Dickey-Fuller (ADF) Test is used to determine whether the series is stationary.

The analysis includes:

- ADF Statistic
- p-value
- Critical Values

---

### 6. Log Transformation

A logarithmic transformation is applied to stabilize variance across the time series.

---

### 7. First-Order Differencing

Differencing removes trend components and helps create a stationary series suitable for forecasting.

---

### 8. Stationarity Verification

The ADF Test is repeated after differencing to confirm that the transformed series satisfies stationarity assumptions.

---

## 📈 Visualizations

The notebook includes:

- Original Time Series Plot
- Rolling Mean Plot
- Rolling Standard Deviation Plot
- Differenced Time Series Plot

---

## 📊 Statistical Methods

- Rolling Mean
- Rolling Standard Deviation
- Log Transformation
- First-Order Differencing
- Augmented Dickey-Fuller Test

---

## 📁 Repository Structure

```
AirPassengers-Time-Series-Analysis/
│
├── AirPassengers.csv
├── Time_Series_Analysis.ipynb
├── README.md


## 📌 Key Learning Outcomes

This project demonstrates practical knowledge of:

- Time Series Data Preparation
- Exploratory Time Series Analysis
- Stationarity Testing
- Data Transformation Techniques
- Statistical Validation
- Forecasting Data Preparation

---

## 📚 Future Improvements

Possible extensions include:

- ARIMA Modeling
- SARIMA Modeling
- Exponential Smoothing
- Prophet Forecasting
- LSTM Neural Networks
- Forecast Accuracy Evaluation

---

## 👨‍💻 Author

**Trevor**

## ⭐ If you found this project useful

Consider giving the repository a ⭐ to support the project.# AirPassengers-Time-Series-Analysis
