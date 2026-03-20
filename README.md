# HR Analytics Power BI Project

## Project Overveiw
**Project Title**: HR Analytics
**Level**: Beginner
**Database**: p1_HR_db

This dashboard provides a comprehensive view of the organization’s headcount and demographics, utilizing Power BI's filtering capabilities to break down staff distribution by age, and tenure. It enables HR leaders to quickly assess the current state of the workforce and plan for future scaling or restructuring."

1.**Set up a HR Analytics Database**: Create and populate a HR Analytics database with the provided data.
2.**Data Cleaning**: Identify and remove any records with missing or null values.

## Project Structure
1.**Data Acquisition & Connection (The Source)**:

**Connection Method**: Use Import Mode for HR data to take advantage of high-performance DAX calculations, as HR datasets are typically small enough for memory.

2.**Power Query**: The ETL Layer (Extract, Transform, Load)

**Filtering**: Removed sensitive personal data (like specific home addresses) that isn't needed for analysis.

**Data Typing**: Ensured Hire Date is set to Date format.

3.**DAX Calculations (The Intelligence)**:

**Attrition Rate**: SUM(HR_Analytics[AttritionCount])/SUM(HR_Analytics[EmployeeCount])

4.**Report Interface & Visualization**:

**Executive Summary**: High-level KPIs (Total Headcount, Attrition %).

**Demographics & Diversity**: Visuals showing gender balance and age distribution.

## Findings

**Used Tooltips**: When a user hovers over a "Visuals" will show the specific attrition Count.

## Reports

**Trend Analysis**: "Visualizes changes in attrition rates, hiring growth, and monthly turnover patterns over time to identify seasonal workforce shifts and long-term stability".

**Employee Insights**: "A deep dive into individual demographics, performance ratings, and tenure levels to segment high-potential talent and address specific retention risks".

## Conclusion

"This project provides a comprehensive framework for workforce management, using interactive analytics to bridge the gap between raw HR data and strategic human capital optimization."



