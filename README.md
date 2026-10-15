# 📊 Customer Churn Analysis Dashboard

An interactive **Power BI dashboard** designed to analyze customer churn in the telecommunications industry. This project uses Excel-based customer data to explore customer demographics, telecom providers, usage behavior, and churn patterns to support data-driven business decisions.

## 📌 Project Overview

Customer churn occurs when customers stop using a company's services. Understanding churn helps telecom businesses identify customer behavior patterns, evaluate retention challenges, and make informed business decisions.

This project analyzes telecom customer data and presents key information through a Power BI dashboard.

## 🎯 Project Objectives

- Analyze customer churn and retention patterns.
- Explore customer demographics, including age and gender.
- Compare churn across telecom service providers.
- Examine customer activity through calls, SMS, and data usage.
- Explore customer distribution across states and cities.
- Present important business metrics using interactive visualizations.
- Support data-driven decision-making through business intelligence.

## 🛠️ Tools and Technologies

- **Microsoft Power BI** — Dashboard development and data visualization.
- **Microsoft Excel** — Dataset storage and data exploration.
- **Data Analytics** — Customer behavior analysis and KPI interpretation.
- **Business Intelligence** — Converting raw data into meaningful insights.

## 📂 Project Files

| File | Description |
|---|---|
| `Jio Churn Dashboard.pbix` | Power BI dashboard project file |
| `telecom_churn.xlsx` | Excel dataset containing telecom customer information |
| `README.md` | Project documentation |

## 📊 Dataset Description

The dataset contains **243,553 customer records** and 14 columns related to telecom customers.

### Dataset Columns

| Column | Description |
|---|---|
| `customer_id` | Unique customer identifier |
| `telecom_partner` | Telecom service provider |
| `gender` | Customer gender |
| `age` | Customer age |
| `state` | State associated with the customer record |
| `city` | City associated with the customer record |
| `pincode` | Postal code associated with the customer record |
| `date_of_registration` | Customer registration date |
| `num_dependents` | Number of dependents |
| `estimated_salary` | Estimated customer salary |
| `calls_made` | Number of calls made |
| `sms_sent` | Number of SMS messages sent |
| `data_used` | Recorded data usage |
| `churn` | Customer churn indicator: 1 = churned, 0 = not churned |

## 📈 Dashboard Features

The dashboard project focuses on telecom customer churn analysis and may include the following analytical areas, depending on the visuals implemented in the Power BI file:

- **Customer Overview:** Understand the customer base.
- **Churn Analysis:** Examine churned and retained customers.
- **Telecom Provider Analysis:** Compare customer churn across providers.
- **Demographic Analysis:** Explore age and gender distributions.
- **Geographical Analysis:** Analyze customer records across states and cities.
- **Usage Analysis:** Explore calls, SMS, and data usage patterns.
- **Interactive Reporting:** Explore the data using Power BI visual interactions and filters, where configured.

## 🔍 Analytical Approach

1. **Data Understanding:** Reviewed the dataset structure, fields, and customer attributes.
2. **Data Preparation:** Examined data types, missing values, and potential data-quality issues.
3. **Data Analysis:** Explored customer characteristics, telecom providers, usage behavior, and churn indicators.
4. **Dashboard Development:** Used Power BI to build an interactive business intelligence report.
5. **Insight Generation:** Used visual comparisons to identify patterns that may support customer retention decisions.

## 💡 Business Applications

This type of analysis can help telecom businesses:

- Understand customer churn patterns.
- Identify customer groups that may require further investigation.
- Compare churn rates across service providers.
- Explore relationships between usage behavior and churn.
- Develop and evaluate customer retention strategies.
- Monitor customer-related KPIs through business intelligence dashboards.

These are potential business applications of the analysis, not claims that specific retention improvements have already been achieved.

## 🚀 How to Use This Project

1. Clone or download this GitHub repository.
2. Download and install Microsoft Power BI Desktop.
3. Open `Jio Churn Dashboard.pbix` in Power BI Desktop.
4. If prompted, update the Excel data source path to the location of `telecom_churn.xlsx`.
5. Refresh the data if required.
6. Explore the report visuals, filters, and interactions available in the dashboard.

## 📁 Repository Structure

```text
telecom-customer-churn-analysis/
│
├── Jio Churn Dashboard.pbix
├── telecom_churn.xlsx
└── README.md
```

## 🔮 Future Improvements

- Add more customer retention KPIs.
- Perform deeper analysis of churn by customer segment.
- Investigate relationships between customer usage and churn.
- Add time-based churn trend analysis where the data supports it.
- Integrate SQL for data extraction and transformation.
- Develop a churn prediction model using machine learning.
- Publish an online dashboard or create a dashboard preview for the repository.

## ⚠️ Data Quality and Limitations

The dataset should be checked for unusual values, inconsistent geographic fields, and business-rule violations before drawing final conclusions. For example, the recorded `data_used` field contains negative values that require investigation.

The dataset's source, licensing terms, and permission for public redistribution should be verified before publishing the Excel file.

## 👨‍💻 Author - Atharv Khumkar

**Data Analytics Portfolio Project**

Skills demonstrated: Power BI, Excel, data analysis, data visualization, and business intelligence.

## ⭐ Support

If you find this project useful, consider starring the repository and sharing feedback or suggestions for improvement.
