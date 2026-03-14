# TS_Academy_Capstone_Project

#  Chocolate Sales Analysis

##  Overview
This project explores chocolate sales data across multiple countries,
products, and sales representatives. The goal is to uncover sales trends,
top-performing products and salespeople, and regional performance patterns
through exploratory data analysis and visualisation.

---

##  Dataset
- **Rows:** 3,282 entries
- **Features:** 6 columns

| Column | Description | Type |
|---|---|---|
| `Sales Person` | Name of the sales representative | object |
| `Country` | Country where the sale was made | object |
| `Product` | Name of the chocolate product sold | object |
| `Date` | Date of the sale | object |
| `Amount` | Revenue generated from the sale | object |
| `Boxes Shipped` | Number of boxes shipped for the sale | int64 |

---

##  Objectives
- Clean and preprocess the dataset (parse dates, convert Amount to numeric)
- Explore overall sales trends over time
- Identify top-performing salespeople, products, and countries
- Analyse the relationship between boxes shipped and revenue
- Visualise regional and product-level performance
- Time series forecasting 
- SARIMA Forecasting Model
- Model Diagnostics

---

##  Tech Stack
| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical computing |
| Matplotlib / Seaborn | Data visualisation |
| Jupyter Notebook | Development environment |

---

##  Analysis Workflow

### 1. Data Cleaning
- Convert `Date` column from object to datetime
- Convert `Amount` column from object to numeric (remove currency symbols)
- Check for missing values and duplicates

### 2. Exploratory Data Analysis (EDA)
- Sales distribution by country, product, and salesperson
- Monthly and yearly sales trends
- Top 10 products and top 10 salespeople by revenue

### 3. Revenue vs. Boxes Shipped
- Correlation between boxes shipped and amount earned
- Average revenue per box by product and country

### 4. Visualisations
- Bar charts for top products and salespeople
- Line chart for sales trends over time
- Heatmap of sales by country and month

---

##  Key Findings
| Feature | highest Revenue |
|---|---|
| Country  | Australia |
| Product | Smooth Sliky Salty |
|Sales Person | Ches Bonnell |
- January has the highest revenue likely driven by festive demand

---
