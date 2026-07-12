# 📊 Retail Customer Behavior Analysis Dashboard

### SQL Server • Python • NLP (VADER) • Power BI

---

## 🚀 Project Overview

This project presents an end-to-end retail customer analytics solution that combines SQL Server, Python, and Power BI to transform raw customer interaction data into actionable business insights.

The workflow covers the complete analytics lifecycle—from data validation and cleaning to sentiment analysis, dashboard development, and business recommendations.

The objective is to identify customer behavior patterns, understand conversion bottlenecks, evaluate marketing performance, and analyze customer sentiment to support better business decisions.

---

# 🎥 Dashboard Walkthrough

> *(Upload your GIF here)*

<p align="center">

<img src="images/walkthrough.gif" width="900">


https://github.com/user-attachments/assets/afb5ce5f-e3a9-4d4f-ad09-d67dbed7a88e



</p>

---

# 📌 Business Problem

Retail companies collect millions of customer interactions every day.

However, raw business data alone cannot answer important questions like:

- Why are customers abandoning purchases?
- Which products perform poorly?
- What are customers complaining about?
- Which marketing channels drive engagement?
- Which products require immediate attention?

This project answers these questions through an end-to-end analytics pipeline.

---

# ⚙️ Technology Stack

| Technology | Purpose |
|------------|---------|
| SQL Server | Data Validation & Cleaning |
| Python | Sentiment Analysis |
| Pandas | Data Processing |
| NLTK (VADER) | Natural Language Processing |
| SQLAlchemy | Database Connection |
| PyODBC | SQL Server Connectivity |
| Power BI | Dashboard Development |
| DAX | KPI Calculations |

---

# 🔄 Project Workflow

```text
Raw Retail Data
        │
        ▼
SQL Data Validation
        │
        ▼
SQL Cleaning & Transformation
        │
        ▼
Python NLP Sentiment Analysis
        │
        ▼
Processed Data
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Insights
```

---

# 📂 Dataset

The project uses six datasets.

| Dataset | Description |
|-----------|-------------|
| Customer Journey | Customer purchase journey |
| Customer Reviews | Product reviews |
| Engagement Data | Marketing engagement |
| Customers | Customer information |
| Products | Product details |
| Geography | Customer location |

---

# 🧹 SQL Data Preparation

The SQL phase focuses on preparing high-quality data for analysis.

### Data Validation

✔ NULL Value Analysis

✔ Duplicate Detection

✔ Rating Validation

✔ Case Sensitivity Checks

✔ Invalid Data Detection

✔ Data Quality Assessment

### Data Cleaning

✔ Removed Logical Duplicates

✔ Standardized Text Casing

✔ Cleaned Customer Reviews

✔ Split Combined Columns

✔ Data Type Conversion

✔ Created Analysis-Ready Tables

---

# 🤖 Python Sentiment Analysis

Python was used to perform Natural Language Processing on customer reviews.

### Tasks Performed

- Connected SQL Server
- Loaded Cleaned Data
- Performed Sentiment Analysis using VADER
- Generated Sentiment Scores
- Classified Customer Reviews
- Extracted Negative Reviews
- Categorized Customer Issues
- Exported Results for Power BI

---

# 📊 Power BI Dashboard

The dashboard is divided into four interactive report pages.

---

# 🏠 Overview Dashboard

<p align="center">

<img width="1304" height="733" alt="Overview" src="https://github.com/user-attachments/assets/1596a353-0632-4a61-a238-c2e227a8c871" />


</p>

### Highlights

- Overall Conversion Rate
- Customer Sentiment
- Click Through Rate
- Product Performance
- Monthly Trends

---

# 😊 Customer Sentiment Dashboard

<p align="center">

<img width="1303" height="729" alt="Customer Sentiment" src="https://github.com/user-attachments/assets/372d2579-4631-47ae-8552-d894f569ed76" />


</p>

### Highlights

- Sentiment Distribution
- Product Health Score
- Customer Rating Analysis
- Review Issue Categories
- Product-wise Sentiment

---

# 🔄 Conversion Analysis Dashboard

<p align="center">

<img src="images/conversion.png" width="950">
<img width="1302" height="731" alt="Conversion Analysis" src="https://github.com/user-attachments/assets/8f76114a-f3d4-4070-bb83-9631ad17c626" />


</p>

### Highlights

- Customer Purchase Funnel
- Conversion Rate
- Checkout Drop-off
- Monthly Conversion Trend
- Product-wise Conversion

---

# 📢 Marketing Performance Dashboard

<p align="center">
        
<img width="1302" height="731" alt="Marketing Performance" src="https://github.com/user-attachments/assets/944aeffc-e7f3-4062-bb62-df374db5a76f" />


</p>

### Highlights

- Total Views
- Total Clicks
- Total Likes
- Marketing Funnel
- Quarterly Engagement
- Product-wise Click Performance

---

# 📈 Key Business Insights

The analysis reveals several actionable insights:

- High customer drop-off during the checkout stage.
- Strong product engagement does not always translate into purchases.
- Customer reviews reveal recurring product-related concerns.
- Marketing engagement varies across products and time periods.
- Product performance differs significantly across categories.

---

# 💡 Business Recommendations

Based on the analysis:

- Improve checkout experience to reduce customer abandonment.
- Optimize product pages with poor conversion rates.
- Address recurring issues identified in customer reviews.
- Reallocate marketing budget toward high-performing products.
- Monitor product health using combined customer feedback and conversion metrics.

---

# 🛠 Skills Demonstrated

- SQL Query Writing
- Data Validation
- Data Cleaning
- Window Functions
- Common Table Expressions
- Python Programming
- NLP using VADER
- Data Visualization
- Dashboard Design
- Business Intelligence
- DAX
- Data Storytelling

---

# 📁 Repository Structure

```text
Retail-Customer-Behavior-Analysis
│
├── SQL
├── Python
├── Output
├── PowerBI
├── images
└── README.md
```

---

# 🚀 Future Enhancements

- Customer Segmentation (RFM)
- Customer Lifetime Value (CLV)
- Sales Forecasting
- Cohort Analysis
- Predictive Analytics
- Automated Data Pipeline

---


https://github.com/user-attachments/assets/fdca041d-05b0-4b19-8bf5-8baa1d13cc85


