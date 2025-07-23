# Western Australia Mining Tenement Dashboard

This project visualises and analyses mining tenements across Western Australia using geospatial data and interactive visualisations.

## Project Overview

Western Australia holds a vast number of mining tenements, each representing different types of licenses and exploration statuses. This project aims to provide a clear view of:
- The volume and status of tenements (Live, Pending, Surveyed, Unsurveyed)
- Tenement types and distributions
- Trends in tenement grants over time
- Regional insights based on WA’s **Regional Development Commission Boundaries (DPIRD-020)**

Built using:
-  Python + GeoPandas for spatial processing
-  Power BI for interactive dashboarding

## 📈 Dashboard

Explore the live dashboard here:  
👉 [WA Mining Tenement Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzE5OTRkODAtMTkyYy00YjA0LWEzODgtYWU4MDQyYjE3NzZmIiwidCI6IjJmOTEzM2NiLWJhNGEtNDFmYy1hZGQ5LTZjMGEzZTYwY2Q4ZSJ9)
<img width="1128" height="632" alt="Screenshot 2025-07-23 at 1 05 17 pm" src="https://github.com/user-attachments/assets/4d2c251c-9cb6-43cd-991a-6572fb2e4fe2" />
<img width="1126" height="635" alt="Screenshot 2025-07-23 at 1 05 33 pm" src="https://github.com/user-attachments/assets/db864cd1-40ee-4f0e-af3e-9afc7e2e97af" />


> *Note: Best viewed on desktop.*

## Datasets

1. **Mining Tenements (DMIRS-003)**  
   Source: [data.wa.gov.au](https://catalogue.data.wa.gov.au/dataset/mining-tenements-dmirs-003)

2. **Regional Development Commission Boundaries (DPIRD-020)**  
   Source: [data.wa.gov.au](https://catalogue.data.wa.gov.au/dataset/regional-development-commissions-regions-dpird-020)

## Files in this Repo
- `MineTenementWA.ipynb`: Jupyter Notebook for cleaning, processing, and joining geospatial datasets.
- `tenements_wa.csv`: Cleaned tenement data including centroid coordinates.
- `tenement_regions_clean.csv`: Mapping of tenements to WA regions using regional boundary geometry.
- `tenement_holders.csv`: Extracted holder details, separated from the main tenement dataset for normalisation.
- `README.md`: You're reading it!

## Insights

- Over **29,882** tenements across WA, with nearly **80% currently live**.
- **Exploration Licenses** are the most common tenement type.
- **Goldfields-Esperance and Pilbara** regions hold the largest concentration of tenements.
- Significant growth in tenement grants since the early 2000s.
