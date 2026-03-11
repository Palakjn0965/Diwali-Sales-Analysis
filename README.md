# 🪔 Diwali Sales Data Analysis

An exploratory data analysis (EDA) project on Diwali season sales data, uncovering key trends across customer demographics, product categories, and geographic regions.

---

## 📊 Dataset

- **Source:** [Kaggle – Diwali Sales Dataset](https://www.kaggle.com/)
- **Size:** 11,252 rows
- **Features:** Customer ID, Gender, Age Group, State, Product Category, Orders, Revenue, and more

---

## 🛠️ Tools & Libraries

| Library | Purpose |
|--------|---------|
| `Pandas` | Data loading, cleaning, and manipulation |
| `NumPy` | Numerical operations |
| `Matplotlib` | Data visualization (bar charts, plots) |
| `Seaborn` | Enhanced statistical visualizations |

---

## 🔍 Key Findings

### 💰 Overall Numbers
- **Total Revenue:** ₹106.25 Crore
- **Total Orders:** 27,981
- **Average Order Value (AOV):** ₹3,797

### 👥 Customer Trends
- **Female customers** drive ~70% of total revenue vs ~30% from male customers — making them the primary target segment during Diwali
- The **26–35 age group** generates the highest revenue, suggesting stronger purchasing power or higher purchase frequency in this demographic

### 🛍️ Top Product Categories (by Revenue)
1. Food
2. Clothing & Apparel
3. Electronics & Gadgets

> Customers prioritize consumables and lifestyle products during Diwali, with Electronics also performing strongly — likely driven by gifting and personal upgrades.

### 🗺️ Top Revenue-Generating States
1. Uttar Pradesh
2. Maharashtra
3. Karnataka

> Sales are concentrated in large, high-population states, likely reflecting both purchasing power and distribution reach. Central and Western zones dominate overall revenue contribution.
---

## 💡 Observations & Limitations

- Heavy revenue dependence on a single gender group and a few states may indicate gaps in reach
- Strong reliance on a few product categories could be a risk if demand shifts
- A small number of records with missing revenue values were excluded from calculations
- Analysis is based on existing data only — no external assumptions or forecasts were made
