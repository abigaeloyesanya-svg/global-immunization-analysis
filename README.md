# Global Immunization Coverage Analysis
### WHO/UNICEF WUENIC 2024 | Python | Power BI | Health Analytics

## Overview
This project is a full end-to-end analysis of global vaccination 
coverage trends using the WHO/UNICEF WUENIC 2024 dataset — the 
most authoritative immunization data source in the world. It covers 
167 countries, 16 vaccine types, and 44 years of records from 
1980 to 2024.

The analysis goes beyond summary statistics. Before any chart was 
built, every sheet in the dataset was audited for data quality. 
Sheets with over 65% missing values were excluded with documented 
reasoning. Only 7 of the 16 vaccine sheets met the threshold for 
inclusion — 5 core vaccines with under 15% missing data, and 2 WHO 
priority vaccines included with clearly flagged caveats.

## Business Problem
WHO sets a 90% coverage target for a reason. Below that threshold, 
communities lose herd immunity and outbreaks become likely. Despite 
decades of global immunization programmes and billions in funding, 
nearly 20 million children worldwide did not complete their DTP3 
vaccination in 2024. This project investigates where the gaps are, 
which vaccines are failing the most, and whether coverage is 
recovering from the post-COVID disruption.

## Key Findings
- Global DTP3 coverage in 2024 stands at 85% — 5 percentage points 
  below the WHO 90% target
- 5 out of 7 UNICEF regions are still below the WHO target
- West and Central Africa has the lowest coverage at 72% and the 
  highest burden with 5.7 million unvaccinated children
- A visible post-COVID dip between 2019 and 2021 affected all 
  regions — West and Central Africa has not fully recovered
- The gap between DTP1 and DTP3 coverage signals a dropout problem, 
  not just an access problem
- Newer vaccines like Measles second dose (74%) and Hepatitis B 
  lag significantly behind older programs

## Tools and Technologies
- **Python** — data ingestion, cleaning, EDA, visualizations
- **Libraries** — Pandas, NumPy, Matplotlib, Seaborn
- **Power BI** — interactive 3-page dashboard
- **Data Source** — WHO/UNICEF WUENIC 2024

## Repository Structure
```
global-immunization-analysis/
│
├── notebook/
│ └── Project1_Global_Immunization_Analysis.ipynb
│
├── charts/
│ ├── chart1_global_dtp3_trend.png
│ ├── chart2_regional_dtp3_2024.png
│ ├── chart3_vaccine_comparison.png
│ ├── chart4_unvaccinated_by_region.png
│ ├── chart5_regional_trend.png
│ ├── chart6_top_bottom_countries.png
│ ├── chart7_heatmap_region_vaccine.png
│ └── chart8_dtp3_vs_mcv1.png
│
├── data/
│ └── cleaned_wuenic2024_final.xlsx
│
├── dashboard/
│ ├── wuenic_dashboard.pbix
│ └── wuenic_dashboard.pdf
│
└── README.md
```

## Dashboard Preview
[Page 1 — Global Overview]
[Page 2 — Regional Deep Dive]  
[Page 3 — Country Level]

## Full Article
Read the complete case study on Medium: [link]

## Author
**Oluwapelumi Abigael Oyesanya**
Data Analyst | Health Analytics | Python | Power BI 
