# Adventure Works Sales Dashboard

This repository contains a Power BI project analyzing sales performance, customer demographics, and product trends for the Adventure Works dataset.

## Project Overview
The goal of this dashboard is to provide interactive business intelligence reporting, highlighting key performance indicators (KPIs) to drive strategic decision-making. The project utilizes a robust architecture and custom calculations to surface actionable data insights.

## Technical Details
* **Tooling:** Built using Power BI Desktop, utilizing the Power BI Project (.pbip) format for text-based version control.
* **Data Modeling:** Features a fully realized dimensional model (star schema) designed for optimized query performance.
* **Calculations:** Employs advanced DAX formulas for dynamic aggregations, time intelligence, and customized KPI cards.
* **Visualizations:** Incorporates customized data labels, specialized pie chart configurations, and custom visual themes to match organizational branding.

## Repository Contents
* `/Adventure Works.Report/` - Contains the visual layout, custom theme JSON files, and rendering configurations.
* `/Adventure Works.Semantic Model/` - Contains the metadata defining the schema, relationships, and DAX measures.
* `.gitignore` - Prevents large binary cache files from being tracked in version control.

## How to Run Locally
1. Clone this repository to your local machine.
2. Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed with the "Power BI Project (.pbip) save option" enabled in Preview Features.
3. Open the `Adventure Works.pbip` file in Power BI Desktop to interact with the dashboard and explore the underlying semantic model.
