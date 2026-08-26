# Credit Card Financial Analytics

An end-to-end data analytics project focused on credit card transactions, customer behavior, revenue performance, and financial insights.

This project was built using SQL and Power BI. The main purpose was to take raw credit card data, analyze it, prepare it for reporting, and convert the results into interactive dashboards that can be used to understand business performance.

---

## Dashboard Preview

### Credit Card Transaction Report

<!-- Add your first dashboard image here -->

![Credit Card Transaction Report](Images/credit-card-transaction-report.png)

### Credit Card Customer Report

<!-- Add your second dashboard image here -->

![Credit Card Customer Report](Images/credit-card-customer-report.png)

---

## LinkedIn Post

I have also shared my project journey and learning experience on LinkedIn.

[View LinkedIn Post](YOUR_LINKEDIN_POST_URL)

---

## About the Project

Credit card businesses generate a large amount of transaction and customer data. The main challenge is to convert this raw data into information that can help understand revenue, transactions, customer behavior, and overall financial performance.

In this project, I worked on the complete data analytics process, starting with SQL and ending with interactive Power BI reports.

The project contains two reports:

1. Credit Card Transaction Report
2. Credit Card Customer Report

Both reports use the same project data but focus on different aspects of the business.

---

## Business Questions

Before building the reports, I focused on questions that could provide useful business insights:

* What is the overall revenue?
* What is the total transaction amount and transaction count?
* How much interest is generated?
* Which card types are performing better?
* Which customer segments contribute more revenue?
* Which states have the highest contribution?
* How does revenue change over time?
* How do customer income, age, education, and job affect revenue?
* What are the important financial KPIs that should be monitored?

---

## Tools Used

* SQL
* PostgreSQL
* Power BI
* DAX
* Power Query
* Data Modeling

---

## Project Workflow

I followed a complete data analytics workflow throughout the project:

**Raw Data → SQL Analysis → Data Cleaning → Data Transformation → Data Modeling → DAX → Dashboard Development → Business Insights**

### 1. Data Loading and SQL Analysis

I first loaded the credit card data into PostgreSQL.

After loading the data, I used SQL to explore the dataset and understand its structure, columns, customer information, transaction information, and important financial fields.

I also used SQL queries to perform initial analysis and identify useful patterns in the data.

### 2. Data Cleaning and Transformation

After the initial analysis, I prepared the data for Power BI.

This included checking data types, handling data quality issues, preparing fields for analysis, and transforming the data into a suitable format for reporting.

### 3. Data Modeling

After connecting the data to Power BI, I created the required data model and relationships.

The model was designed to make it easier to analyze transactions, customers, revenue, card types, demographics, and time-based performance.

### 4. DAX

I used DAX to create the measures and calculations required for the reports.

Some of the important metrics included:

* Total Revenue
* Total Transaction Amount
* Transaction Count
* Total Interest
* Customer Income
* Customer Satisfaction Score
* Revenue by Card Type
* Revenue by Customer Segment
* Revenue by State
* Revenue Trends

### 5. Dashboard Development

After completing the data preparation and calculations, I created two Power BI reports.

---

# Report 1: Credit Card Transaction Report

The first report focuses mainly on transaction and financial performance.

The report includes analysis of:

* Total Revenue
* Total Transaction Amount
* Transaction Interest
* Transaction Count
* Revenue by Card Type
* Revenue by Expenditure Type
* Revenue by Customer Job
* Revenue by Education Level
* Quarterly Performance
* Transaction Trends

The main purpose of this report is to understand how credit card transactions are performing and where the revenue is coming from.

---

# Report 2: Credit Card Customer Report

The second report focuses on customer-level analysis.

It includes:

* Customer Revenue
* Customer Income
* Transaction Interest
* Customer Satisfaction Score
* Revenue by Income Group
* Revenue by Age Group
* Revenue by Education
* Revenue by Customer Job
* Top States
* Customer Segmentation

This report helps understand customer behavior and how different customer groups contribute to the overall financial performance.

---

# Key Insights

After analyzing the data, I identified several important insights from the project.

### Overall Financial Performance

