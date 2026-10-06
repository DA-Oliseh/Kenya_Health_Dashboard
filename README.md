# Kenya County Health Dashboard 🏥

An interactive Power BI dashboard analysing outpatient visits, 
disease burden, and maternal & child health indicators across 
5 Kenya counties (Nairobi, Mombasa, Kisumu, Nakuru, Eldoret).

## Project Overview
Built as a portfolio project simulating the kind of dashboard 
an MOH department, county government, or NGO would use for 
health data decision-making.

## Data Model
- 4 tables: Facilities, OPD Visits, Disease Burden, Maternal & Child Health
- Star schema with 3 one-to-many relationships via facility_id
- 2 years of monthly data (2023–2024) across 67 facilities

## DAX Measures
- Total OPD Visits
- Total Under-5 Visits
- % Under-5 Visits
- Total Disease Cases
- Skilled Delivery Rate

## Dashboard Pages
**Page 1 — Overview**
- KPI cards: Total OPD Visits, Disease Cases, Skilled Delivery Rate
- OPD Visits by County
- Monthly OPD Trend

**Page 2 — Disease Burden**
- Disease Cases by Disease Type (10 diseases)
- Disease Cases by County
- Disease Cases by Month

**Page 3 — Maternal & Child Health**
- Skilled Delivery Rate by County
- ANC1 Visits by County

## Tools Used
- Power BI Desktop
- DAX
- Power Query

## Data Source
Simulated Kenya county health data modelled on MOH DHIS2 
reporting structure. Generated for portfolio purposes.

## Files
- `Kenya_County_Health_Dashboard.pbix` — Power BI project file
- `Kenya_County_Health_Dashboard.pdf` — Dashboard export
- `facilities.csv` — Facility master data
- `opd_visits.csv` — Monthly OPD visit data
- `disease_burden.csv` — Monthly disease case data
- `maternal_child_health.csv` — Maternal & child health indicators
