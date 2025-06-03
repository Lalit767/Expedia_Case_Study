# 📊 HCOM Analytics Insights Case Study

## 🎯 Objective
Quantify the drivers impacting the performance of **Net Room Nights** and surface key insights across marketing channels, platforms, and geographic regions. Deliver recommendations to improve business performance, targeted toward a senior executive audience.

---

## 📁 Dataset
The dataset provided in CSV format includes simulated booking data with the following key fields:

| Field                | Description                                                    |
|---------------------|----------------------------------------------------------------|
| `Date`              | Date of user activity (YYYY-MM-DD)                             |
| `Geographic Region` | Website region (e.g., EMEA, APAC, Americas)                    |
| `Platform`          | Device type (Desktop or Mobile)                                |
| `Marketing Channel` | Source of traffic (e.g., Google, TripAdvisor, Trivago)         |
| `Visits`            | Total visits to the site                                       |
| `Qualified Shoppers`| Visitors who viewed search results or property details         |
| `Net Orders`        | Orders excluding cancellations                                 |
| `Net Room Nights`   | Total room nights associated with net orders                   |

> 🔐 *Note: Data is simulated and does not reflect actual trading performance.*

---

## 🧠 Analytical Approach

### ✅ Data Preparation
- Cleaned and parsed date fields
- Handled missing or invalid entries (e.g., 2017-02-29)
- Engineered features: `Month`, `Day of Week`, `Quarter`

### ✅ Exploratory Analysis
- Breakdown by **Channel**, **Platform**, **Region**, and **Seasonality**
- Conversion Funnel:  
  `Visits → Qualified Shoppers → Net Orders → Room Nights`

### 📊 Efficiency Metrics
1. **Shopper Conversion Rate** = Qualified Shoppers / Visits  
2. **Booking Conversion Rate** = Net Orders / Qualified Shoppers  
3. **Traffic Efficiency** = Net Room Nights / Visits  
4. **Room Nights per Order** = Net Room Nights / Net Orders

### ✅ Predictive Modeling
- **Linear Regression**: To identify top positive and negative drivers of Net Room Nights and interpret coefficients directly for business insights  
- **Random Forest Regressor**: Used for non-linear relationships and variable importance analysis to validate and complement linear model insights

---

## 📈 Tools Used
- **Python**: pandas, matplotlib, seaborn, scikit-learn  
- **Jupyter Notebook**: Google Colab  
- **PowerPoint**: For executive-level presentation  

---

## 📝 Deliverables
- `HCOM_Case_Study_Presentation.pptx`: 15-slide executive summary  
- `README.md`: This file
