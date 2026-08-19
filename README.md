# 📊 CodeAlpha Task 2 – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on the **Global Superstore dataset** using Python.

The objective is to explore sales performance, customer segments, regional trends, product performance, monthly sales patterns, outliers, and relationships between numerical variables.

The analysis transforms raw business data into meaningful insights that can support **data-driven business decision-making**.

---

## 🎯 Objectives

- Understand the structure and quality of the dataset
- Analyze overall sales performance
- Compare sales across product categories
- Analyze regional sales performance
- Compare customer segments
- Identify monthly sales trends
- Identify top-performing products
- Detect sales outliers
- Analyze correlations between numerical variables
- Generate actionable business recommendations

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Google Colab** – Development environment
- **GitHub** – Project documentation and version control

---

## 📂 Dataset

The analysis uses the **Global Superstore dataset**.

### Dataset Information

- **Rows:** 9,800
- **Columns:** 18
- **Target Metric:** Sales

### Important Features

- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Postal Code
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales

---

## 🔍 Exploratory Data Analysis

### 1. Data Overview

The dataset was inspected for:

- Number of rows and columns
- Column names
- Data types
- Missing values
- Duplicate records
- Basic statistical information

The dataset contains **9,800 records** and **18 columns**.

There were **no duplicate rows**.

The only missing values were found in the **Postal Code** column, with 11 missing records.

---

## 📈 Key Business Metrics

| Metric | Value |
|---|---:|
| Total Sales | 2,261,536.78 |
| Average Sale | 230.77 |
| Minimum Sale | 0.444 |
| Maximum Sale | 22,638.48 |
| Total Orders | 4,922 |
| Total Customers | 793 |

---

## 📊 Sales by Product Category

The analysis identified the following category performance:

| Category | Total Sales |
|---|---:|
| Technology | 827,455.87 |
| Furniture | 728,658.58 |
| Office Supplies | 705,422.33 |

### Insight

**Technology** generated the highest total sales, followed by **Furniture** and **Office Supplies**.

---

## 🌎 Sales by Region

| Region | Total Sales |
|---|---:|
| West | 710,219.68 |
| East | 669,518.73 |
| Central | 492,646.91 |
| South | 389,151.46 |

### Insight

The **West region** generated the highest total sales, while the **South region** recorded the lowest sales.

---

## 👥 Sales by Customer Segment

| Customer Segment | Total Sales |
|---|---:|
| Consumer | 1,148,061.00 |
| Corporate | 688,849.10 |
| Home Office | 424,982.20 |

### Insight

The **Consumer segment** is the strongest contributor to overall sales.

---

## 📅 Monthly Sales Trend

Monthly sales were analyzed using the Order Date.

The analysis shows that sales fluctuate significantly across months, with several noticeable peaks and declines.

The overall trend indicates increasing sales activity toward the later part of the dataset, with some strong monthly peaks.

---

## 🏆 Top 10 Products by Sales

The highest-selling products include:

1. Canon imageCLASS 2200 Advanced Copier
2. Fellowes PB500 Electric Punch Plastic Comb Binding Machine
3. Cisco TelePresence System EX90 Videoconferencing Unit
4. HON 5400 Series Task Chairs for Big and Tall
5. GBC DocuBind TL300 Electric Binding System
6. GBC Ibimaster 500 Manual ProClick Binding System
7. Hewlett Packard LaserJet 3310 Copier
8. HP Designjet T520 Inkjet Large Format Printer
9. GBC DocuBind P400 Electric Binding System
10. High Speed Automatic Electric Letter Opener

### Insight

The **Canon imageCLASS 2200 Advanced Copier** was the highest-selling product in the analysis.

---

## 🚨 Outlier Analysis

The **Interquartile Range (IQR)** method was used to identify unusual sales values.

### Results

- **Q1:** 17.248
- **Q3:** 210.605
- **IQR:** 193.357
- **Lower Bound:** -272.788
- **Upper Bound:** 500.641
- **Sales Outliers:** 1,145

### Insight

The dataset contains a significant number of high-value sales transactions. These may represent premium products or large business orders rather than data errors.

---

## 🔗 Correlation Analysis

Correlation analysis was performed on numerical variables.

The analysis showed:

- Sales and Postal Code have almost no correlation.
- Sales and Row ID have almost no correlation.
- Postal Code and Row ID also have very weak correlation.

This indicates that these numerical fields do not have a meaningful linear relationship with Sales.

---

## 💡 Business Recommendations

Based on the EDA findings:

- Strengthen strategies around the high-performing **Technology** category.
- Investigate the success factors behind the **West region**.
- Develop targeted campaigns to improve **South region** performance.
- Prioritize the **Consumer segment** through personalized offers.
- Analyze seasonal sales patterns for better inventory and marketing planning.
- Maintain availability of high-performing products such as the **Canon imageCLASS 2200 Advanced Copier**.
- Investigate high-value outlier transactions to identify opportunities for premium products and larger orders.

---

## 📊 Visualizations

The project includes visualizations for:

- Sales by Product Category
- Sales by Region
- Sales by Customer Segment
- Monthly Sales Trend
- Top 10 Products by Sales
- Sales Distribution and Outliers
- Correlation Heatmap

---

## 🧠 Key Learnings

Through this project, I gained practical experience in:

- Data cleaning and preprocessing
- Exploratory Data Analysis
- Pandas data manipulation
- GroupBy and aggregation
- Date-time analysis
- Statistical analysis
- Outlier detection using IQR
- Correlation analysis
- Data visualization
- Extracting business insights from raw data

---

## 📁 Project Structure

```text
CodeAlpha_Task2_EDA/
│
├── CodeAlpha_Task2_EDA.ipynb
└── README.md

---

## 👩‍💻 Author

**Saranya Bandlamudi**

B.Tech – Computer Science Engineering

Aspiring Data Analyst

### Skills

Python | Pandas | NumPy | SQL | Power BI | Excel | Data Visualization

---

## 🚀 Future Scope

The insights obtained from this EDA will serve as the foundation for the next stage of the project:

**CodeAlpha Task 3 – Data Visualization**

Future enhancements can include:

- Interactive dashboards using Power BI
- Advanced sales forecasting
- Profitability analysis
- Customer-level analysis
- Product-level performance analysis
- Regional performance monitoring
- Advanced business intelligence reporting
