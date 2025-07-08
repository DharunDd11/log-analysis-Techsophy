# 🧠 Intelligent Log Analysis & Incident Prediction

This is a Python-based project that analyzes application and infrastructure logs to detect anomalies and predict potential incidents **before they impact users**.

---

## 📌 Features

✅ Upload logs in `.csv`, `.json`, or `.log` format   
✅ Fatigue-aware alerting system (prevents redundant alerts)  
✅ Real-time alert simulation using batch learning  
✅ Incident timeline visualization using Matplotlib  
✅ Export alerts to `.csv` and `.xlsx`  

---

## 📁 Supported Log Format

Each log file should contain the following fields:

- `timestamp` (e.g., `2025-07-08 10:00:00`)
- `log_level` (e.g., `INFO`, `WARN`, `ERROR`)
- `message` (text description of the event)

Supported file types:
- `.csv`
- `.json`
- `.log` (with standard log pattern: `timestamp level message`)

---

## 🚀 How to Run (Google Colab or Local Jupyter Notebook)

1. Open the notebook: `Log_Analysis_Full_Colab_Extended.ipynb`
2. Upload your log file when prompted
3. Run each cell in order
4. View predicted incidents, alerts, and visual graphs
5. Download `alerts.csv` and `alerts.xlsx` from the notebook

---

## 🧪 Sample Dataset

Included in this repo: `sample_log_data_large.csv`  
Use it to test log anomaly detection and alert simulation.

---

## 🧰 Dependencies

To run locally:

```bash
pip install pandas scikit-learn matplotlib openpyxl colorama
