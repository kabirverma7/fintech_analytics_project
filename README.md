📊 Fintech Transaction Analytics – Data Cleaning & KPI Analysis
This project focuses on cleaning, transforming, and analyzing a fintech transaction dataset as part of a self-driven data internship. The goal was to prepare the data for business insights and dashboarding by handling inconsistencies, engineering features, and calculating key performance metrics.

🔍 Project Objectives
⦁	Clean raw transaction data: handle missing values, outliers, and invalid timestamps.
⦁	Engineer meaningful features to support analysis:
⦁	'txn_hour' (hour of transaction)
⦁	'is_weekend' (boolean based on transaction day)
⦁	'weekday_type' (Weekend/Weekday label)
⦁	Compute important business KPIs:
⦁	Overall success and failure rates
⦁	Channel-wise and merchant-wise success rates
⦁	Save a fully cleaned and enriched dataset for future use in dashboarding tools like Power BI.

📁 Files Included
⦁	'cleaned_transactions.csv' – Final cleaned and feature-rich dataset.
⦁	'fintech-analytics.ipynb' – Python script for preprocessing, feature engineering, and KPI generation.
⦁	'README.md' – Project summary and documentation.
⦁	'fintech.pbix' – Power BI dashboard file.
⦁	'dashboard_preview.png' – Preview of dashboard visuals.

🧰 Tools & Technologies
⦁	Python
⦁	Pandas
⦁	Jupyter Notebook / PyCharm
⦁	CSV file handling
⦁	Power BI (for dashboarding)

📈 Key Outcomes
⦁	Cleaned and transformed over 1,000 transaction records.
⦁	Created time-based features to enable behavioral analysis.
⦁	Calculated success/failure rates by channel and merchant.
⦁	Developed a Power BI dashboard for visual exploration and reporting.

📊 Dashboard
The final Power BI dashboard is included in this repo as:
⦁	'fintech.pbix' – Editable Power BI file
⦁	'dashboard_preview.png' – Dashboard screenshot
Dashboard Highlights
⦁	Transaction status breakdown (Success vs Failure)
⦁	Transaction volume by channel and hour
⦁	Total transaction value by merchant
⦁	Interactive filters for channel and status

Getting Started
1.	Clone this repository  
'''bash
git clone https://github.com/yourusername/fintech-analytics-project.git
'''
2.	Open 'fintech-analytics.ipynb' to explore the cleaning process.
3.	Open 'fintech.pbix' in Power BI Desktop to view or extend the dashboard.

📌 Future Improvements
⦁	Add anomaly detection metrics like velocity and transaction clustering
⦁	Integrate with Streamlit for web-based insights
⦁	Link customer and merchant profiles for enriched analysis

👤 Author
Kabir Verma
Data Analytics Intern | Python & Data Enthusiast  
LinkedIn • GitHub
