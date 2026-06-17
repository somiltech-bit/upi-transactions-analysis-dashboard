# UPI Transactions Analysis Dashboard

## Overview
This project analyzes 20,000 UPI transaction records using SQL Server, Power Query Editor, and Power BI.  
The goal was to clean the data, profile it, and build an interactive dashboard for transaction monitoring and business insights.

## Objectives
- Clean and prepare raw UPI transaction data
- Perform data profiling and transformation
- Build an interactive Power BI dashboard
- Analyze trends by month, city, currency, bank, device type, gender, merchant, and payment method

## Dataset
- Rows: 20,000
- Columns: TransactionID, TransactionDate, Amount, BankNameSent, BankNameReceived, RemainingBalance, City, Gender, TransactionType, Status, TransactionTime, DeviceType, PaymentMethod, MerchantName, Purpose, etc.

## Tools Used
- Microsoft SQL Server
- Power Query Editor
- Power BI
- Excel

## Data Cleaning & Profiling
- Checked for missing values
- Standardized column types
- Formatted dates and times
- Validated categorical values
- Profiled columns for consistency and quality
- Prepared the dataset for reporting in Power BI

## Dashboard Pages
### Page 1
Interactive KPI-style dashboard with:
- Monthly transaction trend
- Monthly balance trend
- Toggle-based charts for amount and balance
- Filters for bank, city, device type, gender, merchant, purpose, payment method, and transaction type

### Page 2
Detailed matrix/table view showing:
- City
- Currency
- Month-wise transaction amount
- Remaining balance

## Key Insights
- Monthly transaction volume remained fairly stable across the year
- Transaction amount showed visible month-to-month variation
- Balance trends helped compare transaction behavior across cities and currencies
- The dashboard supports fast filtering and comparison across user segments

## Repository Structure

```text
UPI-Transactions-Analysis/
├── README.md
├── data/
│   └── upi_transactions.csv
├── powerbi/
│   └── UPI_Transactions_Dashboard.pbix
├── docs/
│   ├── data_dictionary.md
│   ├── cleaning_steps.md
│   └── insights_summary.md
└── screenshots/
    ├── dashboard_page_1.png
    ├── dashboard_page_2.png
```

## Screenshots
Inside the screenshots folder. 

## Future Improvements
- Add DAX measures for advanced KPIs
- Build drill-through pages
- Add anomaly detection for failed transactions
- Add city-wise and bank-wise ranking visuals
