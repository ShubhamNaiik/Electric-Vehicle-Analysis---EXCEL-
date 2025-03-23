#  Electric Vehicle Analysis Dashboard - 2024

##  Project Overview
This project analyzes electric vehicle (EV) adoption across U.S. states, manufacturers, and consumer segments using VIN registration data. An interactive Excel dashboard provides insights into electric range, EV types, geographic trends, and clean fuel eligibility to support data-driven decision-making.

##  Objectives
- Identify states with the highest EV adoption.
- Compare Battery Electric Vehicles (BEVs) vs Plug-in Hybrid Electric Vehicles (PHEVs).
- Analyze average electric range by model and manufacturer.
- Explore Clean Alternative Fuel Vehicle (CAFV) eligibility.
- Discover top EV manufacturers and best-selling models.
- Track EV trends over model years and regions.
- Provide visual KPIs and dashboards for stakeholders.

## Dashboard
![image](https://github.com/user-attachments/assets/9a413c1c-40d1-4cc4-b351-d0e5a2a797c7)


##  Dataset Description
The project uses EV registration data with the following key columns:

| Column Name                          | Description |
|-------------------------------------|-------------|
| `VIN (1–10)`                        | Unique Vehicle Identifier |
| `County`, `City`, `State`, `Zip`   | Geographical info |
| `Model Year`                        | Year of manufacture |
| `Make`, `Model`                     | Manufacturer and model |
| `Electric Vehicle Type`            | BEV or PHEV |
| `CAFV Eligibility`                 | Clean fuel compliance status |
| `Electric Range`                   | Max miles on full charge |
| `Base MSRP`                        | Manufacturer suggested price |
| `Electric Utility`                 | Utility provider |
| `Vehicle Location`                 | Geo-coordinates |
| `Census Tract`                     | Demographic location data |

##  Data Preparation
- Converted raw data into structured Excel tables for easier referencing.
- Cleaned and standardized column formats.
- Used `COUNTIF`, `AVERAGEIFS`, and `INDEX-MATCH` for calculations.
- Built PivotTables and PivotCharts to summarize and filter data.
- Created slicers for interactive dashboard navigation.

##  Dashboard Features
- **KPI Cards**: Total EVs, Average Electric Range
- **State Map View**: EV counts by state
- **Model Year Trend**: Yearly growth of EVs
- **Top EV Models**: Most popular by count
- **Electric Range by Manufacturer**: Compare average range
- **CAFV Breakdown**: Eligibility status analysis

##  Key Insights
- **Top States**: Washington leads with 114,000+ EVs
    ![image](https://github.com/user-attachments/assets/6849a609-bf0d-4725-8b6c-cdbb783916c6)

- **Vehicle Types**: BEVs make up ~77% of all entries
    ![image](https://github.com/user-attachments/assets/60f0bf91-36da-4d16-8b13-b672cc88c84f)

- **CAFV Eligible**: Over 50% of vehicles meet clean fuel criteria
    ![image](https://github.com/user-attachments/assets/4b6ee8b4-207c-46e5-ae72-6aeb55a93b68)

- **Top Models**: Tesla Model 3 and Y dominate the market
      ![image](https://github.com/user-attachments/assets/85cd9e7f-34e8-4033-82a8-2b5c487987e6)

- **Longest Range**: Jaguar leads with 200+ average miles
      ![image](https://github.com/user-attachments/assets/a9fbe6b0-0990-482f-b42c-6dc1ba416ac1)


##  Recommendations
- **Policy Makers**: Expand infrastructure in WA, CA, and high-growth states
- **Auto Industry**: Increase high-range BEV availability
- **Utility Providers**: Target EV-heavy districts for collaboration
- **Marketing Teams**: Focus campaigns on BEV and CAFV-compliant models


