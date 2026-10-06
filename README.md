# Customer-Churn-Analysis

# 📉 Customer Churn Analysis

A data-driven **Customer Churn Analysis project** built using **PostgreSQL, Python, Pandas, and Jupyter Notebook** to understand customer retention, identify churn patterns, evaluate customer risk, and analyze the relationship between customer support activity and churn.

---

## 📖 Short Description / Purpose

**Customer Churn Analysis** is an exploratory data analysis project focused on understanding why customers leave a subscription-based service and identifying patterns associated with customer churn.

The analysis combines **customer information, subscription details, and support activity** into a unified analytical dataset.

The project focuses on:

- Customer retention and churn rates
- Subscription and contract patterns
- Monthly charges and customer value
- Customer tenure
- Churn risk based on existing churn scores
- Customer complaints and support escalations
- Regional churn patterns
- Relationship between support escalations and churn

The objective is to transform raw customer data into meaningful business insights that can support **customer retention and churn-reduction strategies**.

---

# 🛠️ Tech Stack

- 🐘 **PostgreSQL** – Database storage and structured customer data management.
- 🐍 **Python** – Data analysis and processing.
- 🐼 **Pandas** – Data cleaning, transformation, merging, and analysis.
- 🔢 **NumPy** – Numerical operations and feature creation.
- 📓 **Jupyter Notebook** – Interactive analysis and documentation.
- 📊 **Matplotlib** – Data visualization.
- 📈 **Seaborn** – Statistical and exploratory visualizations.
- 🔌 **SQLAlchemy** – PostgreSQL database connectivity with Pandas.
- 🔗 **Psycopg2** – PostgreSQL connection handling.

---

# 📂 Data Source

The analysis uses customer data stored in a **PostgreSQL database** named `customer_churn`.

The database contains three primary tables:

### 👤 `db_customer`

Contains customer demographic and geographic information.

Key fields include:

- Customer ID
- Customer Name
- Country
- State
- Gender
- Date of Birth
- Interests
- Pincode

### 📋 `db_subscription`

Contains customer subscription and financial information.

Key fields include:

- Customer ID
- Subscription Start Date
- Subscription Type
- Renewal Date
- Plan Type
- Contract Type
- Cancellation Date
- Cancellation Reason
- Monthly Charges
- CLTV
- Churn Score

### 🎧 `db_support`

Contains customer support and complaint information.

Key fields include:

- Customer ID
- Complaint Date
- Escalations
- CSAT Score
- Complaint Details

The three tables were loaded from PostgreSQL into Pandas for further analysis.

---

# ✨ Features / Highlights

## 📌 Business Problem

Customer churn directly affects recurring revenue and customer lifetime value.

When customer, subscription, and support information are stored separately, it becomes difficult to understand:

- Which customers are leaving
- Which subscription plans have higher churn
- Whether contract type is associated with churn
- Which customers have higher churn risk
- How customer tenure relates to retention
- Whether support escalations are associated with churn
- Which regions have higher churn rates

The project addresses these questions by integrating multiple customer-related datasets and performing exploratory churn analysis.

---

# 🎯 Goal of the Analysis

The primary goal of this project is to:

- Measure overall customer churn and retention.
- Understand churn across different subscription plans.
- Analyze customer tenure and monthly charges.
- Identify high-risk customers using churn scores.
- Analyze customer complaints and support escalations.
- Compare churn patterns across states.
- Examine relationships between customer support activity and churn.
- Create a consolidated dataset for further analysis.

---

# 🔄 Project Workflow

The analysis follows a structured data analytics workflow:

```text
PostgreSQL Database
        ↓
Data Extraction
        ↓
Data Exploration
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Data Integration
        ↓
Exploratory Data Analysis
        ↓
Churn & Risk Analysis
        ↓
Business Insights
        ↓
Exported Analytical Dataset
