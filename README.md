# Power BI Projects

![Power BI](https://img.shields.io/badge/Power%20BI-Interactive%20Reports-yellow?style=flat-square&logo=powerbi)
![Status](https://img.shields.io/badge/status-Active-brightgreen?style=flat-square)

A collection of Power BI projects showcasing data analysis, visualization, and interactive dashboard development skills.

---

## Project: Maven Toys KPI Dashboard

### Overview

This project demonstrates the creation of an interactive KPI dashboard for **Maven Toys**, a toy store chain with multiple locations across Mexico. The dashboard enables leadership teams to monitor key business metrics and identify high-level trends in real-time.

### What This Project Shows

- **Data Connection & Profiling**: Importing and analyzing data from multiple sources
- **Relational Data Modeling**: Building a structured data model with proper relationships
- **DAX Calculations**: Creating calculated measures and fields for business metrics
- **Interactive Visualization**: Building dynamic, filterable reports and dashboards
- **Business Intelligence**: Translating raw data into actionable insights

### Dataset Details

| Attribute | Description |
|-----------|-------------|
| **Company** | Maven Toys |
| **Industry** | Retail - Toy Store Chain |
| **Locations** | Multiple stores across Mexico |
| **Time Period** | January 2022 - September 2023 |
| **Data Type** | Transactional sales records, product information, store locations |

### Key Metrics Visualized

- Sales performance and trends
- Revenue by store location
- Product-level analysis
- Temporal patterns (daily, monthly, quarterly)
- Year-over-year comparisons

---

## Repository Structure

```
PowerBI-Projects/
├── README.md
├── LICENSE
├── PROJECT_POWERBI_001_MAVEN_TOYS/
│   ├── PROJECT_POWERBI_001_MAVEN_TOYS.pbix      # Power BI report file
│   ├── PROJECT_POWERBI_001_MAVEN_TOYS.pdf        # Exported report
│   ├── PROJECT_POWERBI_001_MAVEN_TOYS_Screenshot.png  # Dashboard preview
│   ├── PROJECT_POWERBI_001_MAVEN_TOYS_video.mp4  # Demo video
│   └── PROJECT_POWERBI_001_MAVEN_TOYS_Maven Toys Data.zip  # Source data
```

---

## How to Use

### Prerequisites

- [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (latest version)
- Windows or macOS operating system

### Opening the Report

1. Clone or download this repository
2. Navigate to the project folder
3. Open the `.pbix` file with Power BI Desktop:
   ```bash
   # On Windows (if Power BI is installed)
   start PROJECT_POWERBI_001_MAVEN_TOYS.pbix
   
   # Or simply double-click the file to open in Power BI Desktop
   ```
4. Explore the interactive filters, slicers, and drill-through capabilities

### Working with the Data

The source data is provided in the zip file. To refresh or modify:

1. Extract the data files from the zip archive
2. Use Power BI's "Get Data" to connect to the source files
3. Follow the modeling steps outlined in the project PDF

---

## Technologies Used

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoft/azure-original.svg" width="40" height="40" alt="Azure" title="Microsoft Azure"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/excel/excel-original.svg" width="40" height="40" alt="Excel" title="Microsoft Excel"/>
  <img src="https://img.icons8.com/color/48/microsoft-office-2019.png" width="40" height="40" alt="Office" title="Microsoft Office"/>
</p>

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Data visualization and report building |
| Power Query | Data extraction, transformation, and loading (ETL) |
| DAX | Calculated measures and business logic |
| Excel | Source data format and supplementary analysis |

---

## Learning Source

This project was built following the LinkedIn Learning course: **"Build an Interactive Business KPI Dashboard with Power BI (Guided Project)"**

---

## Author

**Claudio Falconi**

*Data Analyst | Business Intelligence Enthusiast*

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Last Updated: May 2026*
