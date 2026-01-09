# 🧠 Bottleneck — Data Analysis Project

Welcome to the **Bottleneck Analysis Notebook**, an end-to-end exploration of sales, stock, and margin data.  
This project was designed for **clarity, structure, and interactivity**, featuring a dark-themed layout and a dynamic HTML export for easy reading.  

---

## 🚀 Live Access

📘 **Interactive Notebook (GitHub Pages)**  
➡️ [Open the live HTML version](https://stephane-oc.github.io/bottleneck/)  

💻 **Original Jupyter Notebook**  
➡️ [View the notebook file](https://github.com/Stephane-OC/bottleneck/blob/main/analyse_bottleneck.ipynb)  

---

## 📊 Project Overview

This project provides an **in-depth analysis of sales performance and stock management**, focusing on:

- **Data import and cleaning**
- **Exploratory data analysis (EDA)** for the ERP, web, and liaison datasets
- **Data merging and consistency checks**
- **Univariate analyses** of:
  - 💰 Revenue (CA)
  - 📦 Quantities sold
  - 🧱 Stock levels
  - 📈 Margin rates
- **Correlation study** between price, stock, and sales
- **Final export of the cleaned dataset**

---

## 🧩 Key Features

- ✨ Clean, structured notebook with collapsible sections  
- 🧭 Table of contents with “Back to Top” navigation anchors  
- 🌑 Optimized **dark theme** for visual comfort  
- 📊 Interactive plots using **Plotly Express** and **Seaborn**  
- ✅ Automated detection and correction of stock inconsistencies  
- 📦 Ready for export to **GitHub Pages** and presentation reviews  

---

## 🧠 Technical Stack

| Category | Tools & Libraries |
|-----------|------------------|
| **Language** | Python 3.11 |
| **Data Analysis** | pandas, numpy |
| **Visualization** | plotly.express, seaborn, matplotlib |
| **Environment** | Jupyter Notebook |

---

## 🗂️ Table of Contents

### **Step 1 — Importing Libraries and Loading Files**
- 1.1 Importing Libraries
- 1.2 1.2 Loading Files

### **Step 2 — Exploratory Data Analysis**
- 2.1 Analysis of the `erp.xlsx` File
  - 2.1.1 Variable Exploration
    - PRICE  
    - STOCK  
    - ONSALE_WEB  
    - PURCHASE PRICE
- 2.2 2.2 Analysis of the `web.xlsx` File
- 2.3 Analysis of the `liaison.xlsx` File

### **Étape 3 — Jonction des fichiers**
- 3.1 Merge `df_erp` + `df_liaison`  
- 3.2 Merge `df_merge` + `df_web`  

### **Étape 4 — Analyse univariée des prix**
- 4.1 Data visualization  
- 4.2 Statistical methods (Z-index, IQR)

### **Étape 5 — Advanced analysis**
- 5.1 Sales by revenue (CA)  
- 5.2 Sales by quantity  
- 5.3 Stock analysis  
- 5.4 Margin analysis  
- 5.5 Correlation between stock, sales, and price  
- 5.6 Export of the final Excel dataset  

---

## 💡 Author

**👨‍💻 Stephane-OC**  
Data Analyst & Web Developer — Passionate about clean data, automation, and storytelling through analytics.  

---

## 🧾 License

This project is shared under the **MIT License**.  
Feel free to use, modify, and credit appropriately.  

---

> _“Great data doesn’t just tell stories — it builds understanding.”_  
> **Stephane-OC**