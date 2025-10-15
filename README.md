# Glassdoor Job Insights Dashboard

**Project:** Glassdoor Job Insights & Salary Analysis

**File included:** `Glassdoor Dashboard.pbix`

## About

The **Glassdoor Job Insights Dashboard** is a Power BI project that visualizes job market data, salary distributions, and company ratings based on data scraped or downloaded from Glassdoor. This dashboard helps job seekers, recruiters, and analysts understand hiring trends, compensation benchmarks, and company culture ratings across industries and locations.

> *This repository contains only the Power BI report file (`.pbix`). The underlying dataset is not included for confidentiality. Refer to the **Data & Connections** section to configure your own dataset.*

---

## Key Features

* **Salary Insights:** Analyze salary ranges, averages, and medians by job title, company, and location.
* **Job Distribution:** Explore job counts by role, region, and company type.
* **Company Ratings:** View company performance through ratings (overall, work-life balance, management, etc.).
* **Industry Breakdown:** Identify hiring trends and salary differences across industries.
* **Filters & Slicers:** Dynamic filters by location, job title, experience level, and company size.
* **Visual Storytelling:** Attractive and interactive visuals for data-driven decision-making.

---

## Recommended Folder Structure

```
/ (root)
├─ Glassdoor Dashboard.pbix        # Main Power BI project file
├─ data/                           # (optional) raw or processed data (CSV, Excel, SQL extracts)
├─ docs/                           # documentation, screenshots, data dictionary
└─ README.md                       # this file
```

---

## Requirements

* [Power BI Desktop](https://powerbi.microsoft.com/) (latest version)
* Access to Glassdoor dataset (CSV/Excel/SQL)
* Power BI Service (optional, for publishing and sharing)

---

## How to Open & Use

1. **Download** or **clone** this repository.
2. Open `Glassdoor Dashboard.pbix` in **Power BI Desktop**.
3. If the visuals are blank or broken, update the data source paths:

   * `Home → Transform Data → Data Source Settings`
4. Click **Refresh** after connecting your dataset to update visuals.

### Example Use Cases

* Compare salary ranges for similar job titles across different locations.
* Identify top-rated companies in specific industries.
* Explore hiring demand and job availability by region.
* Support HR and workforce analytics projects.

---

## Data & Connections

The dashboard connects to Glassdoor job and company data, typically structured as:

* **Job Data:** Job title, company name, location, salary estimate, experience level.
* **Company Data:** Ratings (overall, management, work-life balance, etc.).
* **Industry Data:** Sector classification and job volume per category.

To reconnect your dataset:

1. Go to `Transform Data → Data Source Settings`.
2. Choose the data source → `Change Source...`.
3. Browse and update the dataset path or connection credentials.

> ⚠️ **Note:** This `.pbix` file contains no raw data due to copyright restrictions from Glassdoor.

---

## Suggested Enhancements

* Add screenshots of visuals and insights in the `docs/` folder.
* Include a **data dictionary** describing each dataset column.
* Add **DAX measure descriptions** (for metrics like average salary, rating score, etc.).
* Document **Power Query transformations** used for data cleaning.

---

## Publishing

* Publish via Power BI Desktop → `File → Publish → Power BI Service`.
* Configure scheduled refresh if connected to an external database.
* Share dashboards securely using Power BI apps or embedded reports.

---

## Troubleshooting

| Issue            | Cause               | Solution                         |
| ---------------- | ------------------- | -------------------------------- |
| Blank visuals    | Missing data source | Update connections               |
| Slow performance | Large dataset       | Aggregate data or reduce columns |
| Publish error    | Permission issue    | Verify Power BI workspace access |

---

## License

Include your license of choice (e.g., MIT License) in a separate `LICENSE` file.

---

## Author / Maintainer

* **Author:** *Your Name*
* **Email:** *[your.email@example.com](mailto:your.email@example.com)*
* **Created:** 2025

---

## Version History

* **v1.0** — Initial release of `Glassdoor Dashboard.pbix`

---

> Need enhancements? I can extend this README with example visuals, DAX summary, or a section comparing industry salary benchmarks for GitHub documentation.
