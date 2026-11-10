# SWYNEX Task 3: Interactive Dashboard

## Overview
An interactive Power BI dashboard built on the cleaned Titanic dataset from Tasks 1 and 2 (891 passengers).

## Tools Used
- Power BI Desktop
- Python (pandas) in Google Colab to add FamilySize and AgeGroup columns

## Dashboard Features
**KPIs:** Total Passengers, Survival Rate, Average Fare, Average Age

**Charts:**
- Survival rate by Sex
- Survival rate by Passenger Class
- Survival rate by Age Group
- Survival rate by Family Size
- Passenger share by Port of Embarkation (donut)
- Average fare by Passenger Class

**Filters (slicers):** Sex, Passenger Class, Port of Embarkation, Age Group

## Key Findings
- Overall survival rate was 38.4%.
- Women survived at 74.2% compared to 18.9% for men.
- Survival fell with class: 63.0% (1st) and 24.2% (3rd).
- Families of 2-4 passengers had the highest survival rates.

## Screenshots
![Dashboard](dashboard_screenshot.png)
![Filtered view](dashboard_filtered.png)

## Files
- `SWYNEX_Interactive_Dashboard.pbix`: Power BI dashboard (open with Power BI Desktop)
- `dashboard_data.csv`: dataset used
- `dashboard_screenshot.png`, `dashboard_filtered.png`: previews

## How to Use
Download the .pbix file, open it in Power BI Desktop, and use the slicers to filter the charts.
