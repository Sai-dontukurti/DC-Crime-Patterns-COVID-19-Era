# DC Crime Patterns: COVID-19 Era and Proximity Insights

This project explores changes in crime patterns in Washington, DC, throughout the COVID-19 pandemic, examining spatial and temporal crime data to identify trends and insights. Using advanced GIS tools and Python, the project analyzes the proximity of crime incidents to urban infrastructures, with a goal to inform public safety and urban planning strategies.

## Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Dataset Description](#dataset-description)
- [Data Engineering](#data-engineering)
- [Methodology](#methodology)
- [Analysis](#analysis)
- [Conclusion and Future Use Cases](#conclusion-and-future-use-cases)
- [Contributors](#contributors)
- [References](#references)

## Overview
The COVID-19 pandemic introduced significant socio-economic changes, directly influencing crime patterns in urban areas. This project utilizes geospatial analysis to understand shifts in crime dynamics across different periods (Pre-COVID, COVID, Post-COVID), focusing on proximity to urban features like schools and grocery stores. Insights from this analysis can help in adaptive public safety and resource allocation strategies.

## Objectives
1. **Impact of COVID-19 on Crime**: Compare and visualize crime incidents in Washington, DC, from 2019 to 2023, segmented into pre-COVID, COVID, and post-COVID periods.
2. **Crime Categorization**: Analyze four main categories of crime and trends over the specified periods.
3. **Proximity Analysis**: Examine crime occurrences within 300 feet of key urban features (schools, police stations, grocery stores) to understand spatial patterns.

## Dataset Description
- **Data Source**: Crime data from Open Data DC, provided by the Metropolitan Police Department (MPD).
- **Content**: Approximately 114,000 records, covering crime incidents from 2019 to 2023.
- **Key Attributes**: `CCN`, `REPORT_DATE`, `SHIFT`, `METHOD`, `OFFENSE`, `BLOCK`, `XBLOCK`, `YBLOCK`.
- **Additional Attributes**: Temporal segmentation by pre-COVID, COVID, and post-COVID periods for focused trend analysis.

## Data Engineering
1. **Data Consolidation**: Merged crime datasets from 2019 to 2023, creating a unified dataset for a comprehensive five-year analysis.
2. **Crime Categorization**: Simplified crime types into four main categories to enhance clarity in analysis.
3. **Temporal Feature Engineering**: Segmented data based on the 'REPORT_DATE' attribute into three phases: Before Pandemic, During Pandemic, and Post Pandemic.

## Methodology
### Crime Analysis
- **Interactive Tool**: Developed an interactive user tool for selecting time periods and crime categories.
- **Spatial Visualization**: Employed KDE plots in ArcGIS Pro to visualize crime concentration.

### Proximity Feature Analysis
- Calculated the proximity of crimes within 100m (300 feet) of critical urban locations, like schools and police stations.
- Used tables and graphs to highlight patterns in crime proximity, aiding in identifying hotspots and crime-prone areas.

## Analysis
- **Crime Type Trends**: Analyzed trends for specific crime categories (Theft, Property Crimes, Robbery, Violent Crimes) across different COVID periods.
- **Overall Crime Trends**: Observed general crime trends and shifts throughout the pandemic phases.
- **Proximity Analysis**: Found correlations between certain crime types and their proximity to urban features, highlighting potential crime hotspots.

## Conclusion and Future Use Cases
- **Impact of COVID-19**: Crime patterns exhibited distinct shifts during Pre-COVID, COVID, and Post-COVID periods, suggesting that socio-economic changes affect urban crime dynamics.
- **Crime Proximity**: Certain crime types occurred frequently near locations like liquor stores and parks, indicating these as potential hotspots.
- **Advancements in Crime Analysis**: GIS technologies and Python facilitated a detailed understanding of spatial crime patterns.

### Future Enhancements
- **Adaptability for Other Cities**: Methodologies can be adapted for comparative studies in different urban areas.
- **Integration with Urban Planning**: Insights can inform city design and public safety strategies.
- **Real-Time Data Analysis**: Future iterations could incorporate real-time data for timely insights.
- **Addition of Socio-Economic Data**: Including demographic information may provide a deeper understanding of underlying crime causes.

## Contributors
- Nammin Woo
- Sasank Reddy Chaganti
- Sai Narayana Murthy Dontukurti
- Abhishek Pradhan

## References
1. [Crime risk prediction incorporating geographical spatio-temporal dependency into machine learning models](https://doi.org/10.1016/j.ins.2023.119414)
2. [The use of predictive analysis in spatiotemporal crime forecasting](https://doi.org/10.1016/j.apgeog.2017.06.011)
3. [Open Data DC (2023)](https://opendata.dc.gov/search?collection=Dataset&q=crime)

Thank you for reviewing the **DC Crime Patterns: COVID-19 Era and Proximity Insights** project!
