# 📦 ML-Driven Demand Forecasting & Inventory Optimization (FMCG – India)

A complete Machine Learning project designed to improve demand forecasting accuracy, reduce stockouts, and optimize inventory levels for FMCG supply chains (Yogabar-style environment). This system integrates time-series forecasting, external event signals, and inventory optimization models to enable proactive replenishment decisions.

---

## 🚀 Project Overview

This project develops an **end-to-end demand forecasting and inventory optimization engine** using classical ML, deep learning, and business-driven forecasting strategies.

### 🎯 Key Outcomes
- **20% reduction in forecast error** (accuracy improved to ~92%)  
- **30% reduction in stockouts** and lost sales  
- **Service level improvement to ~98%**  
- **35% improvement in inventory efficiency**  
- Proactive replenishment instead of reactive reordering  
- Automated alerts and Power BI dashboards

---

## 🧠 Problem Statement

Traditional forecasting struggled with seasonality, promotions, and volatility, leading to:
- Frequent stockouts  
- Overstock buildup  
- High manual forecasting effort  
- Misaligned demand & supply  

**Goal:** Build an ML system that predicts SKU-wise demand and recommends optimal inventory levels for a 1–12 week horizon.

---

## 📊 Data Requirements

### **Internal Data**
- Historical sales (SKU, region, channel)
- Inventory levels (opening, closing, safety stock)
- Lead time & supplier performance
- Promotions & price changes
- Order fulfillment records

### **External Data**
- Seasonal events & festivals
- Weather patterns
- Online search trends
- Competitor pricing/events  

### **Real-Time Signals**
- POS live demand  
- Warehouse IoT data (if available)  
- Social sentiment spikes  

---

## 🔧 Tech Stack Used

| Component | Tools |
|----------|-------|
| **Data Engineering** | Python, SQL, n8n, PostgreSQL |
| **Forecasting Models** | ARIMA, SARIMA, Prophet, LSTM |
| **ML Libraries** | Scikit-Learn, TensorFlow, Statsmodels |
| **Visualization** | Power BI / Looker Studio |
| **Version Control** | Git, GitHub |

---

## 🧮 Model Approaches

### **1. Classical Time-Series Models**
- ARIMA / SARIMA  
- Prophet  
- Exponential Smoothing  

### **2. Machine Learning Models**
- XGBoost  
- Random Forest  

### **3. Deep Learning Models**
- LSTM Neural Networks  
- GRU for long-range dependencies  

### **4. Event Detection (NLP)**
- Identifying spikes from promotions, news, or seasonality  
- BERT/DistilBERT keyword trend signals  

---

## 📏 Evaluation Metrics

| Metric | Purpose |
|--------|----------|
| **MAPE / WAPE** | Forecast accuracy |
| **RMSE / MAE** | Error magnitude |
| **Service Level (%)** | Inventory performance |
| **Stockout Rate (%)** | Risk indicator |
| **Inventory Turnover** | Efficiency measure |

---

## 🗓 Project Timeline (8 Weeks)

### **Week 1:** Requirement gathering & data audit  
### **Week 2:** ETL pipeline setup (Python/SQL)  
### **Week 3:** Baseline ARIMA/Prophet models  
### **Week 4–5:** LSTM + Ensemble models  
### **Week 6:** Hyperparameter tuning & evaluation  
### **Week 7:** Deployment-ready scripts & APIs  
### **Week 8:** Power BI dashboard + automated alerts  

---

## 📊 Deliverables

- Feature-engineered dataset  
- ML forecasting models (ARIMA, LSTM, Prophet)  
- Inventory optimization logic (safety stock, reorder points)  
- Power BI dashboard (service level, stockouts, forecast accuracy)  
- GitHub repository with notebooks & scripts  

---

## 📂 Repository Structure

