# Semiconductor Manufacturing Yield & Defect Trend Analysis using Python

## 📌 Project Overview
This project focuses on analyzing **semiconductor manufacturing process data** to understand **yield behavior, defect trends, and process stability** using **Python-based exploratory data analysis (EDA)**.

The objective is to demonstrate how data analytics techniques can be applied to **high-dimensional, real-world manufacturing sensor data** to extract meaningful insights related to **quality and yield performance**.

This is a **Python-only data analytics project** (no machine learning), emphasizing **data cleaning, visualization, and interpretability**.

---

## 🎯 Objectives
- Analyze overall **manufacturing yield distribution**
- Identify **missing-value patterns** in sensor data
- Remove **non-informative and unreliable sensors**
- Study **sensor behavior differences** between passing and failing units
- Analyze **yield trends over time**
- Detect **sensor redundancy** through correlation analysis

---

## 📂 Dataset Description
- **Dataset**: SECOM Semiconductor Manufacturing Dataset  
- **Records**: 1,567 production instances  
- **Features**: 590 sensor/process parameters  
- **Target**: Yield outcome (Pass / Fail)  

### Data Challenges
- High dimensionality  
- Significant missing values  
- Strong class imbalance  
- Real-world sensor noise  

Each row represents a single production entity with associated sensor measurements and final yield outcome.

📎 **Dataset Link**  
👉 [SECOM Dataset (CSV)](https://github.com/magantidatta/data-analytics/blob/main/python-analytics/Semiconductor%20Manufacturing%20Yield%20%26%20Defect%20Trend%20Analysis/Dataset/secom.csv)

---

## 🛠 Tools & Technologies
- **Python**
- **Pandas** – data manipulation and preprocessing
- **NumPy** – numerical computations
- **Matplotlib & Seaborn** – data visualization

---

## 🔄 Project Workflow
1. Data loading and structural understanding  
2. Missing value analysis and visualization  
3. Removal of sensors with excessive missing values  
4. Median-based imputation for remaining missing data  
5. Elimination of constant / non-informative sensors  
6. Yield distribution analysis (Pass vs Fail)  
7. Sensor behavior comparison across yield classes  
8. Time-based yield trend analysis  
9. Correlation analysis for sensor redundancy detection  

---

## 📊 Key Insights
- Manufacturing yield is **highly imbalanced**, with failures accounting for a small percentage of total production.
- Several process parameters show **abnormal variance** for failed units, indicating potential defect contributors.
- Certain sensors are **highly correlated**, suggesting redundancy in the measurement system.
- Yield performance remains largely **stable over time**, with occasional spikes in defect rates.

---

## 📁 Project Files
📓 **Jupyter Notebook (Code)**  
👉 [Semiconductor Manufacturing Yield & Defect Trend Analysis.ipynb](https://github.com/magantidatta/data-analytics/blob/main/python-analytics/Semiconductor%20Manufacturing%20Yield%20%26%20Defect%20Trend%20Analysis/Code/Semiconductor%20Manufacturing%20Yield%20%26%20Defect%20Trend%20Analysis.ipynb)

📊 **Dataset**  
👉 [secom.csv](https://github.com/magantidatta/data-analytics/blob/main/python-analytics/Semiconductor%20Manufacturing%20Yield%20%26%20Defect%20Trend%20Analysis/Dataset/secom.csv)

---

## 📌 Resume Description
**Semiconductor Manufacturing Yield & Defect Trend Analysis (Python)**  
Performed exploratory data analysis on semiconductor manufacturing sensor data to study yield distribution, defect trends, missing-value patterns, and process stability using Python.

---

## 📝 Notes
- This project focuses on **exploratory data analysis and insight generation**.
- No machine learning models are used.
- The emphasis is on **data quality, interpretability, and real-world analytics workflows**.

---

## 👤 Author
**Maganti Shanmukha Sri Datta**

