# 🌐 Global Cybersecurity Threat Analysis Dashboard

An **Advanced Microsoft Excel data analytics project** that explores global cybersecurity incident records, financial losses, attack patterns, affected industries, vulnerabilities, defense mechanisms, and incident resolution time.

> **Dashboard preview:** The image below is a visual preview generated from the workbook's `Raw_Data` sheet. Open the Excel workbook to explore the original dashboard and its interactive elements.

![Global Cybersecurity Threat Analysis Dashboard](dashboard-preview.png)

## 📌 Project Overview

This project analyzes **3,000 cybersecurity incident records** across **10 countries** from **2015 to 2024**. The Excel workbook contains a dashboard, supporting pivot-analysis sheets, and the raw dataset.

The analysis is intended to help explore:
- Which attack types account for the highest recorded financial losses.
- How recorded financial losses vary by country.
- How incident counts vary by year.
- How incidents are distributed across reported attack sources.
- How average incident resolution time varies by defense mechanism.
## 📊 Dashboard Preview

![Global Cybersecurity Threat Analysis Dashboard](dashboard-preview.png)
## 🎯 Project Objectives

1. Explore global cybersecurity incident patterns.
2. Compare financial losses across attack types and countries.
3. Examine incident trends over the available years.
4. Understand the distribution of reported attack sources.
5. Compare average incident resolution time across defense mechanisms.
6. Present the analysis in an Excel dashboard for easier exploration.

## 📊 Dataset Details

- **Records:** 3,000
- **Columns:** 10
- **Countries represented:** 10
- **Year range:** 2015–2024

### Data Dictionary

| Column | Description |
|---|---|
| `Country` | Country associated with the incident |
| `Year` | Year of the incident |
| `Attack Type` | Reported type of cyberattack |
| `Target Industry` | Industry targeted |
| `Financial Loss (in Million $)` | Recorded financial loss, in million US dollars |
| `Number of Affected Users` | Number of users affected |
| `Attack Source` | Reported source category |
| `Security Vulnerability Type` | Vulnerability category associated with the incident |
| `Defense Mechanism Used` | Defense mechanism used |
| `Incident Resolution Time (in Hours)` | Time taken to resolve the incident, in hours |

## 📈 Dashboard Components

The workbook's dashboard includes five chart analyses:

1. **Loss by Attack Type** — compares financial loss across attack categories.
2. **Financial Loss by Country** — compares recorded losses across countries.
3. **Yearly Cybersecurity Trend** — shows incident counts by year.
4. **Attack Source Distribution** — displays the count of incidents by attack source.
5. **Incident Resolution Time by Defense Mechanism** — compares average resolution time by defense mechanism.

## 🔎 Selected Dataset Summary

These figures are calculated from the included `Raw_Data` sheet:

| Metric | Value |
|---|---:|
| Incident records | 3,000 |
| Countries | 10 |
| Years covered | 2015–2024 |
| Total recorded financial loss | $151,478.91 million |
| Average recorded financial loss per incident | $50.49 million |
| Total affected users (sum of records) | 1,514,052,409 |
| Average incident resolution time | 36.48 hours |

### Attack source counts

| Attack source | Incidents |
|---|---:|
| Nation-state | 794 |
| Unknown | 768 |
| Insider | 752 |
| Hacker Group | 686 |

## 🛠️ Tools & Excel Skills

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers / interactive filtering (where available in the workbook)
- Data summarization and aggregation
- Dashboard design and data visualization

## 📂 Repository Structure

```text
Global-Cybersecurity-Threat-Analysis/
├── Global_Cybersecurity_Threat_Dashboard.xlsx
├── dashboard-preview.png
└── README.md
```

## ▶️ How to Use

1. Download `Global_Cybersecurity_Threat_Dashboard.xlsx`.
2. Open it in Microsoft Excel (desktop Excel is recommended for workbook features).
3. Open the dashboard worksheet.
4. Use the available slicers and filters to explore the data.
5. Review the supporting analysis sheets and `Raw_Data` worksheet.

## 📝 Notes

- The workbook is provided as the project deliverable; the raw dataset is included in the same Excel file.
- Financial-loss figures are expressed in **million US dollars**, as indicated by the source column name.
- The repository preview image is generated from the workbook's data. It is not a direct screenshot of the Excel application window.
- The dataset is presented as supplied in the workbook; this repository does not claim that it is a live cybersecurity threat feed.

## 👨‍💻 Author

**Om Pingle**  
Information Technology Engineering Student  
Interests: Data Analytics and Cybersecurity

---

If you find this project useful, feel free to ⭐ the repository.
