
· Climate Change Impact Dashboard (Global Metrics, 1960–Present)

•	Problem Statement
· Understanding climate change impacts requires interactive visual analysis of long-term temperature, emissions, and sea-level data. Static reports lack the ability to reveal geographic patterns, temporal trends, and country-level comparisons. This Tableau solution integrates global climate datasets to deliver actionable insights for researchers, policymakers, and the public.

•	Objectives
· Visualize global average temperature rise since 1960
· Illustrate CO₂ emissions by country and region over time
· Track historical sea-level changes and project trend lines
· Compare emission densities across continents
· Enable interactive filtering by year, country, and metric
· Provide a publishable Tableau workbook for stakeholder engagement
•	Key Performance Indicators & Features
· Global temperature anomaly (°C) relative to 1960 baseline
· Cumulative CO₂ emissions by country and region
· Sea-level rise rate (mm/year) and cumulative increase
· Top five CO₂-emitting countries’ share of global emissions
· Emission density map showing per-capita and per-area metrics
· Decadal trend line charts and heatmaps
· Interactive geographic map with drill-down

· Dynamic filters for year range, metric, and country groupings
1.	Tools & Technologies
1.	Tableau Desktop/Public for dashboard development
2.	Global climate CSV datasets (temperature, emissions, sea level)
3.	Calculated fields for anomaly and growth rate computations
4.	Filters and parameters for interactive analysis
5.	Geographic mapping for choropleth and point visualizations
6.	Trend lines and forecast models for projection analysis
7.	Presentation mode and Tableau Public publishing

2.	Repository Contents
1.	Climate_Change_Impact_Dashboard.twbx — Tableau workbook
2.	global_climate_data.csv — Combined dataset
3.	README.md — Project documentation
4.	assets/screenshot_overview.png — Dashboard preview
5.	assets/data_dictionary.pdf — Field definitions

3.	Data Overview
1.	File: global_climate_data.csv (NOAA, NASA, IPCC)
2.	Metrics: Year, Country, Avg_Temperature, CO₂_Emissions, Sea_Level
3.	Processing: Cleaned and merged in Excel; formatted for Tableau
   
5.	Calculated Fields:
· Temperature_Anomaly = Avg_Temperature – baseline_1960
· Emissions_Share = CO₂_Emissions / Global_Total
· Sea_Level_Rate = (Sea_Level – Sea_Level_1960) / (Year – 1960)

4.	Key Insights Discovered
1.	Global average temperature has risen by 1.2 °C since 1960
2.	Top five emitting countries account for over 60% of global CO₂ emissions
3.	Sea levels are rising at 3.3 mm per year on average
4.	Asia and North America exhibit the highest emission densities
5.	Decadal heatmaps reveal accelerated warming in polar and equatorial regions
6.	Projections estimate an additional 0.8 °C rise by 2050 under current trends

5.	Strategic Recommendations
1.	Prioritize emission reduction in top emitting countries
2.	Enhance coastal resilience planning based on sea-level projections
3.	Invest in renewable energy in high-density regions
4.	Implement global temperature monitoring for early anomaly detection
5.	Publish dashboards for transparency and stakeholder engagement

6.	Dashboard Features & Navigation
1.	Overview Page: Summary KPIs and trend lines
2.	Temperature Analysis: Line charts and anomaly heatmaps
3.	Emissions Page: Bar charts, rankings, and density maps
4.	Sea-Level Page: Time series and projections
5.	Comparison Tools: Dual-axis cross-metric charts
6.	Interactive Filters: Year slider, country selector, metric toggle

7.	Usage Instructions
1.	Prerequisites: Tableau Desktop/Public installed
2.	Open Climate_Change_Impact_Dashboard.twbx in Tableau
3.	Ensure global_climate_data.csv is accessible
4.	Refresh data source to load the latest records
5.	Use filters to select years, countries, and metrics
6.	Hover and click visuals for tooltips and drill-downs
7.	Export views or publish to Tableau Public

