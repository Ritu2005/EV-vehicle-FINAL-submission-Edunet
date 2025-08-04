# EV Adoption Forecaster

An interactive web application that uses machine learning to forecast the future uptake of electric vehicles (EVs). With the help of **Streamlit**, this tool enables users to visualize future trends, train a forecasting model, and upload EV data without writing any code.
---

## Features

- Historical or forecast EV datasets in CSV format, need to be uploaded.
- Automatic data cleaning and preprocessing.
- It also performs time-series feature engineering in the background, like calculating lag values, rolling averages, and growth rates to make predictions more accurate.
- It uses an XGBoost regression model and handles time-aware cross-validation to avoid data leakage.
- Predicton of future EV adoption for up to 60 months.
- Has interactive visualizations using Plotly.
- Forecast results as CSV can be downloaded.

---

## Requirements

To run the app the dependencies need to be installed using:

```bash
pip install -r requirements.txt
