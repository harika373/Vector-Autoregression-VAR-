# PM2.5 Air Pollution Prediction Using VAR

## 📌 About
A time-series forecasting project that predicts PM2.5 air pollution levels using **Vector Autoregression (VAR)** and environmental variables such as humidity, wind direction, solar radiation, pressure, and temperature.

## 🛠️ Technologies
- Python
- Pandas, NumPy
- Statsmodels
- Matplotlib
- Scikit-learn

## ⚙️ Workflow
1. Load and preprocess the Excel dataset.
2. Handle missing values.
3. Split data into training and testing sets.
4. Select the VAR lag order using BIC.
5. Train the model and predict PM2.5.
6. Evaluate performance and visualize results.

## 📊 Results
- **Lag Order:** 2
- **RMSE:** 19.90
- **MAPE:** 12.11%
- **R² Score:** 0.8845

*Results are based on rolling one-step-ahead predictions on the test dataset.*

## ▶️ Run the Project
```bash
pip install -r requirements.txt
python pm25_var.py
```

## 📁 Files
- `Data.xlsx` — Input dataset
- `pm25_var.py` — Python implementation
- `requirements.txt` — Dependencies
- `VAR_PM25_Prediction.png` — Prediction graph
- `VAR_PM25_Errors.png` — Error graph

## 🎯 Objective
To explore how environmental variables can help predict PM2.5 levels and support air quality analysis.
