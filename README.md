# 🛒 BlinkIT Grocery Sales Analysis

### Retail & Grocery Sales Analytics | Python | Pandas | NumPy | Matplotlib | Seaborn

## 📌 Project Overview

This project focuses on analyzing grocery sales data from BlinkIT to understand sales performance, product trends, and outlet-level performance.

The analysis was conducted as part of a Data Analyst project for **Sapphire IQ**, with the objective of transforming raw sales data into meaningful business insights that can support better inventory planning, product decisions, and outlet performance evaluation.

## 🎯 Business Objectives

The project addresses four key business objectives:

1. **Understand Sales Performance:** Analyze total sales, product categories, outlet performance, and customer ratings.
2. **Ensure Data Quality:** Identify missing values, duplicate records, outliers, and inconsistent categories.
3. **Identify Sales Drivers:** Explore the relationship between product types, outlet characteristics, item visibility, weight, and sales.
4. **Support Business Decisions:** Generate actionable recommendations to improve product assortment, inventory planning, and outlet performance.

## 📂 Dataset Overview

The dataset contains **8,523 records and 12 original columns**, covering product attributes and outlet-level information.

Key attributes include:

- Item Identifier
- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Item MRP
- Outlet Identifier
- Outlet Establishment Year
- Outlet Size
- Outlet Location Type
- Outlet Type
- Item Outlet Sales

After data preparation, an additional derived column, `Weight Category`, was created for advanced analysis.

## 🛠️ Tools & Technologies

| Tool / Library | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Analysis environment |

## 🧹 Data Cleaning & Preparation

The following data-cleaning operations were performed:

- Identified and handled missing values in `Item Weight`.
- Imputed missing weights using product-level median values, followed by category-level median values.
- Standardized inconsistent values in `Item Fat Content`.
- Checked
