# HVAC Market Analysis Dashboards

Multi-county Power BI dashboard suite that analyzes the HVAC contractor market across Southern California, helping identify where competition is dense and where market opportunity exists at the ZIP-code level.

> Built as a freelance project for a U.S.-based HVAC/refrigeration business. All data in this repository is anonymized or sample data.

## Business Problem
The client needed to understand contractor competition and market potential across multiple counties before deciding where to focus outreach and expansion. Raw contractor licensing records, demographics and supply store data were scattered across many files, so there was no single view of the market.

## Coverage
- Riverside County
- San Bernardino County
- Los Angeles County
- Orange County

## What I Built
- **Standardized data model:** One Excel master file per city or county, all with the same 20-column structure: ZIP-level contractor counts by license classification, demographics, direct-mail address counts, supply store counts, and derived density metrics.
- **Multi-page Power BI reports** with:
  - ZIP-level contractor maps
  - Market analysis pages
  - Contractor density charts
  - Data insight KPI cards
- **Consolidated county reports:** A single Power BI file per county with a **City slicer synced across all pages**, so users can filter the whole report by city in one click.

## Tools & Skills
`Power BI` `Excel` `Power Query` `Data Cleaning` `Data Modeling` `Map Visuals` `KPI Design`

## Data Pipeline
1. Collect public contractor licensing data and supporting datasets per city
2. Clean and standardize into the 20-column Excel master format (Power Query / Excel)
3. Load into Power BI and build the data model
4. Design report pages, maps, KPI cards and slicers
5. Review with the client and iterate on feedback

## Screenshots
![Dashboard overview]
![ZIP-level contractor map]
![Density analysis]

## Key Technical Lessons
- Fixed map plotting issues by setting latitude/longitude fields to "Don't summarize" instead of the default aggregation
- Resolved map visual conflicts when multiple map visuals shared a page
- Used **Sync Slicers** so one city filter controls every page
- Adjusted KPI card **Display Units** to prevent truncated or misleading number formatting

## Results
- Delivered dashboards for four counties on a consistent, reusable template
- The consolidated County dashboard with the synced City slicer received strong client feedback and became the model for later dashboards
- *(Add a measurable outcome if you have one, e.g. "reduced report prep time from X to Y")*

## Repository Structure
