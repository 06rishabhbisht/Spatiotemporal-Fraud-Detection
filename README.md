# Spatiotemporal Financial Fraud Detection

## 📌 Overview

This project explores financial fraud detection using **spatiotemporal analysis** of transaction data. It integrates geographic, temporal, and transactional features to improve fraud detection accuracy.

## 🎯 Objectives

* Identify fraud hotspots using spatial clustering
* Analyze temporal fraud patterns
* Build machine learning models for fraud detection

## 📊 Dataset

* Synthetic financial transactions dataset (10,000 records)
* Enriched with U.S. city population data
* Includes:

  * Transaction amount
  * Timestamp
  * Location (lat/long)
  * Card type & category
  * Fraud label

## 🔍 Key Techniques

* Exploratory Data Analysis (EDA)
* DBSCAN clustering (geospatial)
* Feature engineering (time gaps, population scaling)
* Machine Learning:

  * Logistic Regression
  * Random Forest
  * XGBoost

## 📈 Results

* XGBoost achieved best performance:

  * F1 Score ≈ 0.71
  * ROC-AUC improved with spatial features
* Fraud peaks:

  * Time: 12 AM – 2 AM
  * Location: clustered in specific cities

## 🧠 Key Insights

* Spatial + temporal features improved detection significantly
* Mid-sized cities showed disproportionate fraud rates
* Fraud often occurs in bursts (coordinated activity)

## 🚀 How to Run

```bash
pip install -r requirements.txt
```

Run notebooks in order:

1. EDA
2. Feature Engineering
3. Modeling

## 📂 Repository Structure

(Explain folders briefly)

## 📄 Report

Full research paper available in `/report`

## 👤 Author

Rishabh Bisht
