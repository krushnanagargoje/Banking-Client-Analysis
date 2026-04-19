# Banking Client & Investment Analysis Dashboard

## 📌 Project Overview
This project provides a comprehensive analysis of banking client portfolios, demographics, and investment behaviors. Using Power BI, the dashboard transforms raw transactional data into actionable financial insights, helping relationship managers and investment advisors optimize their service delivery and risk management.

## 🛠️ Tech Stack
* **Power BI Desktop**: Data Modeling, DAX, and Visualization.
* **Power Query**: Data cleaning, ETL, and merging multiple datasets.
* **Excel/CSV**: Source data management.

## 📊 Key Metrics & Financial KPIs
The dashboard tracks several critical banking indicators:
* **Client Segmentation**: Analysis by **Loyalty Classification** (Jade, Platinum, Gold, Silver) and **Risk Weighting**.
* **Portfolio Value**: Monitoring **Bank Deposits**, **Superannuation Savings**, and **Estimated Income**.
* **Debt Analysis**: Tracking **Bank Loans** and **Credit Card Balances**.
* **Relationship Management**: Evaluating performance across different **Banking Relationships** (Private, Retail, Commercial, Institutional).

## 📁 Dataset Description
The analysis is built on five core relational datasets:
1.  `banking-clients.csv`: Master file containing client IDs, joined dates, occupation, and financial balances.
2.  `investment-advisiors.csv`: Mapping file for assigned financial advisors.
3.  `banking-realtionships.csv`: Categorization of banking service levels.
4.  `gender.csv`: Demographic mapping.
5.  `dashboard_final.pbix`: The complete Power BI report file.

## 💡 Key Insights
* **Wealth Distribution**: Identify which loyalty tiers contribute the most to the bank's total deposit pool.
* **Demographic Trends**: Understand the age and nationality distribution of high-net-worth individuals.
* **Risk vs. Loyalty**: Correlate risk weightings with client loyalty tiers to identify potential portfolio vulnerabilities.
* **Advisor Efficiency**: Compare the total assets under management (AUM) across different investment advisors.

## 🚀 How to Run the Project
1.  **Clone the Repository**: Download all `.csv` and the `.pbix` file.
2.  **Open Power BI**: Launch the `dashboard_final.pbix` file in Power BI Desktop.
3.  **Update Data Path**: If the visuals show an error, go to **Home > Transform Data > Data Source Settings** and update the file paths to point to the CSV files on your local machine.
4.  **Explore**: Use the slicers on the dashboard to filter by Gender, Loyalty Tier, or Advisor.

---
*Created as a demonstration of data-driven financial decision-making in the banking sector.*
