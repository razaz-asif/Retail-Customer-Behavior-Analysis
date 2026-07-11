# Retail Customer Behavior & Sentiment Analysis Dashboard

An end-to-end Data Analytics project that analyzes customer behavior, marketing performance, and customer sentiment using **SQL Server, Python, and Power BI**.

The project demonstrates the complete analytics workflow—from raw data validation and cleaning to sentiment analysis and interactive business dashboards.

---

## Project Overview

Retail businesses generate large volumes of customer interaction data, product reviews, and marketing metrics. However, raw data often contains duplicates, inconsistent formatting, and missing values that must be cleaned before meaningful analysis.

This project focuses on:

- Understanding customer purchase behavior
- Identifying conversion bottlenecks
- Analyzing customer reviews using NLP
- Measuring marketing performance
- Building an interactive Power BI dashboard for business decision-making

---

## Business Objectives

The project answers the following business questions:

- Where are customers dropping off during the purchase journey?
- Which products receive the most negative feedback?
- What are the major reasons behind customer dissatisfaction?
- How effective are different marketing channels?
- Which products require immediate business attention?

---

## Project Workflow

```
Raw Data
    │
    ▼
SQL Data Validation
    │
    ▼
SQL Data Cleaning & Transformation
    │
    ▼
Python Sentiment Analysis (VADER NLP)
    │
    ▼
Processed Data
    │
    ▼
Power BI Dashboard
    │
    ▼
Business Insights & Recommendations
```

---

## Tools & Technologies

- SQL Server
- SQL (CTEs, Window Functions, Data Cleaning)
- Python
- Pandas
- SQLAlchemy
- PyODBC
- NLTK
- VADER Sentiment Analyzer
- Power BI
- DAX

---

## Dataset

The project uses simulated retail data consisting of:

- Customer Journey
- Customer Reviews
- Marketing Engagement
- Products
- Customers
- Geography

---

## SQL Tasks

### Data Validation

- NULL value analysis
- Duplicate detection
- Data quality checks
- Rating validation
- Case sensitivity checks
- Invalid value detection

### Data Cleaning

- Removed logical duplicates
- Standardized text casing
- Cleaned review text
- Split combined columns
- Created cleaned tables
- Converted data types

---

## Python Analysis

Python was used for Natural Language Processing (NLP).

### Tasks Performed

- Connect SQL Server
- Load cleaned review data
- Sentiment Analysis using VADER
- Hybrid sentiment categorization
- Sentiment score calculation
- Negative review extraction
- Issue categorization
- Export processed CSV files

---

## Power BI Dashboard

The dashboard contains multiple report pages including:

### Executive Overview

- Conversion Rate
- Customer Ratings
- Positive Sentiment
- Product Health

### Customer Sentiment

- Sentiment Distribution
- Product Health Score
- Issue Categories
- Product Performance

### Conversion Analysis

- Customer Purchase Funnel
- Conversion Rate
- Drop-off Analysis

### Marketing Performance

- Views
- Clicks
- Likes
- Click Through Rate
- Campaign Performance

---

## Key Features

- End-to-End Analytics Project
- SQL Data Cleaning
- NLP Sentiment Analysis
- Interactive Power BI Dashboard
- Business KPI Analysis
- Conversion Funnel Analysis
- Marketing Performance Dashboard
- Product Health Analysis

---

## Project Structure

```
├── Data
│
├── SQL
│   ├── 01_Data_Validation.sql
│   └── 02_Cleaning_Transformation.sql
│
├── Python
│   └── sentiment_analysis.ipynb
│
├── Output
│   ├── customer_reviews_sentiment.csv
│   └── negative_reviews_issues.csv
│
├── Power BI
│   └── Retail_Analytics_Dashboard.pbix
│
└── README.md
```

---

## Skills Demonstrated

- Data Cleaning
- SQL Query Writing
- Common Table Expressions (CTEs)
- Window Functions
- Data Transformation
- NLP using Python
- Sentiment Analysis
- Data Visualization
- Dashboard Design
- Business Analysis
- DAX
- Storytelling with Data

---

## Business Insights

The analysis identifies:

- Customer conversion bottlenecks
- Product performance trends
- Customer satisfaction levels
- Marketing campaign effectiveness
- Common customer complaints
- Product improvement opportunities

---

## Future Improvements

- Customer Segmentation (RFM Analysis)
- Customer Lifetime Value (CLV)
- Sales Forecasting
- Cohort Analysis
- Predictive Machine Learning Models
- Advanced Power BI Features
- Automated Data Pipeline

---

## Dashboard Preview

> Add your dashboard screenshots here.

```
images/
│── overview.png
│── conversion.png
│── sentiment.png
│── marketing.png
```

---

## Author

**Asif Raza**

B.Tech – Electronics & Communication Engineering

Delhi Technological University (DTU)

Interested in Data Analytics, SQL, Python, and Power BI.

---

## License

This project is intended for educational and portfolio purposes.
