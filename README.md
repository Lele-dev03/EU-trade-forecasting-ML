# Forecasting EU Import-Export Volumes Using Time Series Machine Learning Models

---

## 🎯 Overview
This repository contains the Python code and documentation for my MSc thesis *“Forecasting EU Import-Export Volumes Using Time Series Machine Learning Models.”*  
The project compares **traditional econometric models** (ARIMAX, Linear Regression) and **machine learning models** (Random Forest, XGBoost) to forecast EU–U.S. trade volumes under external shocks such as tariffs and the COVID-19 pandemic.

---

## 🧰 Contents
- `data_preprocessing.ipynb` – Cleaning and harmonizing datasets  
- `feature_engineering.ipynb` – Creation of lag, macroeconomic, and interaction features  
- `model_training.ipynb` – Model implementation and evaluation  
- `requirements.txt` – Python dependencies  

---

## 📊 Data Sources
All data used are publicly available:
- Eurostat  
- European Central Bank (ECB)  
- World Bank (Pink Sheet)  
- Oxford COVID-19 Government Response Tracker (OxCGRT)  

---

## ⚙️ Reproducibility
All scripts and models are reproducible using Python and Jupyter Notebooks.  
To reproduce the analysis:

```bash
git clone https://github.com/leina-madaschi/EU-trade-forecasting-ML.git
pip install -r requirements.txt
jupyter notebook
---

