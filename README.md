# 📈 Crude Oil Price Forecasting App  
### _Tkinter Desktop App • XGBoost Regression • Time-Series Forecasting_

A fully interactive **desktop application** for crude oil price forecasting built using:

- **Python 3**
- **Tkinter** (GUI)
- **XGBoost**
- **Pandas / NumPy**
- **Matplotlib**
- **Joblib**

This tool transforms raw crude oil CSV data into a **clean, feature-engineered** dataset, trains an **XGBoost model**, and generates **recursive multi-day forecasts** with visualizations.

---

# ⭐ Features

### ✅ **1. Upload CSV Data**
Supports files with:
- `Date`
- `Close` / `Close_Last` / `Close/Last`
- `Volume`

### ✅ **2. Preprocessing (Automated)**
Automatically builds:
- `lag_1, lag_2, lag_3, lag_7, lag_14, lag_30`
- `MA_7`, `MA_30`
- `STD_7`
- `return_1`
- `vol_lag1`

### ✅ **3. Train XGBoost Model**
Time-based split (80/20).  
Metrics shown:
- **MAE**
- **RMSE**
- **MAPE**
- **R² Score**

### ✅ **4. Forecast Future Prices**
- Recursive prediction (default = 30 days)
- Adjustable in UI

### ✅ **5. Show Plots**
- Actual vs Predicted  
- 30-Day Forecast Curve  

### ✅ **6. Save & Load Model**
- Saves via `joblib`
- Reload & predict without retraining

### ✅ **7. Simple Tkinter UI**
- Upload → Preprocess → Train → Forecast → Plot
- Real-time log window

---

# 📁 Project Files

| File | Description |
|------|-------------|
| `crude_oil_forecast_app.py` | Main Tkinter desktop application |
| `crude_oil_forecast.ipynb` | Notebook version |
| `Crude oil file - Google Docs.pdf` | Report with screenshots & graphs |

📄 **PDF Path:**  
`/mnt/data/Crude oil file - Google Docs.pdf`  
(Contains all example screens & graphs.)  
📸 Screenshots referenced below come from this PDF. :contentReference[oaicite:0]{index=0}

---






