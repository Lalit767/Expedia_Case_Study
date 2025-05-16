# Expedia_Case_Study
📊 HCOM Analytics Insights Case Study
🔍 Objective
Quantify the drivers impacting the performance of Net Room Nights and surface key insights across marketing channels, platforms, and geographic regions. Deliver recommendations to improve business performance, targeted toward a senior executive audience.

📁 Dataset
The dataset provided in CSV format includes simulated booking data with the following key fields:

Field	Description
Date	Date of user activity (YYYY-MM-DD)
Geographic Region	Website region (e.g., EMEA, APAC, Americas)
Platform	Device type (Desktop or Mobile)
Marketing Channel	Source of traffic (e.g., Google, TripAdvisor, Trivago)
Visits	Total visits to the site
Qualified Shoppers	Visitors who viewed search results or property details
Net Orders	Orders excluding cancellations
Net Room Nights	Total room nights associated with net orders

🔐 Note: Data is simulated and does not reflect actual trading performance.

🧠 Analytical Approach
✅ Data Preparation
Cleaned and parsed date fields

Handled missing or invalid entries (e.g., 2017-02-29)

Engineered features: Month, Day of Week, Quarter

✅ Exploratory Analysis
Channel, Platform, Region, and Seasonal breakdowns

Conversion Funnel: Visits → Qualified Shoppers → Net Orders → Room Nights

Efficiency Metrics:

Shopper Conversion Rate

Booking Conversion Rate

Traffic Efficiency (Nights/Visit)

Room Nights per Order

✅ Advanced Analysis
Multivariate Regression to model Net Room Nights

Identified key drivers across categorical and numeric dimensions

📈 Tools Used
Python (Pandas, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

PowerPoint (for executive presentation)

📝 Deliverables
HCOM_Case_Study_Presentation.pptx: 15-slide executive summary

HCOM_Analytics_Insights_Case_Study_Dataset.csv: original input dataset

model_analysis.ipynb: code notebook for data prep, EDA, and regression modeling

README.md: this file

