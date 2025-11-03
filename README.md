# ⚡ Energy Analytics Project — Africa

### 📊 Exploring the Relationship Between Energy Use and Economic Growth

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fjnelima-pixel/energy_analytics_project/blob/main/Energy_Analytics.ipynb)

---

## 📘 Overview

This project explores the relationship between **energy consumption** and **economic growth** across six African countries from different regions, using real-world data from the **World Bank**.  

The study applies **bivariate analysis** and **Ordinary Least Squares (OLS) regression** to assess how energy use per capita influences GDP per capita — highlighting the role of energy access in driving economic performance.

This is part of a data analytics portfolio demonstrating practical applications of **Python, econometrics, and data visualization** for development insights.

---

## 🌍 Countries Covered
- **Kenya** (East Africa)  
- **Nigeria** (West Africa)  
- **Egypt** (North Africa)  
- **South Africa** (Southern Africa)  
- **Ethiopia** (Horn of Africa)  
- **Ghana** (West Africa)

---

## 🧰 Tools and Libraries
- **Python** (Google Colab)  
- **Pandas** – Data manipulation  
- **Seaborn & Matplotlib** – Visualization  
- **Statsmodels** – Econometric modeling  
- **World Bank API (wbdata)** – Data retrieval  

---

## 📈 Methodology

1. **Data Collection**  
   - Energy use (kg of oil equivalent per capita) and GDP per capita (USD) were retrieved from the **World Bank API** for 2000–2023.  
2. **Data Cleaning**  
   - Standardized variable names and dropped missing values.  
3. **Visualization**  
   - Seaborn scatter plots to visualize relationships across countries.  
4. **Statistical Analysis**  
   - **Bivariate correlation** to measure direct relationships.  
   - **OLS regression** to quantify the impact of energy use on GDP.

---

## 🧮 Key Findings

- Energy use per capita is **positively correlated** with GDP per capita across all six countries.  
- The OLS regression indicates that **higher energy use predicts higher income levels**, suggesting energy access supports productivity and growth.  
- **R² ≈ 0.70–0.80**, indicating strong explanatory power of energy consumption for GDP.  
- Differences across regions reflect variations in industrial structure, energy efficiency, and investment in infrastructure.

*(Full regression summary tables and plots are available in the notebook.)*

---

## 🧠 Interpretation

Energy consumption is a key enabler of economic activity.  
Countries with efficient and diversified energy systems achieve stronger and more sustainable economic growth.  
Policies enhancing access to reliable, affordable, and clean energy can therefore play a critical role in achieving inclusive growth.

---

## 💻 Run it Yourself

You can open and run this notebook directly on Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fjnelima-pixel/energy_analytics_project/blob/main/Energy_Analytics.ipynb)

---

## 🗂️ Data Source
- **World Development Indicators (World Bank, 2024)**  
  - Indicator 1: `EG.USE.PCAP.KG.OE` — Energy use (kg of oil equivalent per capita)  
  - Indicator 2: `NY.GDP.PCAP.CD` — GDP per capita (current US$)

---

## 🧩 Author
**Faith Nelima- Data and Policy Analyst**  
Portfolio: [github.com/fjnelima-pixel](https://github.com/fjnelima-pixel)

---

### ⭐ If you found this project useful, please consider giving it a star on GitHub!
