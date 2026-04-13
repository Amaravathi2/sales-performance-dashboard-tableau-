#  Regional Sales Analysis Dashboard — Tableau

A **Data Visualization** course-end project built using **Tableau**, designed to compare sales performance across two selected regions and help upper management make informed strategic decisions.

---

##  Project Overview

Sales performance analysis is essential for strategic planning in any organisation. This project involves building an interactive Tableau dashboard that visualises and compares sales data from two user-selected regions — highlighting regional trends, identifying areas for improvement, and supporting management in implementing effective sales strategies.

---

##  Repository Contents

```
├── sales_performance_dashboard.twbx               # Packaged Tableau workbook (dashboard + data)
├── regional_sales_analysis_problem_statement.pdf  # Original project brief
└── README.md
```

---

##  Project Objectives

- Compare **total sales** between a Primary and a Secondary region
- Analyse **average sales per order** and **total order counts** per region
- Identify the number of **unique customers** in each region
- Track the number of **distinct products sold** per region
- Present all findings in a single, interactive Tableau dashboard with dynamic region selection

---

## 🛠️ Dashboard Components

### 1. Sales Performance Parameters
- **Primary Region** parameter — allows the user to select the first region from all available regions
- **Secondary Region** parameter — allows the user to select the second region for comparison
- Calculated fields filter data dynamically based on the selected parameters
- Separate worksheets display **Total Sales** for the Primary and Secondary regions

### 2. Average Sales & Order Statistics
- Worksheet showing **Average Sales per Order** for both regions
- Displays the **Total Number of Orders** for each region
- Filters applied to each worksheet to show only the selected region's data

### 3. Customer & Product Analysis
- Worksheet displaying the count of **Unique Customers** per region
- Worksheet showing the number of **Distinct Products Sold** per region
- Filters applied to ensure data accuracy across both regions

### 4. Comparative Dashboard
- All individual worksheets combined into a **single unified dashboard**
- **Containers** used to partition the layout into clear Primary and Secondary region sections
- **Parameter controls** added so users can switch regions and instantly refresh all visualisations

---

##  Key Metrics Tracked

| Metric | Description |
|---|---|
| Total Sales | Combined revenue for the selected region |
| Average Sales per Order | Mean order value within the region |
| Total Orders | Count of all orders placed in the region |
| Unique Customers | Count of distinct customers per region |
| Distinct Products Sold | Count of unique products sold per region |

---

##  How to Open the Dashboard

1. Download and install [Tableau Public](https://public.tableau.com/en-us/s/download) (free) or Tableau Desktop
2. Clone or download this repository
3. Open `sales_performance_dashboard.twbx` in Tableau
4. On the dashboard, use the **Primary Region** and **Secondary Region** parameter controls to select any two regions
5. All worksheets and KPIs will update dynamically based on your selection

---

##  Submission Requirements

As per the course guidelines, the submission includes:
- A **Word document** with screenshots illustrating each step performed
- Actionable insights drawn from the regional sales performance analysis
- Uploaded to the **Learning Management System (LMS)**

---

##  Tools & Technologies

| Tool | Purpose |
|---|---|
| **Tableau** | Dashboard creation and data visualisation |
| **Parameters** | Dynamic Primary and Secondary region selection |
| **Calculated Fields** | Custom logic for region-based data filtering |
| **Dashboard Containers** | Structured layout separating the two regions |
| **Filters** | Ensuring worksheet-level data accuracy |

---

##  Skills Demonstrated

- Data visualisation and storytelling
- Dashboard design with interactive controls
- Regional sales performance analysis
- Comparative analysis using parameters and calculated fields
- KPI reporting for business decision-making

---

##  Course Context

> **Course:** Data Visualization Using Tableau Certification Training
> **Project Type:** Course-End Project
> **Deliverable:** Packaged Tableau Workbook (`.twbx`) + Word document with screenshots

---

##  License

This project was created for educational purposes as part of a Tableau Certification Training programme.
