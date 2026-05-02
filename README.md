# Credit-Card-Final-Analysis-Report
# Credit Card Analysis Dashboard

## Project Overview

This project focuses on analyzing customer behavior and credit card usage patterns using Power BI. The goal is to extract meaningful insights related to spending habits, customer segmentation, and potential churn indicators.

## Tools & Technologies

* Power BI
* CSV Data Files
* Data Cleaning & Transformation

## Datasets Used

### 1. customer_details.csv

Contains customer-related information such as:

* Customer ID
* Age
* Gender
* Income
* Location

### 2. credit_card_details.csv

Contains transaction and card usage data:

* Transaction ID
* Customer ID
* Transaction Amount
* Transaction Date
* Credit Limit
* Payment Status

## Data Processing Workflow

Raw Data → Data Cleaning → Data Transformation → Data Modeling → Visualization

### Key Steps:

* Removed missing and duplicate values
* Converted categorical data into usable formats
* Created new features such as:

  * Total spending per customer
  * Average transaction value
  * Credit utilization ratio

## Dashboard Insights
## Dashboard Preview

### Overall Dashboard
![Overview](dashboard/dashboard-overview.jpg.jpg)

### Customer Analysis
![Customer](dashboard/customer-segmentation.jpg.jpg)

### Forecast Insights
![Forecast](dashboard/forecast-analysis.jpg.jpg)

### Risk Indicators

* Customers with high credit utilization show higher default probability
* Delayed payments are more common in low-income segments

## Key Metrics (KPIs)

* Total Revenue
* Total Transactions
* Average Transaction Value
* Customer Segmentation
* Credit Utilization

## Project Structure

```
credit-card-analysis/
│
├── data/
│   ├── customer_details.csv
│   └── credit_card_details.csv
│
├── reports/
│   └── credit-card-final-report.pbix
│
├── images/
│   ├── dashboard_overview.png
│   └── insights.png
│
├── README.md
```

## How to Use

1. Download the `.pbix` file
2. Open using Power BI Desktop
3. Explore dashboards and filters

## Business Value

* Helps financial institutions understand customer spending behavior
* Identifies high-risk customers
* Supports data-driven decision making

## Future Improvements

* Add machine learning model for churn prediction
* Integrate real-time data
* Deploy as a web dashboard

## Author

 P. Chandra Chaitanya Kumar
