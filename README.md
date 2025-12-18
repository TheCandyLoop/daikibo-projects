# daikibo-projects
Tableau dashboard and Excel task for Deloitte

## Task 1: Telemetry Data Dashboard

**Objective:**  
Analyze telemetry data from Daikibo devices to identify downtime per factory and per device type.

**Details:**  
- Imported `daikibo-telemetry-data.json` into Tableau.  
- Created a calculated field `Unhealthy` (10 minutes per unhealthy status).  
- Built two bar charts:  
  1. Down Time per Factory  
  2. Down Time per Device Type  
- Combined charts into a dashboard with interactive filtering.  
- Selected the factory with the most downtime.  

**Deliverable:**  
- `Task1_Dashboard.png` → screenshot of the dashboard showing the factory with the most downtime.

---

## Task 2: Gender Pay Equality Analysis

**Objective:**  
Classify employee roles based on equality scores to investigate potential pay disparities.

**Details:**  
- Used `Equality Table.xlsx` containing: Factory, Job Role, Equality Score.  
- Added a new column `Equality Class` based on the following rules:  
  - **Fair:** Equality Score between -10 and +10  
  - **Unfair:** Equality Score between -20 and -11 or 11 and 20  
  - **Highly Discriminative:** Equality Score < -20 or > 20  

**Deliverable:**  
- `Equality Table.xlsx` → completed Excel file with `Equality Class` filled.

---

## Repository Contents

| File | Description |
|------|-------------|
| `Task1_Dashboard.png` | Screenshot of Tableau dashboard (Task 1) |
| `Equality Table.xlsx` | Completed Excel table with Equality Class (Task 2) |
| `README.md` | This file, explaining both tasks |

---

## Notes

- Tableau Public was used to recreate the dashboard since the trial version expired.  
- Only the deliverables (screenshot and completed Excel file) are included in this repository; raw telemetry data is not uploaded for privacy.  
