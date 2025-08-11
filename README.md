
# Project Title

# Power BI Dashboard – Crop Production Dashboard
Purpose
This Power BI dashboard provides an interactive and visual overview of crop production statistics across different states and districts in India. It helps identify production patterns, top-performing crops, and seasonal trends.

## Key Metrics
Count of Crop: 242.36K – Total number of crop entries recorded.

Sum of Yield: 10M – Total crop yield produced.

Avg of Area: 12.17K – Average cultivation area across entries.

Avg of Production: 582.50K – Average production per crop record.

## Main Visuals
State vs Production (Bar Chart)

Shows total production by state.

Helps identify high and low production states.

Map View (State & District level)

Displays crop distribution geographically.

Allows drill-down to district-level details.

Top 5 Crops by States (Horizontal Bar Chart)

Lists states with highest crop performance in percentage.

Season-wise Crop Count & Yield (Combo Chart)

Compares crop count and total yield across seasons like Kharif, Rabi, Summer, Winter, Autumn.

## Usage
Use filters to select specific states, districts, crops, or years.

Hover over visuals for detailed tooltips.

Drill through to district-level data for deeper insights.

## Excel Dashboard
![image_alt](https://github.com/Hema-Kumari/Crop-Production-Analysis/blob/5cb881cb0df7abaca2f926e62cc566b8714ebfac/Screenshot%202025-08-11%20142300.png)
# This Excel dashboard

## Key Features
Interactive Slicers for:

Crop Year

District Name

State Name

Crop Type

## Visuals Included:

Total Crop Production (Column Chart) – State-wise production totals.

Pie Chart – Distribution of production share among states.

Horizontal Bar Chart by Year – Year-on-year crop production trends.

## Usage
Click slicers to filter the visuals instantly.

Compare crop production across multiple years or states.

Combine filters to analyze specific crops in particular regions.

## Final Dashboard
![image_alt](https://github.com/Hema-Kumari/Crop-Production-Analysis/blob/5cb881cb0df7abaca2f926e62cc566b8714ebfac/Screenshot%202025-08-11%20142225.png)

# 📊 Python Dashboard – Crop Production Analysis
Purpose
This Python dashboard provides an interactive and visual representation of crop production data using libraries such as Pandas, Plotly, and/or Dash/Streamlit. It enables data exploration, trend analysis, and performance comparison across crops, states, and years.

## Features
Data Loading & Cleaning

Reads raw crop production data (CSV/Excel).

Handles missing values, duplicates, and inconsistent formats.

Converts data types for proper calculations (e.g., numeric yield, date formats).

Key Metrics Displayed

Total Crop Count – Total number of crop records.

Total Yield – Overall yield produced.

Average Area – Average cultivation area per record.

Average Production – Average production value across entries.

## Interactive Visuals

State vs Production – Bar chart comparing production volumes across states.

Year-wise Trends – Line or bar charts showing production growth/decline over years.

Seasonal Analysis – Breakdown of production by Kharif, Rabi, Summer, Winter, etc.

Top Crops – Ranking crops based on yield or production.

## User Controls

Dropdowns / Filters for selecting:

Crop Type

State

Year

Season

Real-time updates of charts based on selected filters.

## Workflow
Import Libraries
(pandas, numpy, plotly.express, dash/streamlit)

Load Dataset

Read from .csv or .xlsx.

Data Cleaning & Transformation

Handle missing values.

Convert data types.

Aggregate data for analysis.

Create Visualizations

Generate bar charts, line graphs, pie charts, maps.

Deploy Dashboard

Run locally or host via Streamlit/Dash for web access.

## Usage Instructions
Install required libraries:

bash
Copy
Edit
pip install pandas numpy plotly streamlit
Place dataset in the project folder.

Run the script/notebook:

bash
Copy
Edit
streamlit run app.py
Use sidebar filters to explore data interactively.
