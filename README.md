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
**1. EV Adoption by State**
Washington (WA) dominates the dataset with 114,000+ electric vehicles registered, far ahead of California (CA) and Virginia (VA).

*Analysis:* Washington's strong EV presence suggests mature infrastructure, favourable incentives, and widespread adoption. This trend reflects the state’s commitment to sustainable transportation and positions it as a benchmark for EV policy implementation in the U.S.

   ![image](https://github.com/user-attachments/assets/6849a609-bf0d-4725-8b6c-cdbb783916c6)

**2. Battery Electric Vehicles (BEVs) Lead the Market**
BEVs represent approximately 77% of all electric vehicles, with the remaining share held by Plug-in Hybrid Electric Vehicles (PHEVs).

**Analysis:** The market is clearly shifting toward fully electric vehicles, driven by advances in battery technology, longer range, and zero-emission incentives. This shows a growing consumer preference for cleaner and more future-ready mobility solutions.
  
  ![image](https://github.com/user-attachments/assets/60f0bf91-36da-4d16-8b13-b672cc88c84f)

**3. Clean Fuel Eligibility**
Over 50% of the vehicles qualify as Clean Alternative Fuel Vehicles (CAFV), while a significant portion lacks eligibility due to limited battery range.

**Analysis:** Manufacturers are increasingly focused on meeting clean fuel criteria, which aligns with federal and state regulations. However, there's still a notable gap in vehicles falling short—highlighting opportunities for innovation and compliance-focused upgrades.
  
   ![image](https://github.com/user-attachments/assets/4b6ee8b4-207c-46e5-ae72-6aeb55a93b68)

**4. Top Manufacturers and Models**
Tesla is the leading brand, with the Model 3 and Model Y among the top registered EVs. Other notable brands include Chevrolet and Nissan.

**Analysis:** Tesla’s dominance is due to its advanced technology, superior range, and strong brand equity. Chevrolet and Nissan show consistent performance, especially among early adopters. This data can guide competitors in benchmarking product performance and customer loyalty.
  
   ![image](https://github.com/user-attachments/assets/85cd9e7f-34e8-4033-82a8-2b5c487987e6)

**5. Model Year Growth**
A steep increase in EV adoption is visible from 2017 onward, with exponential growth in recent years.

**Analysis:** This reflects industry-wide momentum post-2016 when multiple manufacturers launched high-range models. Government rebates and consumer awareness also contributed to the surge. Expect continued upward trends with upcoming federal EV initiatives.


**6. Average Electric Range by Manufacturer**
Jaguar leads with an average electric range of 206+ miles, followed by Tesla, Chevrolet, and others.

**Analysis:** Manufacturers are investing in battery efficiency to stay competitive. Longer range not only appeals to urban users but also helps overcome range anxiety—a major adoption barrier. Highlighting this metric supports consumer education and industry benchmarking.
  
   ![image](https://github.com/user-attachments/assets/a9fbe6b0-0990-482f-b42c-6dc1ba416ac1)


##  Recommendations
- **Policy Makers & Government Agencies**:
  1. Expand EV incentives in underperforming regions to encourage broader adoption.
  2. Invest in public charging stations and EV-friendly infrastructure, especially in rural areas.

- **Automotive Manufacturers**
1. Prioritize development of Battery Electric Vehicles (BEVs) to match consumer trends.
2. Improve battery range for hybrid models to qualify for clean fuel programs (CAFV).

-**Marketing & Sales Teams**
1. Launch targeted campaigns in high-adoption states like WA and CA.
2. Promote EVs with CAFV eligibility and sustainability features to eco-conscious buyers.

-**Electric Utility Providers**
1. Partner with automakers to bundle home charging solutions with EV sales.
2. Develop off-peak charging plans to reduce grid stress and support EV owners.

-**Analysts & Decision-Makers**
1. Track underperforming states to identify and resolve adoption barriers.
2. Use data to forecast EV demand and guide future model releases or market entries.

# Conclusion
-The analysis reveals strong EV growth in select regions and a clear market shift toward BEVs.
-With data-driven actions from stakeholders, the U.S. EV market can achieve faster, smarter, and greener adoption.

