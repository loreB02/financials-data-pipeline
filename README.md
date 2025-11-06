# 📊 Financials Data Pipeline

- This project develops a complete data analysis workflow (**ETL + EDA + BI**) using a sales and revenue dataset broken down by **segment, country, and product**.
- The goal is to demonstrate the integrated application of **Python, SQL, and Power BI** to extract business insights from raw data.
---

## 🧩 Project Objectives

- Clean and transform financial data using **Python (Pandas)**.
- Perform **Exploratory Data Analysis (EDA)** with **Matplotlib** and **Seaborn**.
- Query information using **SQL (SQLite3)** within the Python environment.
- Design a **dashboard in Power BI** with key metrics (Coming soon).
---

## ⚙️ ETL Process

**Extract:**  
Load the dataset in CSV format.

**Transform:**  
- Standardization of names and formats.
- Conversion of numeric columns (removal of `$`, `,`, `-`).
- Replacement of null values ​​and normalization of text.

**Load:**  
Exporting the clean data to a local **SQLite (`financials.db`)** database.

---

## 🔍 Exploratory Data Analysis (EDA)

Visualizations were used to understand key relationships:

- **Discounts vs. sales relationship by segment** (`sns.scatterplot`)
- **Total sales by country** (`plt.bar`)
- **Monthly Sales Trend by Year** (`sns.lineplot`)
- **Average Profit by Segment** (`plt.bar`)
---


