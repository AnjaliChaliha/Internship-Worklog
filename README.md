# 📊  Power BI Analytics Dashboards

##  Project Overview
This repository showcases a suite of **interactive Power BI dashboards** developed during my internship at **Welspun Group**. The dashboards are designed for **enterprise-level user activity monitoring**, **license utilization analysis**, and **departmental engagement insights** across multiple business units.

The data was sourced from internal user activity logs and system usage reports, and was transformed using **Power Query** and modeled with **DAX (Data Analysis Expressions)**.

![Dashboard 1](https://github.com/AnjaliChaliha/Internship-Worklog/blob/2855a73e1796649c976371dd8b4c08423a767d55/Dashboard%201.png)
![Dashboard 2](https://github.com/AnjaliChaliha/Internship-Worklog/blob/2855a73e1796649c976371dd8b4c08423a767d55/Dashboard%202.png)
![Dashboard 3](https://github.com/AnjaliChaliha/Internship-Worklog/blob/2855a73e1796649c976371dd8b4c08423a767d55/Dashboard%203.png)

---

##  Dashboards Summary

###  1. User Engagement & License Analytics

#### Description:
This dashboard provides a **macro-level overview** of user activity and licensing statistics across business units and departments.

#### Key Features:
- **New Users by Month**: Bar chart visualizing user onboarding trends over time.
- **Average Activities by Department**: Departmental breakdown of usage volume using clustered bar visuals.
- **Active vs. Inactive Users**: Segmentation by status and company (WELSPUN India, Global, UK, USA).
- **User Activity Metrics (KPI Tiles)**:
  - `New Users MTD`
  - `New Users LMTD`
  - `Total Active Users`
  - `Inactive Users`
  - `Licensed Users`

#### Technical Highlights:
- **Slicer filters** for Company, Department, and Date Range.
- Use of **DAX measures** to calculate MTD/LMTD user counts.
- Visuals built using **stacked bar charts**, **table visuals**, and **KPI indicators**.

---

###  2. Individual User Activity Tracker

#### Description:
This dashboard provides a **micro-level deep dive** into individual user behavior within the enterprise applications.

#### Key Features:
- **Total Activities & Events**: Quantitative metrics representing user interaction frequency.
- **User Profile Metadata**: Department, role, office location, and license status.
- **User Event Trend (Time Series)**: Line chart tracking activity timeline (CreationDate).
- **Weekly Event Distribution**: Column chart for day-wise activity.
- **Activity Type Ratio**: Pie chart visualizing the distribution of activity types:
  - `ViewReport`, `ExportReport`, `InstallApp`, `CreateReport`, `RefreshDataset`, etc.

#### Technical Highlights:
- Use of **time intelligence DAX functions** to generate weekly trends.
- Integration of **user metadata** with activity metrics.
- **Hierarchical filters** for year selection and user name.

---

###  3. Organization-Wide Activity Trend Dashboard

#### Description:
A dashboard built for **weekly monitoring of user interaction trends** across departments and business functions.

#### Key Features:
- **Weekly Activity Trends**: Daily distribution of total events and last week's activity.
- **Event Timeline**: Peak usage detection using time-series event charts.
- **Activity Ratio Breakdown**: Action-based segmentation of user events.
- **Active vs. Inactive Users**: Gauge indicators showing real-time engagement levels.

#### Technical Highlights:
- Advanced DAX logic for calculating week-over-week activity changes.
- Use of **card visuals**, **donut charts**, and **stacked column charts** for comparative analysis.
- **Cross-filtering capabilities** across departments, years, and week numbers.

---

##  Tools & Technologies

| Tool/Platform     | Purpose                               |
|-------------------|----------------------------------------|
| **Power BI Desktop** | Data modeling and dashboard design |
| **Power Query (M)** | Data transformation and ETL logic   |
| **DAX**             | Calculated columns, measures, KPIs  |
| **Excel / SharePoint** | Data sources                      |

---

##  Impact & Outcome
- Enabled real-time tracking of user engagement across departments and subsidiaries.
- Identified inactive licenses, supporting cost optimization for Power BI licenses.
- Facilitated performance reviews with **usage-based user activity audits**.
- Helped IT and Digital Strategy teams prioritize resource allocation based on usage patterns.

---

##  Notes
- All datasets used were internal to Welspun Group.
- Sensitive data has been anonymized or redacted in visuals.

---

##  Future Enhancements
- Integration with Power BI Service APIs for real-time monitoring.
- Automated user notifications for inactivity or license expiration.
- Role-based access dashboards for department heads.