* Overall Revenue: 57M
* Total Interest: 8M
* Total Transaction Amount: 46M

These KPIs provide a high-level view of the financial performance of the credit card business.

### Revenue by Gender

Male customers contributed approximately 31M in revenue, while female customers contributed approximately 26M.

This shows that both customer groups make a significant contribution to overall revenue, with male customers having a higher contribution in the analyzed data.

### Card Type Performance

Blue and Silver credit cards contributed approximately 93% of overall transactions.

This indicates that these two card categories account for the majority of transaction activity in the dataset.

### Geographic Contribution

Texas, New York, and California together contributed approximately 68% of the overall contribution.

This shows that a large portion of the business activity is concentrated in these three states.

### Revenue Growth

Revenue increased by approximately 28.8% compared with the previous period analyzed in the project.

This indicates positive revenue growth during the period covered by the analysis.

### Activation Rate

The overall activation rate was 57.5%.

This indicates that there is an opportunity to improve card activation and customer engagement.

### Delinquent Rate

The overall delinquent rate was 6.06%.

This KPI is important from a financial risk perspective and should be monitored regularly.

---

# Business Recommendations

Based on the analysis, some possible business actions could be:

### Improve Card Activation

With an activation rate of 57.5%, targeted onboarding campaigns and activation reminders could help improve customer engagement.

### Focus on High-Contribution States

Texas, New York, and California represent a major share of the business contribution. These markets could be considered for targeted campaigns and customer retention strategies.

### Monitor Delinquency

The delinquent rate of 6.06% should be monitored regularly to identify customer segments with higher financial risk.

### Analyze High-Performing Card Types

Since Blue and Silver cards account for approximately 93% of transactions, further analysis can help understand what is driving their high usage.

### Customer Segmentation

Customer attributes such as income, age, job, education, and spending behavior can be used to create more targeted customer segments.

---

# Dynamic Reporting

One of the important aspects of this project is its dynamic reporting approach.

The Power BI reports are connected to the underlying data source. When new data is added and the configured refresh process runs, the reports can be updated with the latest information.

This makes the reports useful for ongoing analysis rather than being limited to a one-time static dashboard.

The actual refresh behavior depends on the data source and Power BI refresh configuration.

---

# Why Two Reports?

I created two separate reports because transaction performance and customer behavior answer different business questions.

The Transaction Report focuses on:

**What is happening with transactions and financial performance?**

The Customer Report focuses on:

**Who are the customers and how are they contributing to the business?**

Keeping these two perspectives separate makes the analysis easier to understand and explore.

---

# What I Learned

This project helped me understand that data analytics is not only about writing SQL queries or creating Power BI dashboards.

The complete process starts with understanding the business problem and ends with finding insights that can support better decisions.

My overall approach was:

**Understand → Explore → Clean → Analyze → Model → Calculate → Visualize → Interpret → Recommend**

Through this project, I improved my practical understanding of SQL, data cleaning, data transformation, data modeling, DAX, Power BI visualization, KPI development, and business-oriented analysis.

The most important learning for me was understanding how SQL and Power BI can work together as part of a complete data analytics workflow.

---

# Project Structure

```text
Credit-Card-Financial-Analytics/
│
├── README.md
│
├── Dataset/
│   └── credit_card_data.csv
│
├── SQL/
│   └── credit_card_analysis.sql
│
├── PowerBI/
│   └── Credit_Card_Financial_Analytics.pbix
│
└── Images/
    ├── credit-card-transaction-report.png
    └── credit-card-customer-report.png
```

---

# Project Details

**Project Name:** Credit Card Financial Analytics

**Domain:** Finance

**Project Type:** End-to-End Data Analytics Project

**Database:** PostgreSQL

**Visualization Tool:** Power BI

**Query Language:** SQL

**Calculation Language:** DAX

**Reports:** Credit Card Transaction Report and Credit Card Customer Report

---

# LinkedIn

I have shared the project journey and learning process on LinkedIn.

[View LinkedIn Project Post](YOUR_LINKEDIN_POST_URL)

---

# Feedback

If you have any suggestions or feedback about this project, feel free to connect with me on LinkedIn.

Thank you for taking the time to explore this project.
