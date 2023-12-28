# Covid

## SQL Documentation

### Exploratory Data Analysis

- Initial queries fetch and display raw data from the 'deaths' and 'vaccination' tables.

### Creating `vaccine_death_rates` Table

- This code calculates average total vaccinations, death rates, and vaccination rates for each location.
- The resulting table, named 'vaccine_death_rates,' combines data from 'vaccination' and 'deaths' tables, excluding rows with missing data.

### Creating `vaccine_death_time` Table

- This code creates the 'vaccine_death_time' table by combining weekly vaccination and death data.
- It utilizes two Common Table Expressions (CTEs), 'WeeklyCases' and 'WeeklyDeaths,' and a LEFT JOIN to merge the data based on the weekly date.

### Creating `geography_summary` Table

- The SQL query analyzes COVID-19 impacts on different locations, generating the 'geography_summary' table.
- It combines population and vaccination data from 'vaccination' and total deaths from the 'deaths' table, ensuring a comprehensive overview.

### Creating `correlation_death_admin` Table

- This code investigates the correlation between average hospital admissions and deaths globally, creating the 'correlation_death_admin' table.
- It calculates weekly statistics using the 'deaths' table, providing insights into temporal patterns on a global scale.

These SQL queries collectively facilitate an in-depth analysis of COVID-19 data, covering aspects such as vaccination rates, death rates, weekly statistics, and geographical impacts.

## Tableau Dashboard Documentation

### Overview

This documentation outlines the design and functionality of a Tableau dashboard created to visualize key aspects of COVID-19 data. The dashboard aims to provide insights into global vaccination campaigns, death rates, and the relationship between deaths and hospital admissions.

### Visualizations

1. **Comparison of Death Rate and Vaccination Rate (Top 4 Nations)**
   - **Objective:** Explore and compare death rates and vaccination rates in the top 4 nations with the highest death rates.
   - **Visualization Type:** Clustered Bar chart.
   - **Insights:** Analyze the effectiveness of vaccination campaigns in mitigating death rates.

2. **Relationship between Deaths and Hospital Admissions**
   - **Objective:** Understand the correlation between deaths and hospital admissions globally.
   - **Visualization Type:** Scatter plot with a trendline.
   - **Insights:** Identify patterns and trends in the relationship between deaths and hospitalizations.

3. **Global Vaccine Campaign Map**
   - **Objective:** Visualize the progress of vaccine campaigns on a global scale.
   - **Visualization Type:** Interactive map.
   - **Insights:** Explore vaccination rates across different countries and regions.

4. **Global Deaths Occurrence Map**
   - **Objective:** Map the occurrence of deaths globally.
   - **Visualization Type:** Interactive map.
   - **Insights:** Identify geographical patterns and hotspots for targeted analysis.

### Dashboard Interactivity

- Users can interact with the dashboard to explore specific data points, filter information, and gain a comprehensive understanding of the global impact of COVID-19.
- The visualizations are designed to be intuitive, allowing users to hover over data points for detailed information and adjust filters for customized views.

### How to Use

1. **Accessing the Dashboard:**
   - Open the Tableau dashboard to explore the visualizations.
   - Use the provided filters to focus on specific regions, time periods, or data points.

2. **Interacting with Visualizations:**
   - Hover over data points to view detailed information.
   - Utilize filters to customize the dashboard based on specific criteria.

3. **Gaining Insights:**
   - Draw insights from the visualizations to understand global trends in vaccination campaigns, death rates, and the relationship between deaths and hospital admissions.

### Conclusion

This Tableau dashboard serves as a powerful tool for analyzing and interpreting COVID-19 data. By providing interactive visualizations, users can extract meaningful insights and contribute to a deeper understanding of the global impact of the pandemic.
