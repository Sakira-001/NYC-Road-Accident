# NYC-Road-Accident

This project analyzes traffic collision data in New York City to identify trends, risk factors, and high-incident areas. By visualizing key metrics such as accident counts by borough, vehicle type, and fatality rates, this analysis provides insights to improve road safety and inform urban planning strategies.
---

## Table of Contents
1. [Overview](#overview)
2. [Raw Data](#raw-data)
3. [Dashboard & Dashboard Features](#dashboard-features)
4. [Data Cleaning Process](Data--cleaning--process&preprocessing)
5. [Key Metrics](#key-metrics)
6. [Insights & Conclusions](#insights--conclusions)
7. [Tools & Techniques Used](#tools--techniques-used)
8. [How to Use the Dashboard](#how-to-use-the-dashboard)
9. [Questions & Answers](#questions--answers)
10. [Conclusions]
11. [Author](#author)

---

## Overview
This interactive dashboard comprehensively analyses traffic collisions across New York City. It is designed to help stakeholders—such as city planners, transportation officials, safety advocates, and the general public—better understand collision patterns, identify high-risk areas, and support data-driven decisions to enhance road safety.

---

## Raw Data
The raw data for this dashboard includes a comprehensive dataset of employee details from a fictional company. It consists of the following fields:

1. **Collison ID**: A unique identifier for each collision record.
2. **Date**: The date on which the collision occurred.
3. **Time**: The specific time the collision happened.
4. **Borough**: The borough (e.g., Brooklyn, Queens, Bronx, etc.) where the collision occurred.
5. **Zip Code**: The zip code of the location where the accident took place.
6. **Latitude**: The latitude coordinate for the accident location.
7. **Longitude**: The longitude coordinate for the accident location.
8. **Street Name**: The primary street name where the accident occurred.
9. **Number of Persons Injured**: Total number of individuals injured in the accident.
10. **Number of Persons Killed**: Total number of individuals who died as a result of the accident.
11. **Number of Pedestrians Injured**: Number of injured individuals who were pedestrians.
12. **Number of Pedestrians Killed**: Number of pedestrians who died in the accident.
13. **Number of Cyclist Injured**: Number of injured individuals who were riding bicycles.
14. **Number of Cyclist Killed**: Number of cyclists who were killed.
15. **Number of Motorist Injured**: Number of motorists injured in the accident.
16. **Number of Motorist Killed**: Number of motorists who died in the accident.

---

### Data Cleaning Process in Power Query
- **Removed Duplicates**: Identified and removed duplicate rows based on Collision ID to ensure each collision record is unique.
- **Time Data Type**: Changed the time data type from Time & Date to Time only.
- **Null**: Chabged the Null values in the Borough, Steet Name and Contributing factor column to "Unknown or "Unspecified".
- **Find and Replace**: Used the Find and Replace to reduce the contents "Vehicle" and "Contributing Factors" columns.

---

## Dashboard Features
- **Interactive Filters**: Users can slice and explore the data by borough, vehicle type, contributing factors, month, and injury/fatality type for flexible, in-depth analysis.
- **Visualizations**: The dashboard incorporates bar charts, pie charts, stacked columns, and heat maps to clearly display accident trends, contributing causes, and spatial distribution.
- **Custom Groupings**: Vehicle types and contributing factors were grouped into meaningful categories (e.g., Passenger, Commercial, Unknown) to simplify interpretation.
- **Time-Based Analysis**: Monthly and hourly trend graphs allow users to detect seasonal patterns and peak collision times.
- **Highlight Cards (KPIs)**: Summary cards show total collisions, injuries, and fatalities, providing an instant snapshot of the overall impact.
- **User-Centric Design**: Custom color schemes, consistent font styles, and intuitive slicer layouts were applied to ensure clarity, readability, and visual appeal.
- **Responsive Insights**: All charts dynamically update based on selected filters, helping users draw targeted conclusions based on specific scenarios.

![NYC_ROAD_ACCIDENT_DASHBOARD]("")

---

## Key Metrics
1. **Total Reported Collisions**: 91,286
2. **Total Injuries**: 45,317
   - Persons Injured: 37,198
   - Pedestrians Injured: 4,211
   - Cyclists Injured: 1,932
   - Motorists Injured: 1,976
3. **Total Fatalities**: 276
   - Persons Killed: 213
   - Pedestrians Killed: 39
   - Cyclists Killed: 12
   - Motorists Killed: 12
4. **Borough with Most Collisions**: Brooklyn
5. **Most Common Contributing Factor**: Driver Inattention/Distraction
6. **Peak Collision Hours**: Between 3 PM – 6 PM
7. **Collisions by Vehicle Type**:
   - Passenger Vehicles: 58%
   - Commercial Vehicles: 18%
   - Two-Wheelers (Motorcycles, Bicycles): 9%
   - Emergency Services: 3%
   - Others: 6%
   - Unknown/Not Reported: 6%
8. **Seasonal Pattern**: Highest collisions recorded in October, lowest in February
9. **Most Affected Demographic**: Motorists and pedestrians injured in Brooklyn and Queens
10. **Location Hotspots**: Most incidents occurred in densely populated areas with high traffic volume

---

## Insights & Conclusions
1. **Attrition Trends**:
   - Employees with Bachelor's degrees face the highest attrition (99 employees).
   - Job roles like "Sales Executive" are particularly prone to attrition.

2. **Demographics**:
   - The majority of employees are female (882 out of 1,470).
   - Most employees fall within the 25-34 age group, indicating a younger workforce.

3. **Department Analysis**:
   - The HR department has the lowest attrition rate.
   - R&D experiences moderate attrition, while Sales have the highest attrition rate.

4. **Job Satisfaction**:
   - With a 2.6-star rating, there is significant room for improvement in employee satisfaction.

5. **Marital Status**:
   - Single employees show the highest attrition (470 employees), followed by married ones (473).

6. **Education Field**:
   - Employees from technical and marketing backgrounds exhibit varying attrition rates.

---

## Tools & Techniques Used
1. **Microsoft Excel**:
   - **Pivot Tables** for data summarization.
   - **Charts** for visual representation of insights.
   - **Slicers** for interactive filtering.
2. **Microsoft Powerpoint**: for creating visual dashboard
3. **Formatting & Styling**:
   - Custom slicer styles and chart designs.
   - Adjustments to align and group dashboard elements for a professional layout.
4. **Data Editing**:
   - Cleaned and structured raw HR data to ensure accuracy.
5. **Paint**: For dashboard screenshot edit.

---

## How to Use the Dashboard
1. **Filter Data**:
   - Use slicers on the right to filter data by department, job roles, or education field.
2. **Analyze Metrics**:
   - View key statistics and graphs to identify patterns and trends.
3. **Draw Insights**:
   - Utilize visualizations to make informed HR decisions.

---

## Questions & Answers
### Q1: What type of data was used to create this dashboard?
**A**: The dashboard is based on raw HR data containing employee demographics, job roles, education, and attrition details.

### Q2: How can I filter data by department?
**Ans**: Click on the department slicer and select the desired department(s). The dashboard will automatically update.

### Q3: What does the attrition rate indicate?
**Ans**: The attrition rate (16.12%) shows the percentage of employees who left the company out of the total workforce.

### Q4: How was the average age calculated?
**Ans**: The average age was calculated using a simple arithmetic mean formula in Excel.

### Q5: Can I update the dashboard with new data?
**Ans**: Yes, replace the data in the source table and refresh all pivot tables to update the dashboard.

---

## Author
This project was created by [Bakare Sukurat Aderonke], a data analyst with expertise in creating Insightful dashboards and performing data analysis using tools like Excel, SQL,Python and Power-BI. I am passionate about uncovering trends and delivering actionable insights accross various domains. For more information, feel free to connect with me on LinkedIn. [www.linkedin.com/in/bakare-aderonke-5214712b2].

---

## Conclusion
The HR Analytics Dashboard provides actionable insights into workforce composition, attrition, and job satisfaction. It serves as an effective tool for HR professionals to identify trends and implement strategies for workforce management.

