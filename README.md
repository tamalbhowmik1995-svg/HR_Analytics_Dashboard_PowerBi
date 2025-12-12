Human Resources Attrition Analysis Dashboard (Power BI)

## Project Overview

This Power BI dashboard provides a comprehensive analysis of employee attrition within the company. The goal of this report is to empower HR management and department heads to identify key drivers of turnover, understand demographic trends of departing employees, and ultimately inform strategic initiatives to improve employee retention and satisfaction.

## Dashboard Key Metrics

The report focuses on these primary Key Performance Indicators (KPIs):

*   **Attrition Rate:** The percentage of employees who left the company over the last 12 months (TTM).
*   **Total Headcount:** Current number of active employees.
*   **Voluntary Turnover:** The percentage of employees who chose to leave the organization.
*   **Average Tenure:** Average length of employment for current and past employees.

## Key Insights & Visualizations

The report utilizes several visualizations to segment data and uncover patterns:

Use code with caution.

Visualization	Description	Key Insight Provided
Attrition by Department (Bar Chart)	Compares turnover rates across different business units.	Identifies which departments require immediate attention/intervention (e.g., Sales, Customer Support).
Attrition by Age Group (Pie Chart/Donut Chart)	Highlights demographics with the highest flight risk.	Reveals if younger employees (25-34 age bracket) are leaving more frequently than older staff.
Attrition by Salary Bracket (Bar Chart)	Correlates compensation levels with turnover.	Determines if low-paid roles have disproportionately high attrition rates.
Monthly Attrition Trend (Line Chart)	Tracks separations over time.	Highlights seasonal trends or the impact of specific company events/policy changes on retention.
Data Sources
The report draws data from the following sources:
HR_Employee_Dataset.csv: Contains core employee master data (department, role, salary, age, tenure).
Separation_Log.xlsx: Contains dates and classified reasons for employee departures (Voluntary/Involuntary).
Note: Data should be refreshed monthly via the Power BI Service gateway.
How to Use the Dashboard
Slicers and Filters
Use the interactive filters on the right-hand side or top navigation bar to slice the data:
Date Range: Select a specific quarter or fiscal year.
Department: Filter insights for a specific business unit (e.g., "Engineering").
Manager Name: Review performance data specific to a team leader.
Drill-Down
Right-click on any data point (e.g., a specific bar on a chart) to use the Drill Through feature to see underlying employee-level details relevant to that data point.
