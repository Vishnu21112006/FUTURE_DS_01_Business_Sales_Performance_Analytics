# 📊 Business Sales Performance Analytics

**Future Interns – Data Science Internship | Task 1**

## 📌 Project Overview

This project focuses on analyzing Superstore sales data to identify business performance trends, understand customer purchasing patterns, and generate actionable business insights.

The analysis was performed using Python, Pandas, Matplotlib, Seaborn, and Microsoft Power BI.

## 🎯 Project Objectives

- Clean and preprocess the sales dataset.
- Analyze sales and profit across product categories and sub-categories.
- Identify regional sales and profit performance.
- Understand monthly and yearly sales trends.
- Develop an interactive Power BI dashboard.
- Generate meaningful business insights and recommendations.

## 🛠️ Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Power BI
- Git and GitHub

## 🧹 Data Cleaning and Preprocessing

The original dataset contained 9,994 records and 9 columns.

The following cleaning operations were performed:

- Checked for missing values.
- Identified duplicate records.
- Removed 2 duplicate rows.
- Converted Order Date into datetime format.
- Verified numerical data types.
- Checked for negative sales and negative quantities.

**Dataset summary:**

| Description | Records |
|---|---:|
| Original records | 9,994 |
| Duplicate rows removed | 2 |
| Final cleaned records | 9,992 |
| Missing values remaining | 0 |

## 📈 Exploratory Data Analysis

The following analyses were performed:

1. Sales and profit analysis by product category.
2. Top 10 sub-categories by sales.
3. Regional sales and profit analysis.
4. Monthly sales trend analysis.
5. Year-wise sales performance.

## 🔍 Key Business Insights

### 1. Category Performance

- Technology generated the highest sales of 836,154.03.
- Technology also generated the highest profit of 145,454.95.
- Furniture generated 741,713.50 in sales but only 18,462.59 in profit.
- Office Supplies generated 719,047.03 in sales and 122,490.80 in profit.

### 2. Sub-Category Performance

- Phones recorded the highest sales of 330,007.05.
- Chairs generated 328,167.73 in sales.
- Tables recorded a loss of 17,725.48.
- Bookcases also recorded a loss of 3,472.56.

### 3. Regional Performance

- West recorded the highest regional sales of 725,457.82.
- East generated the highest regional profit of 91,534.84.
- Central generated 39,706.36 in profit.
- South recorded the lowest regional sales of 391,716.98.

### 4. Monthly and Yearly Trends

- November 2017 recorded the highest monthly sales of 118,447.82.
- February 2014 recorded the lowest monthly sales of 4,519.89.
- 2017 recorded the highest annual sales of 733,215.26.

## 💡 Business Recommendations

- Focus on expanding profitable Technology products.
- Investigate the reasons behind losses in Tables and Bookcases.
- Develop targeted marketing strategies for regions with lower sales.
- Analyze seasonal sales patterns to improve inventory planning.
- Improve profitability by monitoring product-level costs and discount strategies.

## 📊 Power BI Dashboard

An interactive dashboard was developed using Microsoft Power BI.

The dashboard includes:

- Total Sales KPI
- Total Profit KPI
- Total Quantity KPI
- Sales by Category
- Profit by Region
- Monthly Sales Trend (2014–2017)
- Top 10 Sub-Categories by Sales
- Region and Category slicers

## 📁 Project Structure

```text
FUTURE_DS_01_Business_Sales_Performance_Analytics/
│
├── dashboard/
│   └── Superstore_Sales_Dashboard.pbix
│
├── dataset/
│   ├── superstore_sales.csv
│   └── superstore_cleaned.csv
│
├── images/
│   └── charts/
│
├── notebooks/
│   └── sales_analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## ▶️ How to Run the Project

1. Clone this repository.

```bash
git clone https://github.com/Vishnu21112006/FUTURE_DS_01_Business_Sales_Performance_Analytics.git
```

2. Open the project in VS Code.

3. Install the required Python libraries.

```bash
pip install pandas matplotlib seaborn jupyter
```

4. Open `notebooks/sales_analysis.ipynb`.

5. Run the notebook cells to perform the analysis.

6. Open the `.pbix` file using Microsoft Power BI Desktop to explore the interactive dashboard.

## 🏁 Conclusion

This project demonstrates how data cleaning, exploratory data analysis, visualization, and business intelligence tools can transform raw sales data into meaningful business insights.

The findings help identify profitable product categories, understand regional performance, recognize sales trends, and support better business decision-making.

---

**Project:** Future Interns – Data Science Internship  
**Task:** Task 1 – Business Sales Performance Analytics  
**Tools:** Python | Pandas | Matplotlib | Seaborn | Power BI