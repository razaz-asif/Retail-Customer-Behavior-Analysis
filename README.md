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

<img src="images/overview.png" width="950">

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

<img src="images/sentiment.png" width="950">

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

<img src="images/marketing.png" width="950">

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

# 👨‍💻 Author

## Asif Raza

B.Tech – Electronics & Communication Engineering

Delhi Technological University (DTU)

**Interested in**

- Data Analytics
- SQL
- Python
- Power BI
- Business Intelligence

---

# ⭐ If you found this project useful, consider giving it a Star!
