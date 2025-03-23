# Electric-Vehicle-Analysis  -EXCEL
 Electric Vehicle Analysis Dashboard - 2024
Project Overview
This project analyzes electric vehicle (EV) adoption across states, manufacturers, and customer segments in the U.S., based on detailed VIN registration data. The goal is to provide key insights into trends in EV usage, vehicle types, geographic adoption, and performance metrics through an interactive Excel dashboard.

 Objectives
1.Understand which states are leading in EV adoption.

2. Analyze the average electric range by manufacturer and model year.

3. Break down EV types: Battery Electric Vehicles (BEVs) vs Plug-in Hybrid Electric Vehicles (PHEVs).

4.Discover the most common EV manufacturers and models.

5. Segment data by Clean Alternative Fuel Vehicle (CAFV) eligibility.

6. Visualize KPIs such as total number of EVs, average electric range, and adoption trend over time.

Dataset Description
The primary dataset was sourced from state EV registration data and contains the following fields:

Column Name	Description
VIN (1–10)	Unique Vehicle Identifier
County, City, State, Zip	Geographical details
Model Year	Year of manufacture
Make, Model	Manufacturer and model
Electric Vehicle Type	BEV or PHEV
CAFV Eligibility	Clean fuel compliance status
Electric Range	Max range in miles on electric
Base MSRP	Manufacturer suggested retail price
Legislative District	District representation
Electric Utility	Electricity provider
Vehicle Location (Geo-coordinates)	Used for mapping
2020 Census Tract	Demographic segmentation
🔧 Data Preparation
Structured Tables were created using Excel’s Table feature (CTRL + T) for referencing across dashboards.

Used PivotTables & PivotCharts to extract segmented insights.

Cleaned and standardized data types, especially for zip codes, vehicle types, and manufacturer names.

Grouped and summarized data using Excel functions such as COUNTIF, AVERAGEIFS, and structured references.

📈 Dashboard Highlights
KPI Cards: Display total number of EVs and average electric range.

State-wise Map View: Highlights adoption rates, with WA, CA, and VA leading in registrations.

Model Year Analysis: Shows the growing adoption of EVs post-2017.

Top Manufacturers: Tesla, Chevrolet, Nissan, and BMW lead the market.

Electric Range by Manufacturer: Jaguar and Tesla have the highest average ranges.

CAFV Eligibility Breakdown: Majority of vehicles are eligible for clean alternative fuel benefits.

📌 Key Insights
Top States: Washington (WA) has the highest count of EVs at 114,000+.

Top EV Type: Battery Electric Vehicles (BEVs) make up over 76% of the dataset.

CAFV Eligibility: 50%+ vehicles are certified as clean fuel eligible.

Model Trends: Tesla Model 3 and Model Y dominate with consistently high range and registration count.

Range Leaders: Jaguar leads average electric range at over 200 miles.

✅ Recommendations
Policy Makers: Focus on infrastructure support in high-adoption areas like WA and CA.

Manufacturers: Increase availability of high-range, CAFV-eligible models in emerging states.

Marketers: Target campaigns toward eco-conscious consumers in top-performing regions.

Energy Providers: Strategize partnerships in districts with high EV counts.

📁 Files Included
Electric Vehicle Analysis.xlsx: Full dashboard with slicers and interactive visualizations.

README.md: Project summary and insights (this file).

