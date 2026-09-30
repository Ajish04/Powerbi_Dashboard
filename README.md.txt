# Banking Customer Transaction Analytics Dashboard

## 📌 Project Overview

The **Banking Customer Transaction Analytics Dashboard** is a Power BI project designed to analyze customer accounts, transactions, and balance information.

The dashboard helps users understand banking performance, customer behavior, transaction trends, account details, and financial patterns through interactive visualizations.

## 🎯 Objectives

- Analyze customer transaction activities.
- Monitor account and balance details.
- Identify transaction trends and patterns.
- Analyze customer segments and account types.
- Track successful, failed, and suspicious transactions.
- Provide interactive reports for better decision-making.

## 🛠️ Technologies Used

- **Power BI** – Dashboard development and data visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Calculations and measures
- **Microsoft Excel** – Data preparation and storage

## 📊 Dataset

The project contains three main tables:

### 1. Account Details

Contains information about customer accounts, including:

- Account ID
- Customer ID
- Account Number
- Account Type
- Account Status
- Opening Date
- Current Balance
- Available Balance
- Minimum Balance
- Interest Rate
- Branch ID
- IFSC Code
- Last Transaction Date

### 2. Transaction Details

Contains information about customer transactions, including:

- Transaction ID
- Customer ID
- Account ID
- Transaction Date
- Transaction Type
- Amount
- Balance After Transaction
- Channel
- Payment Method
- Merchant Category
- Transaction Status
- Fraud Flag
- Branch ID

### 3. Balance Details

Contains customer account balance information used to analyze balance changes and financial activity over time.

## 📈 Dashboard Features

- Total Customers
- Total Accounts
- Total Transactions
- Total Transaction Amount
- Current Balance
- Transaction Status Analysis
- Transaction Type Analysis
- Account Type Analysis
- Customer Segment Analysis
- Monthly Transaction Trends
- Branch-wise Analysis
- Payment Method Analysis
- Fraud Transaction Analysis
- Interactive filters and slicers

## 🔍 Key Insights

The dashboard can be used to identify:

- High-value customer transactions.
- Frequently used transaction types.
- Popular payment channels and methods.
- Account types with higher activity.
- Monthly transaction trends.
- Suspicious or flagged transactions.
- Customer and branch-level transaction patterns.

## ⚙️ Project Workflow

1. Collect banking customer and transaction data.
2. Import the data into Power BI.
3. Clean and transform the data using Power Query.
4. Create relationships between the tables.
5. Create calculated columns and measures using DAX.
6. Design interactive dashboards and visualizations.
7. Analyze customer and transaction trends.
8. Generate meaningful business insights.

## 📂 Project Structure

```text
Banking-Customer-Transaction-Analytics/
│
├── Dataset/
│   banking.xlsx
│
├── Dashboard/
│   └── Banking.pbix
          banking.pdf
│
└── README.md