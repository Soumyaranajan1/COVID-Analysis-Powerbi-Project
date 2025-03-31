# Power BI COVID-19 Analysis Project

## Project Overview
This Power BI project provides an interactive dashboard for analyzing COVID-19 data. The report consists of three pages:

1. **Index** - Navigation page to access different sections.
2. **COVID Analysis** - Includes various visualizations such as slicers, pie charts, and combo charts for detailed insights.
3. **Bookmark** - A detailed breakdown of COVID-19 data with interactive features.

## Features
- **Index Page**: Serves as the main menu, allowing navigation to other pages.
- **COVID Analysis Page**:
  - 5 card visuals displaying key COVID-19 statistics.
  - 2 slicers for filtering by country/region and continent.
  - Pie chart showing total cases, total deaths, and total recovered.
  - Column chart with drill-down functionality (continent → country/region) based on total cases.
  - Combo chart comparing active cases and total tests (top 10 countries with highest deaths).
  - Drill-through functionality to the Bookmark page.
- **Bookmark Page**:
  - Table visual displaying country-wise data: population, total tests, total cases, total recovered, and total deaths.
  - Bar chart displaying population by country with a toggle button to switch data labels on and off.

## Requirements
- Power BI Desktop
- COVID-19 dataset (preloaded in the report)

## How to Use
1. Open the `.pbix` file in Power BI Desktop.
2. Navigate through the Index page to access different sections.
3. Use slicers and drill-down features for deeper analysis.
4. Utilize the Bookmark toggle for enhanced visualization control.

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/PowerBI-COVID-Analysis.git
   ```
2. Open the `.pbix` file in Power BI Desktop.

## License
This project is open-source and available for personal and educational use.

