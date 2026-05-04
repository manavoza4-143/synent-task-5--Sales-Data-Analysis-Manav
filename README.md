# synent-task-5--Sales-Data-Analysis-Manav

# 📊 Sales Data Analysis – Superstore Dataset

---

## 🔹 Problem Statement

The goal of this project is to analyze business performance using the Superstore Sales dataset. The analysis focuses on identifying key trends, top-performing products, and overall revenue patterns to support data-driven decision-making.

---

## 🔹 Dataset Details
Dataset Name: Superstore Sales Dataset
Source: Public retail dataset commonly used for data analysis and visualization tasks
File Used: train.csv
📎 Dataset Link

You can access the dataset here:
👉 superstoredataset https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

📊 Dataset Description

The dataset contains transactional sales data of a retail store, including:

Order and shipping details
Customer information
Product categories and names
Regional sales distribution
Revenue (Sales) data
📌 Key Columns:
Order Date – Date of purchase
Ship Date – Delivery date
Category – Product category
Sub-Category – Sub classification
Product Name – Name of the product
Region – Sales region
Sales – Revenue generated
⚠️ Note:

The dataset does not include a Profit column, so profit was estimated as 20% of Sales for analysis purposes.

---

## 🔹 Objective

Analyze business performance based on:

* Monthly revenue trends
* Top-selling products
* Profit analysis (estimated)

---

## 🔹 Approach

1. **Data Loading & Cleaning**

   * Imported dataset using Pandas
   * Converted date columns to datetime format using `dayfirst=True`

2. **Exploratory Data Analysis (EDA)**

   * Checked missing values and data types
   * Generated summary statistics

3. **Monthly Revenue Analysis**

   * Extracted Year-Month from Order Date
   * Grouped sales data to identify monthly trends

4. **Top-Selling Products**

   * Aggregated sales by product name
   * Identified top 10 products contributing highest revenue

5. **Category-wise Analysis**

   * Compared sales across different categories

6. **Profit Analysis (Estimated)**

   * Created Profit column assuming 20% margin
   * Analyzed relationship between Sales and Profit

7. **Visualization**

   * Line chart for revenue trends
   * Bar charts for category and product performance
   * Scatter plot for Sales vs Profit
   * Heatmap for correlation analysis

---

## 🔹 Results

* **Revenue Trends:**

  * Sales vary across months, showing seasonal patterns
  * Certain months contribute significantly higher revenue

* **Top Products:**

  * A small number of products generate a major share of total sales

* **Category Performance:**

  * Some categories dominate overall revenue contribution

* **Sales vs Profit:**

  * Strong positive relationship observed
  * Higher sales lead to higher estimated profit

* **Correlation Insights:**

  * Sales is the primary driver of profit (as expected from estimation)

---

## 🔹 Conclusion

The analysis provides valuable insights into business performance:

* Sales are unevenly distributed across time and products
* Top-performing products and categories drive revenue growth
* Estimated profit analysis shows a direct relationship with sales

**Important Note:**
Profit values were not available in the dataset and were approximated. Therefore, profit-related findings are indicative.

---

## 🔹 Output

* Jupyter Notebook (`.ipynb`) containing:

  * Data analysis
  * Visualizations
  * Business insights

---

## 🔹 Recommendations

* Focus on high-performing products for marketing
* Improve strategies in top-performing categories
* Target high-revenue months for campaigns
* Use real profit data for accurate financial insights

---

## 🔹 Task Reference

**Task 5: Sales Data Analysis**

* Dataset: Superstore Sales Dataset
* Objective: Analyze business performance
* Tasks:

  * Monthly revenue trends
  * Top-selling products
  * Profit analysis
* Output:

  * Business insights report

---

🔹 Author

Name: MAANAV M OZA
