# 📈 Cardamom Price Forecasting Using AI/ML

### Developed for DS Group – Procurement & Strategy Team

This project presents a complete **AI/ML-driven forecasting system** to predict **Cardamom Prices and Quantity Trends** using historical auction data and auxiliary weather indicators.
The predictions are visualized through **four Tableau dashboards**, helping business teams take informed procurement decisions.

---

## 🚀 Project Overview

Cardamom prices exhibit high volatility due to seasonal production, climatic changes, and market demand.
To support strategic procurement planning at DS Group, this project:

* Combines auction data, rainfall data, and engineered features
* Applies **four ML/DL forecasting models**
* Compares model performance
* Generates future forecasts
* Visualizes insights in Tableau

This system supports:

* Price-risk mitigation
* Inventory planning
* Budget forecasting
* Long-term sourcing strategies

---

# 🛠️ Tech Stack

### **Programming & Libraries**

* Python, Pandas, NumPy
* Scikit-learn
* XGBoost
* TensorFlow/Keras
* Prophet
* Matplotlib / Seaborn

### **Visualization**

* Tableau Dashboards (4 interactive screens)

# 📊 Dataset Description

The dataset includes:

* **Auction Date**
* **Average Price (₹/Kg)**
* **Quantity**
* **Rainfall**
* **Moving Averages (MA3, MA12)**
* **Lag Features**
* **Time-based Features (Year, Month, Week)**

All data was cleaned, formatted, and combined into a single **master dataset**.

---

# 🔍 Exploratory Data Analysis (Summary)

Key insights from EDA:

* Prices exhibit **clear seasonal patterns** (festival & harvesting cycles)
* Quantity fluctuates with **rainfall and climate variability**
* Several significant spikes are visible in monsoon & winter months
* Trends & cycles strongly influence forecasting accuracy

Charts include:

* Price & quantity trend
* Seasonality plots
* Correlation heatmaps
* Month & year-wise comparisons

---

# 🤖 Machine Learning & Deep Learning Models

The project evaluates **four models**:

### **1️⃣ Random Forest Regressor**

* Good baseline
* Handles non-linearity
* Moderate accuracy

### **2️⃣ XGBoost Regressor**

* Better gradient-boosting performance
* Captures complex relationships
* More accurate than Random Forest

### **3️⃣ Prophet Forecasting Model**

* Strong at seasonality
* Business-friendly
* Suitable for long-term signals

### **4️⃣ LSTM Neural Network**

* Deep learning model
* Learns long-term patterns
* Best performance overall

---

# 📌 Model Performance

### **------ TEST ACCURACY (LOWER = BETTER) ------**

| Model         | MAE           | RMSE          | MAPE (%)     |
| ------------- | ------------- | ------------- | ------------ |
| Random Forest | 1218.854789   | 1305.319729   | 46.695834    |
| XGBoost       | 1033.838831   | 1144.976216   | 39.521504    |
| Prophet       | 463.162790    | 556.107537    | 17.036270    |
| **LSTM**      | **50.527157** | **59.078781** | **1.925114** |

### ✔ **LSTM is the top-performing model** with the lowest error across all metrics.

Contains:

* Future predicted prices
* Predicted quantity
* Date-wise breakdown
* Combined ML + DL outputs

This file is directly consumed by Tableau dashboards.

---

# 📊 Tableau Dashboards

The project includes **four dashboards**, each focusing on a different analytical view:

### **1. Overview Dashboard**

* Price & quantity trends
* Annual comparisons
* Monthly summary

### **2. Forecast Dashboard**

* ML vs DL predictions
* Next 12 months forecast

### **3. Seasonality Dashboard**

* Month & week patterns
* Seasonal peaks

### **4. KPI Dashboard**

* Min/Max price
* Trend KPIs
* Forecast vs actual comparison

# 👨‍💻 Author

**Abhay**
AI/ML Developer & Data Analyst
Project executed for forecasting optimization at DS Group.
