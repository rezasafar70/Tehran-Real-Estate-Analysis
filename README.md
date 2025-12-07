# 🏠 Tehran Real Estate Market Analysis

### 📋 Overview
This project analyzes the housing market in **Tehran, Iran**, using real-world data scraped from **Divar**. The goal is to clean raw data, handle outliers, and visualize price trends across different neighborhoods to identify investment opportunities.

### 🛠️ Technologies Used
* **Python** (Core Logic)
* **Pandas** (Data Cleaning & Manipulation)
* **Matplotlib** (Data Visualization)
* **NumPy** (Numerical Operations)

### 🔍 Key Features
1.  **Data Cleaning:** Handling missing values in addresses and converting object types (Area) to numeric.
2.  **Outlier Removal:** Filtering unrealistic prices (e.g., 0 Toman) and extreme areas (e.g., > 1000 meters).
3.  **Feature Engineering:** Calculated **Price Per Meter (PPP)** for accurate comparison.
4.  **Visualization:** Bar charts for top expensive neighborhoods and Scatter plots for Price/Area correlation.

### 📊 Key Findings
* The most expensive neighborhood in this dataset was identified as **Gandhi**.
* There is a strong correlation between area and price, but outliers exist that present potential undervalued opportunities.

### 🚀 How to Run
1.  Clone the repo:
    ```bash
    git clone [https://github.com/YOUR-USERNAME/Tehran-Real-Estate-Analysis.git](https://github.com/YOUR-USERNAME/Tehran-Real-Estate-Analysis.git)
    ```
2.  Install requirements:
    ```bash
    pip install pandas matplotlib
    ```
3.  Run the script!

---
*Created by Reza Safar*
