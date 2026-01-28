# Global Disaster Response Analysis (2018–2024)

This project analyzes global disaster events and their response effectiveness from 2018 to 2024. It combines an event-level dataset with summary visualizations to explore patterns in economic loss, response performance, disaster type distribution, and geographic spread.

## Overview

- Dataset: [global_disaster_response_2018_2024 (1) (3).csv] with 430+ disaster records.
- Time range: 2018–2024.
- Scope: Multiple countries and disaster types (e.g., earthquakes, hurricanes, floods, extreme heat, wildfires, volcanic eruptions, landslides, droughts, storm surges, tornadoes).
- Goal: Understand how disasters vary by type, location, and severity, and how response time, aid, and efficiency are related to impact.

## Dataset

The main file is [global_disaster_response_2018_2024 (1) (3).csv], with the following columns:

- date
- country
- disaster_type
- severity_index
- casualties
- economic_loss_usd
- response_time_hours
- aid_amount_usd
- response_efficiency_score
- recovery_days
- latitude
- longitude

Each row represents one disaster event.

## Visualizations

This repo includes four key charts:

### 1) Top 10 Countries by Total Economic Loss (2018–2024) – Bar Chart  
- [1_BarChart_EconomicLoss.png]
- Shows the 10 countries with the highest total economic losses (USD).  
- Ordered from highest to lowest loss (e.g., Brazil, Bangladesh, South Africa, etc.).  
- Useful for identifying which countries bear the greatest financial burden from disasters.

### 2) Response Time vs. Efficiency Score – Scatter Plot  
- [2_ScatterPlot_ResponseVsEfficiency.png] 
- X-axis: `response_time_hours`  
- Y-axis: `response_efficiency_score`  
- Points represent individual events.  
- Color indicates disaster type; size indicates severity.  
- Visualizes the relationship between how quickly a response begins and how efficient the response is rated.

### 3) Global Distribution of Disaster Types (2018–2024) – Pie Chart  
- [3_PieChart_DisasterTypes.png]
- Shows the share of each disaster type worldwide.  
- Includes tornadoes, wildfires, volcanic eruptions, storm surges, extreme heat, hurricanes, floods, earthquakes, landslides, and droughts.  
- Distribution is relatively balanced, with each disaster type around 9.9–10.3%.

### 4) Geographic Distribution of Disasters – Map  
- [4_Map_GeoDistribution.png] 
- Plots each disaster using latitude and longitude.  
- Circle size and color represent the severity index (1–10).  
- Provides a spatial view of where disasters occur and how severe they are.

## Example Questions You Can Explore

Using this dataset and charts, you can investigate questions such as:

- Which countries experienced the highest economic losses and casualties?
- How is response time related to response efficiency across different disaster types?
- Do some disaster types tend to have faster or more efficient responses than others?
- How is severity correlated with casualties, economic loss, and recovery days?
- Which regions (by latitude/longitude or country) face the most frequent or severe disasters?

## Potential Use Cases

- Research and coursework on disaster risk, climate impact, and response effectiveness.
- Policy or preparedness planning at national or regional levels.
- dashboards and data stories about global disaster trends.
- Demonstrating data analysis and visualization skills in a portfolio.

## Project Structure

- /data  
  - global_disaster_response_2018_2024.csv
- /notebooks or /scripts  
  - DISASTER PROJECT.zip
- /figures  
  - 1_BarChart_EconomicLoss.png  
  - 2_ScatterPlot_ResponseVsEfficiency.png  
  - 3_PieChart_DisasterTypes.png  
  - 4_Map_GeoDistribution.png
- README.md  


> Note: This dataset is designed for educational and practice purposes only and does not represent official disaster records.
