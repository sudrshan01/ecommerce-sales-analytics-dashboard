# Superstore Sales Analytics Dashboard

## Project Overview

The Superstore Sales Analytics Dashboard is a data analysis project developed using Python to analyze retail sales data and generate actionable business insights. This project explores sales performance, profitability, customer behavior, and product trends using data analysis and visualization techniques.

The goal of this project is to transform raw sales data into meaningful insights that can support business decision-making.

---

## Objectives

- Analyze overall sales performance.
- Identify top-selling products and categories.
- Evaluate profit and loss trends.
- Analyze regional sales performance.
- Understand customer purchasing behavior.
- Generate visualizations to support business insights.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```text
Superstore-Sales-Analytics-Dashboard/
│
├── data/
│   └── Superstore-final.xlsx
│
├── python/
│   ├── basic_analysis.ipynb
│   ├── customers&orders_analysis.ipynb
│   └── sales&profit_analysis.ipynb
│
├── output/
│
│   ├── basic_analysis/
│   │   ├── monthly_sales_trend.png
│   │   ├── Profit by Category.png
│   │   └── Sales by Region.png
│   │
│   ├── customer_orders/
│   │   ├── Ordered Multiple Items vs Single Items percentage.png
│   │   ├── Customer Reordered vs Single Order Products.png
│   │   ├── Orders and Sales by Segment.png
│   │   ├── Product Order Distribution.png
│   │   ├── Region-wise Customers and Orders.png
│   │   ├── Reordered vs Single Order Products.png
│   │   ├── Repeated vs Non-Repeated Customers percentage.png
│   │   ├── Repeated vs Non-Repeated Customers.png
│   │   ├── Segment-wise Customers and Orders.png
│   │   ├── Segment-wise Sales and Profit.png
│   │   └── Top 10 Most Ordered Products.png
│   │
│   └── sale_profit/
│       ├── Monthly Profit Trend by Year.png
│       ├── Monthly Sales Trend by Year.png
│       ├── Overall Monthly Sales and Profit (2014-2017).png
│       ├── Sales and Profit by Category.png
│       ├── Sales and Profit by Region.png
│       ├── Sales and Profit by Sub-Category.png
│       ├── Segment-wise Sales and Profit.png
│       ├── Top 10 Least Profitable Products.png
│       ├── Top 10 Most Profitable Products.png
│       ├── Total Sales and Profit Performance.png
│       ├── Year-over-Year Sales and Profit Growth (%).png
|       ├── Year-wise Sales and Profit Analysis (2014-2017)1.png
│       └── Year-wise Sales and Profit Analysis (2014-2017).png
│
├── README.md
└── .gitignore
```

---

##  Analysis Performed

### Sales Analysis
- Total Sales
- Monthly Sales Trends
- Yearly Sales Trends
- Sales by Region
- Sales by Category
- Sales by Sub-Category

### Profit Analysis
- Total Profit
- Profit by Region
- Profit by Category
- Most Profitable Products
- Least Profitable Products

### Customer Analysis
- Top Customers by Sales
- Customer Purchase Patterns
- Order Frequency Analysis

### Product Analysis
- Best-Selling Products
- Product Reorder Analysis
- Product Performance Evaluation

---

## Visualizations Included

- Bar Charts
- Pie Charts

These visualizations help identify trends, patterns, and business opportunities within the dataset.

---

##  Installation

### Clone the Repository

```bash
git clone https://github.com/sudrshan01/Superstore-Sales-Analytics.git
```

### Navigate to the Project Directory

```bash
cd Superstore-Sales-Analytics
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open either notebook:

```text
python/analysis.ipynb
```

or

```text
python/advance_analysis.ipynb
```

Run all cells to perform analysis and generate visualizations.

---

## Key Insights

- Identified top-performing products and categories.
- Analyzed profit contribution across regions.
- Evaluated customer purchasing behavior.
- Explored sales trends over time.
- Generated visual reports to support decision-making.

---

##  Dataset Information

The project uses the Superstore Sales Dataset containing:

- Order Details
- Customer Name
- Product Name
- Product Id
- Sales Data
- Profit Data
- Regional Information
- Ship Date
- order Date
- etc

---



## Author

### Sudrshan Genure

- Aspiring Data Analyst
- Python Developer
- Data Visualization Enthusiast
- Learning Data Analytics and Business Intelligence

### Skills

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- Excel
- Power BI

---

## Future Enhancements

- Interactive Power BI Dashboard
- Sales Forecasting
- Customer Segmentation
- KPI Dashboard Development
- Automated Reporting
- Machine Learning-Based Insights

---

## 📄 License

This project is created for educational and portfolio purposes.

If you found this project useful, feel free to star ⭐ the repository.
