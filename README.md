# 💊 Tracked to Tragedy: A Data Dive into U.S. Drug Overdose Deaths

**"Numbers don’t lie—but behind every data point is a life, a loss, and a lesson."**

This project explores the rising tide of drug overdose deaths in the U.S. through the lens of data science. By combining demographic analysis with time series forecasting, we aim to both understand the past and anticipate the future.

---

## 🔍 Project Highlights

- 📊 **Trend Analysis**: Visualize overdose rates by year
- 👥 **Demographic Breakdown**: Race, age, sex, Hispanic origin
- 💡 **Predictive Modeling with ARIMA**: Forecast future overdose death trends
- 📈 **Visual Insights**: Create impactful graphs that tell a story

---

## 🔮 Time Series Forecasting with ARIMA

We applied the **ARIMA (AutoRegressive Integrated Moving Average)** model to forecast future overdose death rates based on historical data. Here's what was done:

- Cleaned and preprocessed the data by aggregating annual death rates.
- Conducted stationarity checks and differencing where needed.
- Used **ARIMA(p,d,q)** modeling to fit the trend.
- Generated predictions for upcoming years to show the potential direction of the crisis.
- Visualized both actual and predicted trends to emphasize the urgency of the issue.

📌 *The ARIMA model was key in quantifying future public health risks and showcasing how statistical forecasting can aid in data-driven policymaking.*

---

## 📁 Dataset Info

- **Source**: CDC/NCHS (Centers for Disease Control and Prevention)
- **Title**: Drug Overdose Death Rates by Drug Type, Sex, Age, Race, and Hispanic Origin
- **Format**: CSV

---

## 🛠️ Tools & Technologies

- Python
- Pandas, Matplotlib
- **ARIMA (from `statsmodels` library)**
- Google Colab

---

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Mount your Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
