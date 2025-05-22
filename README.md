# 📊 Predicting COVID-19 Cases in India Using ARIMA, Prophet, LSTM, and Power BI

### Author: Abhrajit Das

**Institution:** Seidenberg School of Computer Science and Information Systems, Pace University, USA
**Email:** [abhrajit.breathin@gmail.com](mailto:abhrajit.breathin@gmail.com)

---

## 📝 Overview

This research project explores time series forecasting models—**ARIMA**, **Facebook Prophet**, and **LSTM**—to predict the spread of COVID-19 in India using publicly available data. The models were evaluated using **Mean Absolute Percentage Error (MAPE)** to determine their forecasting accuracy, with **Power BI** used for interactive visualization and exploration of the pandemic trends.

---

## 🎯 Objectives

* Compare the performance of ARIMA, Prophet, and LSTM models on COVID-19 time series data.
* Use **Power BI** dashboards to uncover trends, hotspots, and conduct exploratory data analysis (EDA).
* Evaluate model performance using MAPE and highlight practical implications for public health planning.
* Inform policymakers with data-driven insights for resource allocation and intervention planning.

---

## 📂 Project Structure

```
COVID19_Forecasting_India/
│
├── data/
│   └── covid19_india_statewise.csv
│
├── notebooks/
│   ├── arima_model.ipynb
│   ├── prophet_model.ipynb
│   └── lstm_model.ipynb
│
├── powerbi/
│   └── covid_dashboard.pbix
│
├── results/
│   ├── performance_comparison.csv
│   └── figures/
│       ├── arima_plot.png
│       ├── prophet_plot.png
│       └── lstm_plot.png
│
├── README.md
└── research_paper.pdf
```

---

## 🧠 Methodology

1. **Dataset:**

   * Source: Kaggle
   * Range: March–August 2020
   * Data Points: 5,694 records from 28 Indian states and 8 union territories

2. **Preprocessing:**

   * Cleaning, formatting, and structuring for time series analysis
   * Feature engineering for model input

3. **Models Implemented:**

   * **ARIMA**: Linear trend capture
   * **Prophet**: Seasonality-aware forecasting
   * **LSTM**: Deep learning model for complex non-linear trends

4. **Evaluation Metric:**

   * **MAPE (Mean Absolute Percentage Error)**

---

## 📈 Key Findings

* **LSTM** model outperformed other models with a **MAPE of 0.0617**
* **Prophet** demonstrated intermediate accuracy with **MAPE of 0.228**
* **ARIMA** lagged with **MAPE of 0.375**, struggling with non-linear patterns
* Power BI dashboard enabled geographic, temporal, and predictive analysis to assist public health officials

---

## 🛠 Tools & Technologies

* **Programming:** Python 3.8, Jupyter Notebook
* **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, fbprophet, tensorflow
* **Visualization:** Power BI
* **Platform:** Windows 11 (16GB RAM, Intel i5)

---

## 📊 Power BI Dashboard Features

* Interactive Time Series Analysis
* State-wise & Monthly Breakdown
* Forecasting Confirmed, Recovered, and Deceased Cases
* Decomposition Tree for Root Cause Analysis

---

### 🖼️ COVID-19 Interactive Dashboard using Power BI

![COVID-19 Dashboard – Time Series, Heat Maps, Trends](https://github.com/Abhrajit23/Predicting-COVID-19-Cases-in-India-Using-ARIMA-Prophet-LSTM-and-Data-Analysis-Using-Power-BI/raw/main/Figure%202.%20COVID-19%20Interactive%20Dashboard%20on%20Power%20BI%20showcasing%20Time%20Series%20Analysis%2C%20Geographical%20Heat%20Maps%2C%20Comparative%20Analysis%2C%20and%20Trend%20Analysis..png)

### 🔮 Forecasting Future COVID-19 Cases

![COVID-19 Forecasting Dashboard – Confirmed, Deceased, Recovered](https://github.com/Abhrajit23/Predicting-COVID-19-Cases-in-India-Using-ARIMA-Prophet-LSTM-and-Data-Analysis-Using-Power-BI/raw/main/Figure%203.%20Dashboard%20for%20Future%20Predictions%20of%20COVID-19%20Cases%20in%20India%20Confirmed%2C%20Deceased%2C%20and%20Recovered.png)


## 📚 Citation

If you use this work, please cite the following paper:

> Das, A. (2025). *Predicting COVID-19 Cases in India Using ARIMA, Prophet, LSTM & Data Analysis Using Power BI*. Lecture Notes in Networks and Systems, Vol. 1, Springer Singapore. DOI: [10.1007/978-981-97-8336-6](https://doi.org/10.1007/978-981-97-8336-6)

---

## 🔮 Future Work

* Incorporate demographic, mobility, and socio-economic features into models
* Experiment with ensemble models (e.g., ARIMA+LSTM hybrid)
* Enable real-time forecasting with auto-updating Power BI dashboards
* Apply the framework to other countries or regional epidemics

---

## 💬 Contact

For questions, collaboration, or academic inquiries:

📧 **[abhrajit.breathin@gmail.com](mailto:abhrajit.breathin@gmail.com)**
🔗 [LinkedIn](https://www.linkedin.com) | 🌐 [Open-talk.co](http://open-talk.co)
