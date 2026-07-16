# Schneider Electric Business Analytics & Digital Transformation

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-Analytics-4479A1?logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Data%20Model-217346?logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Project Overview

This project presents a **data-driven digital transformation strategy** for Schneider Electric's Regional Administration teams. The solution leverages **Business Analytics, Power BI dashboards, KPI design, workflow standardisation, and change management** to improve operational efficiency and enable proactive decision-making.

Using a synthetic enterprise dataset, this project demonstrates how analytics can reduce manual effort, improve data quality, minimise revenue leakage, and support business stakeholders through interactive dashboards and actionable insights.

---

## Disclaimer

This repository is an independent portfolio project based on a Schneider Electric business scenario.

- All datasets included are **synthetically generated** for educational and portfolio purposes.
- No confidential, proprietary, or customer data from Schneider Electric has been used or disclosed.
- Schneider Electric is referenced solely as the business case scenario.

---

# Business Problem

Regional Administration teams rely on multiple enterprise platforms including SAP, Oracle, and Salesforce. Although these systems support day-to-day operations, fragmented workflows and manual processes result in:

- High SLA breach rates
- Revenue leakage
- Invoice corrections
- Manual administrative effort
- Poor operational visibility
- Workflow bottlenecks
- Data quality issues
- Delayed decision-making

This project proposes an analytics-driven transformation strategy to address these challenges.

---

# Project Objectives

- Standardise administrative workflows
- Improve operational visibility
- Reduce billing delays
- Improve invoice readiness
- Reduce manual processing
- Increase forecast accuracy
- Improve SLA performance
- Support proactive business decisions through analytics

---

# Dataset

The project uses a **synthetic enterprise dataset** designed to simulate Schneider Electric's Regional Administration environment over a 12-month operational period.

### Workbook

```
Schneider_Synthetic_Dataset.xlsx
```

### Worksheets

| Worksheet | Description |
|-----------|-------------|
| Projects | Project master data |
| Requests | Service requests and SLA tracking |
| Billing | Invoice and billing information |
| Forecasts | Revenue forecast data |
| Purchases | Purchase orders and goods receipt information |
| DeBookings | Project de-booking records |
| AdminOps | Administrative operations and task logs |

The workbook contains interconnected tables linked through common business identifiers, enabling end-to-end operational analysis.

---

# Tools & Technologies

- Power BI
- SQL
- Microsoft Excel
- Power Query
- Jira (Workflow Design)
- SharePoint (Knowledge Management)

---

# Dashboard Overview

The solution includes three persona-driven interactive Power BI dashboards.

## 1. Project Manager Dashboard

Provides visibility into:

- Invoice Readiness
- Project Health
- GR Ageing
- Rework Root Causes
- 30-Day Action Plan

---

## 2. Finance Controller Dashboard

Provides insights into:

- Forecast Accuracy (MAPE)
- Revenue Leakage
- Billing Performance
- Invoice Corrections
- DSO Monitoring

---

## 3. Regional Administration Dashboard

Supports operational monitoring through:

- SLA Performance
- Request Intake Analysis
- Automation Coverage
- Touch Time vs Wait Time
- First-Time-Right Rate

---

# Key Insights

Analysis of the synthetic dataset identified several operational challenges:

- 70.3% of service requests breached SLA targets
- Peak monthly revenue leakage reached **$1.23M**
- 22.1% of invoices required corrections
- 50.6% purchase order mismatch rate
- Email accounted for over 65% of request intake
- Automation coverage remained below target

These findings highlight opportunities to improve workflow standardisation, automation, and data quality.

---

# Proposed Solution

The recommended transformation strategy includes:

- Standardised Jira workflows
- Power BI executive dashboards
- SharePoint knowledge repository
- REST API integration
- Predictive SLA monitoring
- Invoice readiness scoring
- Workflow automation
- Standardised governance framework

---

# Expected Business Impact

| KPI | Target |
|------|--------|
| Rework Rate | ↓ 50% |
| Invoice Corrections | ↓ 40% |
| SLA Attainment | ≥ 90% |
| Forecast Accuracy | 8–10% MAPE |
| Automation Coverage | ≥ 30% |
| Customer Satisfaction | ≥ 4.4 / 5 |

---

# Repository Structure

```
schneider-electric-business-analytics/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── data/
│   └── Schneider_Synthetic_Dataset.xlsx
│
├── dashboards/
│   ├── Schneider_Dashboard.pbix
│   └── screenshots/
│       ├── project_manager_dashboard.png
│       ├── finance_controller_dashboard.png
│       └── regional_admin_dashboard.png
│
├── reports/
│   └── Schneider_Report.pdf
│
└── images/
```

---

## 📊 Dashboard Preview

### Project Manager Dashboard

Provides project managers with a comprehensive view of project health, invoice readiness, GR ageing, rework trends, and action priorities to support proactive project delivery.

<img width="900" alt="Project Manager Dashboard" src="https://github.com/user-attachments/assets/5ccdd86e-fda8-4770-bcb5-7f45bad8aaf5" />

---

### Finance Controller Dashboard

Provides finance teams with visibility into forecast accuracy, revenue leakage, billing performance, invoice corrections, and Days Sales Outstanding (DSO) to improve financial governance.

<img width="900" alt="Finance Controller Dashboard" src="PASTE_YOUR_FINANCE_IMAGE_LINK_HERE" />

---

### Regional Administration Dashboard

Provides operational insights into SLA performance, request intake channels, automation coverage, first-time-right processing, and workflow efficiency.

<img width="900" alt="Regional Administration Dashboard" src="https://github.com/user-attachments/assets/bc19cf62-5da3-4f3d-bc11-3d1c65b94f2a" />

---

# Skills Demonstrated

- Business Analytics
- Business Intelligence
- Data Visualization
- Dashboard Design
- Power BI
- SQL
- Excel
- KPI Development
- Data Storytelling
- Data Modelling
- Process Standardisation
- Digital Transformation
- Change Management
- Stakeholder Analysis
- Decision Support Systems

---

# Future Enhancements

- Machine Learning for revenue forecasting
- AI-based anomaly detection
- Power Automate workflow automation
- Real-time ERP integration
- Executive KPI alerting
- Azure-based data pipeline implementation

---

# Author

**Nivedha Murugan**

Master of Business Analytics  
Macquarie University

- **LinkedIn:** https://www.linkedin.com/in/nivedham8/
- **GitHub:** https://github.com/Nivedha-85
---

## License

This project is licensed under the MIT License.
