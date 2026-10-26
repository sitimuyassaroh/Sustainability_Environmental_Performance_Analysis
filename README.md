# 🌱 Sustainability & Environmental Performance Analysis
### Deloitte Australia – Data Analysis & Forensic Technology Job Simulation

![Excel](https://img.shields.io/badge/Excel-Data%20Cleaning%20%26%20Analysis-217346?logo=microsoftexcel&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-E97627?logo=tableau&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

This project was completed as part of the **Deloitte Australia Data Analysis Job Simulation (Forensic Technology)**. The scenario: a multinational manufacturing client operating **4 branches in different countries** needs to understand its sustainability and environmental performance, specifically which branch has the worst working conditions and what is causing them.

Using environmental sensor/device data, I classified each reading as **healthy** or **unhealthy**, compared the branches, and traced the problem to a specific piece of equipment.

## 🎯 Business Questions

1. Which branch has the **highest number of unhealthy working condition** indicators?
2. Which **device / equipment type** is responsible for those unhealthy conditions?
3. How can the findings be presented so management can act on them?

## 🏭 Branches in Scope

| Branch |
|---|
| Daikibo Berlin |
| Daikibo Factory Meiyo |
| Daikibo Factory Seiko |
| Daikibo Shenzhen |

## 🛠️ Tools & Skills

| Tool | Usage |
|---|---|
| **Microsoft Excel** | Data cleaning, classification (healthy / unhealthy), logical filtering, pivot-style comparison |
| **Tableau Public** | Interactive dashboard to visualize cross-branch performance |
| **Analytical skills** | Comparative analysis, root-cause identification, business storytelling |

## 🔄 Methodology

1. **Data understanding**: reviewed the raw environmental and sustainability datasets for all 4 branches.
2. **Data cleaning & structuring (Excel)**: standardized fields, removed inconsistencies, and organized the data into an analysis-ready format.
3. **Classification**: applied logical conditions to label each record as *healthy* or *unhealthy*.
4. **Comparative analysis**: aggregated unhealthy counts per branch, then drilled down per device type.
5. **Visualization (Tableau)**: built bar charts and combined them in a dashboard to highlight risk patterns.
6. **Conclusion & recommendation**: translated findings into actionable business insights.

## 📊 Key Findings

> Values are read from the Tableau dashboard (`SUM(unhealthy)`).

- **Daikibo Factory Seiko has the highest unhealthy working condition**, with about **480** unhealthy records. This is the highest among all 4 branches.
- Daikibo Shenzhen follows with roughly **420**, while Daikibo Factory Meiyo (~105) and Daikibo Berlin (~15) are far lower.
- The **LaserWelder** is the device responsible. It accounts for about **480** unhealthy records, while every other device type (AirWrench, CNC, ConveyorBelt, Furnace, HeavyDutyDrill, LaserCutter, MetalPress, SpotWelder) shows close to zero.

**Conclusion:** the unhealthy conditions are not spread evenly across the company. They are concentrated in **one branch (Seiko)** and driven by **one equipment type (LaserWelder)**, which makes the problem targeted and fixable.

## 💡 Recommendations

- Prioritize inspection, maintenance, or replacement of **LaserWelder** units at Daikibo Factory Seiko.
- Review ventilation, emissions control, and safety protocols around laser-welding areas.
- Check LaserWelder units in the other branches (especially Shenzhen) as a preventive measure.
- Set up continuous monitoring so unhealthy thresholds trigger early alerts.

## 📈 Dashboard Preview

![Tableau Dashboard](images/dashboard.jpg)

**Dashboard components**
- **Down Time per Factory**: unhealthy count by branch.
- **Down Time per Device Type**: unhealthy count by equipment type.
- Interactive highlighting: selecting a branch filters the device view.

## 📁 Repository Structure

```
├── README.md
├── images/
│   └── dashboard.jpg          # Tableau dashboard screenshot
├── data/
│   └── ...                    # Excel working files (cleaned / classified data)
└── tableau/
    └── ...                    # Tableau workbook (.twbx) or Tableau Public link
```

> Rename the folders and files above to match your repository.

## 🔗 Certificate
**Certificate here:** [Amazon Performance Business Analytics Dashboard](add link)

## 🧠 What I Learned

- Turning raw, messy operational data into structured, decision-ready datasets.
- Using comparative analysis to move from a company-wide view to a branch and then to a specific device.
- Presenting technical findings in a dashboard that non-technical stakeholders can read quickly.

## 👤 Author

**Siti Muyassaroh**
- LinkedIn: _[Siti Muyassaroh](https://www.linkedin.com/in/sitimuyassaroh/)_
- GitHub: _[Siti Muyassaroh](https://github.com/sitimuyassaroh)_

---

*This project is a job simulation for learning and portfolio purposes. All data is simulated and does not represent a real client.*
