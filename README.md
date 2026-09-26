# OlistPulse 📊

> **Predicting E-Commerce Order Returns & Customer Behavior Analytics**

**OlistPulse** is an end-to-end Machine Learning project developed as the final graduation capstone project for the 140-hour **TechTrek Advanced Data Science** program. Using real-world e-commerce transaction data from Olist, this repository provides a complete data processing, model evaluation, and deployment workflow designed to predict order return likelihood and identify critical post-purchase behavior patterns.

---

## 📌 Project Overview

In online retail, order returns directly impact operating margins and logistics planning. **OlistPulse** formulates return likelihood as a supervised classification challenge, building a modular pipeline that ingests raw transaction records, engineers predictive behavioral features, trains and benchmarks multiple algorithms, and exposes predictions through an interactive web interface.

---

## ✨ Key Features

* **Data Engineering Pipeline:** Cleaned, merged, and transformed multi-table relational data, addressing missing values, outlier detection, and imbalance.
* **Feature Engineering:** Extracted temporal trends, seller/customer location metrics, payment structures, and delivery latency metrics.
* **Model Exploration & Benchmarking:** Evaluated classical baseline models alongside gradient boosting and deep learning architectures:
  * Logistic Regression
  * Decision Trees
  * Random Forests
  * Gradient Boosting (XGBoost / LightGBM)
  * PyTorch Neural Networks
* **Production-Ready Architecture:** Modular Python code layout with structured logging, clean configuration management, and robust error handling.
* **Interactive UI & Containerization:** Built a user-friendly frontend with **Streamlit** and fully containerized the environment using **Docker**.

---

## 🛠️ Tech Stack

* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Machine Learning & Deep Learning:** Scikit-Learn, PyTorch, XGBoost / LightGBM
* **Visualization:** Matplotlib, Seaborn
* **Deployment & Containerization:** Streamlit, Docker
* **Environment & Version Control:** Git, Virtual Environments / Conda

---

## 📂 Repository Structure

```text
OlistPulse/
├── data/                  # Raw and processed datasets (Olist)
├── notebooks/             # Exploratory Data Analysis & experiments
├── src/                   # Production-ready source code
│   ├── preprocessing.py   # Data cleaning & feature engineering scripts
│   ├── train.py           # Model training and hyperparameter tuning
│   ├── evaluate.py        # Evaluation metrics and reporting
│   └── utils.py           # Utility functions and logging setup
├── app.py                 # Streamlit web application
├── Dockerfile             # Container configuration
├── requirements.txt       # Python package dependencies
└── README.md              # Project documentation
