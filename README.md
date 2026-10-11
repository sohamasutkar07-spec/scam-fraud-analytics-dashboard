# Scam & Fraud Analytics Dashboard

**Portfolio project | Power BI | Financial-loss and case analysis**

## Overview

This Power BI report explores scam-related cases and reported financial losses across applications, scam types, platforms, user demographics, states, complaint sources, and recovery outcomes.

The dashboard contains four report views. Filters allow users to explore reporting year and quarter, app category/name, state, age group, gender, platform, complaint source, outcome status, and ban status.

> **Data and interpretation note:** The report visuals show figures and categories displayed in the supplied Power BI screenshots. The source dataset provenance is not documented here, so do not treat the figures as verified official statistics without checking the underlying source and definitions.

## Report highlights visible in the dashboard

The overview page shows:
- **Total amount lost:** approximately ₹8.68 billion
- **Average loss per case:** approximately ₹867.89 thousand
- **Total cases:** 10,000
- **Total apps:** 12

The detailed table on the overview screenshot shows total amount lost of ₹8,678,915,946.04 and average loss per case of ₹867,891.59. These amounts and counts should be interpreted according to the data model and metric definitions in the PBIX file.

## Dashboard pages

### 1. Financial-loss overview

- KPI cards for total amount lost, average loss per case, case count, and app count
- Slicers for report year, quarter, app category, and user state
- Amount lost and case trends by year/quarter
- Amount lost by scam type
- App-level case counts, total losses, and average loss per case

![Financial-loss overview](screenshots/Screenshot%202025-11-29%20002937.png)

### 2. Demographic and platform analysis

- Total amount lost by user age group
- Case distribution by acquisition channel
- Total cases by platform type
- Filters for age group, gender, app category, and platform type

![Demographic and platform analysis](screenshots/Screenshot%202025-11-29%20002954.png)

### 3. State and ban analysis

- State-level view of amount lost, cases, average loss per case, and recovery rate
- Total amount lost by user state
- Case counts by government ban reason
- Filters for ban status, user state, and app name

![State and ban analysis](screenshots/Screenshot%202025-11-29%20003007.png)

### 4. Complaints and recovery outcomes

- Cases by complaint source and outcome status
- Cases by year/quarter
- Case-level table with scam ID, app, state, amount lost, complaint source, and outcome status
- Filters for complaint source, outcome status, and app name

![Complaints and recovery outcomes](screenshots/Screenshot%202025-11-29%20003021.png)

## Files

- `dashboard/visuals%20completed%20power%20bi.pbix` — Power BI Desktop report file
- `screenshots/` — exported screenshots of the four report views

## Tools and techniques

- Power BI
- KPI cards and interactive slicers
- Bar/column charts, line/area trend chart, donut chart, map visual, and detailed data table
- Drill-down investigation through filters for period, geography, app, platform, complaint source, and outcome

The description above is limited to the visuals shown in the provided screenshots. Add specific claims about Power Query, DAX measures, relationships, or data transformations only after confirming them in the PBIX model.

## Potential business questions

- Which scam types account for the greatest reported financial losses?
- Which applications have the highest case counts and average loss per case?
- How do reported losses vary by age group, state, and platform?
- Which complaint sources and recovery outcomes appear most frequently?
- Which government ban reasons are associated with case records?

These are analytical questions supported by the report layout; any recommendations should be grounded in the data definitions and validated results.

## Reproducibility and limitations

- Screenshots demonstrate report visuals but do not expose all model logic.
- Verify measure definitions, filters, date sorting, and source data within Power BI before using the dashboard for decision-making.
- Financial-loss totals depend on the quality and provenance of the underlying records.
- Do not treat dashboard associations as evidence of causation.
- No claim is made that the dashboard has been independently audited or that the reported amounts represent official statistics.

## Author

Portfolio project by Soham Asutkar.
