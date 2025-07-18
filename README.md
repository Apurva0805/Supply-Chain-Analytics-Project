# 📦 Supply Chain Analytics – Python & Power BI

This project analyzes order delivery data to identify delays, cost trends, and regional performance in a supply chain process.

## 🔍 Objective

To uncover insights on delivery performance and build an interactive dashboard that supports business decisions using real-world supply chain data.

## 📁 Dataset

A sample dataset with:
- Order ID, Product ID, Product Name
- Region, Order Date
- Expected vs Actual Delivery Time
- Delivery Cost

## 🔧 Tools & Technologies

- Python (Pandas, NumPy)
- Excel (for initial exploration)
- Power BI (dashboard)
- GitHub (version control)
- Jupyter Notebook

## 📊 Key Steps

1. **Data Cleaning (Pandas)**  
   - Removed nulls  
   - Created a new column `Delayed` based on delivery time  
   - Calculated delay % by Region

2. **Exploratory Data Analysis (EDA)**  
   - Average delivery time per region  
   - Total orders and delayed orders  
   - Visual summaries


## 📈 Results

- Found that ~33% of orders in South region were delayed  
- Delivery time in North was fastest on average  
- Monitor and optimize delay-prone regions

## 🔗 Output Files

- `notebooks/EDA_Supply_Chain.ipynb` – Python exploration  
- `data/supply_chain_data.csv` – Original dataset  
- `cleaned/cleaned_supply_chain.csv` – Cleaned data  
- `dashboard/PowerBI_Report.pbix` – Final dashboard

## 🧠 Learnings

- Practiced data cleaning and grouping in Pandas  
- Built my first Power BI dashboard using real-world metrics  
- Improved storytelling with data

---

