# Asset-Analysis-Dashboard-Power-BI

# Asset Analysis Dashboard – Power BI



## 📌 Project Overview

This project focuses on analyzing **IT / operational assets and service requests** to help operations and asset management teams monitor asset utilization, request efficiency, and resolution performance.

The primary objectives of this dashboard are to:

* Track total assets and request volumes
* Monitor request resolution efficiency and SLA adherence
* Analyze asset distribution by age and type
* Identify regional performance bottlenecks
* Understand request trends over time

The dashboard provides a **centralized operational view** to support data-driven decisions related to asset lifecycle management and service optimization.

---

## 🗂 Data Model

A **star schema** data model was implemented consisting of:

* **Fact Table** – Asset Requests (request date, status, resolution time, priority)
* **Dimension Tables** – Assets, Asset Types, Regions, Date

Relationships are built using AssetID, AssetTypeID, RegionID, and Date keys to enable efficient filtering and slicing.

---
![Asset Analysis Dashboard](Screenshots/dashboard.png)
## 🎯 Key Features & Insights

### 🔹 Dynamic Slicers

* Asset Type
* Priority (High / Medium / Low)
* Date Range

All visuals dynamically respond to slicer selections for flexible analysis.

---

### 🔹 KPI Cards

The dashboard highlights key operational KPIs:

* **Total Assets**
* **Active Assets per Request**
* **Total Requests**
* **Average Resolution Time (Days)**
* **% Requests Resolved On Time**
* **Total Completed Requests**
* **% Assets Within Refresh Cycle**

These KPIs provide a quick snapshot of asset health and service efficiency.

---

### 🔹 Assets Distribution by Age

A column chart showing asset count by **asset age (in years)** to:

* Identify aging assets
* Support refresh and replacement planning

---

### 🔹 Requests & Avg Resolution Time by Region

A combined line and column visual displaying:

* Total requests per region
* Average resolution time per region

This helps identify:

* High-demand regions
* Regions with delayed resolution times

---

### 🔹 Completed Requests by Asset Type

A tabular visual summarizing:

* Asset type
* Total assets
* % contribution
* Total fulfilled requests

---

### 🔹 Requests Status Over Time

An area chart showing monthly trends of:

* Total requests
* Closed requests
* Pending requests

This enables tracking operational load and backlog trends over time.

---

## 🧰 Techniques & Power BI Skills Used

* Data Modeling & Star Schema Design
* KPI Development
* Time-Series Trend Analysis
* Dynamic Slicers & Filters
* Combined Line & Column Charts
* Dynamic Tooltip Pages using Dedicated Tooltip Tables
* Operational Performance Analysis
* Interactive & User-Friendly Dashboard Design

---

## 📊 KPIs Built

* Total Assets
* Total Requests
* Completed Requests
* Average Resolution Time
* SLA Compliance %
* Asset Refresh Compliance %
* Requests by Region & Asset Type

---

## 💻 Repository Structure

```
📁 Asset-Analysis-Dashboard
 ├── 📂 Data
 ├── 📂 Screenshots
 ├── 📂 Documentation
 ├── README.md
 └── Asset-Analysis.pbix
```

---

## 🙌 Kavya

**Kavya Sakhamuri**  
Data Analyst | Power BI | SQL | DAX

