# Rural Land Feasibility Analysis

## Overview

This project analyzes rural U.S. land options using a structured scoring framework. The goal was to compare possible regions based on affordability, environmental risk, build feasibility, development pressure, and access.

## Objective

Identify rural areas that best match a long-term land acquisition and build plan using measurable criteria instead of relying only on personal preference or listing prices.

## Tools Used

* Python
* JupyterLab
* pandas
* Excel
* Data cleaning
* Multi-source comparison
* Weighted scoring

## Data Sources

This project uses information collected from public and research-based sources, including:

* FEMA flood risk information
* USGS seismic risk information
* USDA soil/building suitability information
* U.S. Census population and development trend information
* Public land listing research

## Analysis Criteria

Regions were compared across several criteria:

* Land cost per acre
* Flood risk
* Seismic risk
* Soil/building feasibility
* Road access
* Development pressure
* Estimated build and setup costs

## Method

1. Collected region-level data from multiple public sources.
2. Organized the data in Excel for comparison and cost modeling.
3. Loaded the Excel data into Python using pandas.
4. Compared candidate regions using a scoring framework.
5. Reviewed estimated land and build costs to evaluate overall feasibility.

## Key Findings

* Aroostook County, Maine ranked highly due to low land cost, low seismic risk, favorable soil/building indicators, and low development pressure.
* Some areas with cheap land had weaker scores because of access, risk, or development concerns.
* A structured scoring model made the comparison more objective and easier to explain.

## Files

* `rural_land_feasibility_analysis.ipynb` — Jupyter notebook containing the analysis
* `land_.xlsx` — Excel file containing the comparison data and cost model

## Note

This project is a personal data analysis project and is intended to demonstrate data cleaning, research organization, multi-source comparison, and analytical decision-making using Python and Excel.

