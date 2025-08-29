# Superstore EDA Project

Exploratory Data Analysis on the Superstore dataset using Python, Pandas, Matplotlib, and Seaborn.  
This project demonstrates the ability to clean, analyze, and visualize data to extract actionable business insights.

## Project Structure
- `notebook/` → Jupyter notebook with full analysis
- `data/` → dataset CSV (Superstore.csv)
- `images/` → plots generated during analysis

## Preview of Analysis

### Top Products
![Top Products](images/top_products.png)

### Sales by Category
![Category Sales](images/category_sales.png)

### Profit by Region
![Profit by Region](images/profit_by_region.png)

### Discounts vs Profit
![Discount vs Profit](images/discount_vs_profit.png)

---

## Key Insights

- **Top Products:** The highest selling products include `Staples`, `Binders`, `Pens`, `Paper`, and `Art Supplies`.  
- **Most Profitable Regions:** The `West` region generated the highest profit overall.  
- **Sales Patterns:** 
  - The `Office Supplies` category generates the most sales, followed by `Furniture` and `Technology`.  
  - Discounts are negatively correlated with profit (correlation ≈ -0.25), indicating that higher discounts tend to reduce profit.  
  - Some product sub-categories like `Copiers` and `Chairs` contribute disproportionately to total profit despite lower sales volume.

---

## Next Steps

- Create an interactive dashboard using **Streamlit** to explore sales, profit, and discounts by region, category, and product.  
- Develop predictive models to forecast **future sales** and **profit** based on historical data.  
- Save and document all visualizations in the `images/` folder for portfolio presentation.

---

## Explore the Notebook

[Open Superstore EDA Notebook](notebook/superstore_eda.ipynb)

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/pqpedra/superstore-eda.git