# US Air Pollution Analytics Dashboard (2006–2010)

A multi-page Power BI dashboard analyzing four major air pollutants — Carbon Monoxide (CO), Ozone (O3), Sulphur Dioxide (SO2), and Nitrogen Dioxide (NO2) — across US states and counties from 2006 to 2010. The dashboard uses AQI (Air Quality Index) measurements to identify the most polluted states, track yearly trends, and support environmental data exploration.

**Author:** Ashwin Suryawanshi | **Tool:** Power BI Desktop

---

## Files in This Repository

| File | Description |
|------|-------------|
| `US_Pollution.pbix` | Power BI dashboard — 5 pages (1 overview + 4 pollutant pages), navigation buttons, filled map |

---

## Tools & Technologies

- **Power BI Desktop** — filled map, area charts, clustered bar charts, tables, pie chart, action buttons, slicers
- **Data Source:** `US Pollution 2006-2010` dataset

---

## Dataset

**Period:** 2006–2010 | **Source:** US Pollution 2006–2010

| Column | Description |
|--------|-------------|
| `State` | US state name |
| `County` | County name |
| `County Code` | County numeric code |
| `State Code` | State numeric code |
| `City` | City of measurement station |
| `Date Local` | Date of measurement |
| `CO AQI` | Carbon Monoxide Air Quality Index |
| `CO 1st Max Value` | Peak CO concentration reading |
| `CO 1st Max Hour` | Hour of peak CO reading |
| `CO Units` | Measurement unit for CO |
| `O3 AQI` | Ozone Air Quality Index |
| `O3 1st Max Value` | Peak O3 concentration |
| `O3 1st Max Hour` | Hour of peak O3 reading |
| `SO2 AQI` | Sulphur Dioxide Air Quality Index |
| `SO2 1st Max Value` | Peak SO2 concentration |
| `SO2 1st Max Hour` | Hour of peak SO2 reading |
| `NO2 AQI` | Nitrogen Dioxide Air Quality Index |
| `NO2 1st Max Value` | Peak NO2 concentration |
| `NO2 1st Max Hour` | Hour of peak NO2 reading |

---

## Dashboard Pages (5)

### Page 1 — Overview
| Visual | Type | Purpose |
|--------|------|---------|
| Navigation Buttons | Action Buttons | Direct links to CO, O3, SO2, NO2 pages |
| US State Map | Filled Map | Geographic overview of states in dataset |
| AQI by Quarter | Pie Chart | Combined AQI (NO2, CO, SO2, O3) breakdown by quarter |
| County Reference Table | Table | County name and count of records |
| City Slicer | Slicer | Filter by city |
| State Slicer | Slicer | Filter by state |
| County Slicer | Slicer | Filter by county |
| Date Slicer | Slicer | Filter by date range |

### Page 2 — Carbon Monoxide (CO)
| Visual | Type | Fields |
|--------|------|--------|
| Peak CO Hour | Card | Sum of CO 1st Max Hour |
| Peak CO Value | Card | Sum of CO 1st Max Value |
| City (highest CO) | Card | City |
| CO Units | Card | CO Units |
| States with Highest CO | Table | State, Sum of CO AQI |
| CO AQI by Year | Area Chart | Year, Sum of CO AQI |
| CO AQI by State | Clustered Bar | State, Sum of CO AQI |
| State Count Table | Table | State Code count, Sum of CO AQI |
| Date Slicer | Slicer | Date Local range filter |

### Page 3 — Ozone (O3)
| Visual | Type | Fields |
|--------|------|--------|
| Peak O3 Hour | Card | Sum of O3 1st Max Hour |
| Peak O3 Value | Card | Sum of O3 1st Max Value |
| City (highest O3) | Card | City |
| CO Units | Card | Units |
| States with Highest O3 | Table | State, Sum of O3 AQI |
| O3 AQI by Year | Area Chart | Year, Sum of O3 AQI |
| O3 AQI by State | Clustered Bar | State, Sum of O3 AQI |
| State Count Table | Table | State Code count, Sum of O3 AQI |
| Date Slicer | Slicer | Date Local range filter |

### Page 4 — Sulphur Dioxide (SO2)
| Visual | Type | Fields |
|--------|------|--------|
| Peak SO2 Hour | Card | Sum of SO2 1st Max Hour |
| Peak SO2 Value | Card | Sum of SO2 1st Max Value |
| City (highest SO2) | Card | City |
| Units | Card | CO Units |
| States with Highest SO2 | Table | State, Sum of SO2 AQI |
| SO2 AQI by Year | Area Chart | Year, Sum of SO2 AQI |
| SO2 AQI by State | Clustered Bar | State, Sum of SO2 AQI |
| State Count Table | Table | State Code count, Sum of SO2 AQI |
| Date Slicer | Slicer | Date Local range filter |

### Page 5 — Nitrogen Dioxide (NO2)
| Visual | Type | Fields |
|--------|------|--------|
| Peak NO2 Hour | Card | Sum of NO2 1st Max Hour |
| Peak NO2 Value | Card | Sum of NO2 1st Max Value |
| City (highest NO2) | Card | City |
| Units | Card | CO Units |
| States with Highest NO2 | Table | State, Sum of NO2 AQI |
| NO2 AQI by Year | Area Chart | Year, Sum of NO2 AQI |
| NO2 AQI by State | Clustered Bar | State, Sum of NO2 AQI |
| State Count Table | Table | State Code count, Sum of NO2 AQI |
| Date Slicer | Slicer | Date Local range filter |

---

## Key Insights Enabled

- **State-level pollution ranking** — bar charts on each page rank all states by AQI for every pollutant
- **Year-over-year trends** — area charts track whether pollution improved or worsened 2006–2010
- **Peak hour detection** — cards show which hour of day sees the highest pollutant concentrations
- **Quarterly seasonality** — overview pie chart reveals which quarters carry the highest combined AQI
- **Geographic overview** — filled map gives a spatial view of which states are represented
- **Cross-pollutant navigation** — action buttons enable fast switching between all 4 pollutant views

---

## Suggested Repo Name

`US-Air-Pollution-Analytics-PowerBI-2006-2010`

---

## Topics

`power-bi` `air-quality` `pollution` `environmental-data` `aqi` `data-visualization` `usa` `data-analysis`
