# Under-Five Child Nutrition Analysis Dashboard Report– Power Bi Project

## Table of Contents

[Project Summary](#project-summary)

[Project Objectives](#project-objectives)

[Under-Five Child Nutrition Dataset](#under-five-child-nutrition-dataset)

[KPI Questions](#kpi-questions)

[Dataset Description](#dataset-description)

[Process](#process)

[Dashboard Pages Summary](#dashboard-pages-summary)

[Insights Implied by the Objectives](#insights-implied-by-the-objectives)

[Recommended Actions](#recommended-actions)

[Tools Used](#tools-used)

[Conclusion](#conclusion)

[Dashboard](#dashboard)

## Project Summary

Child malnutrition remains a critical public health challenge, particularly among children under the age of five. This project presents an interactive Power BI dashboard that analyzes nutritional outcomes using data from 4,098 children under five, integrating anthropometric measurements, health indicators, socioeconomic conditions, and geographic factors. The dashboard supports NGOs and policymakers with actionable insights for targeted nutrition interventions.

## Project Objectives

To;

- Assess overall nutritional status of children under five
- Identify prevalence of malnutrition and nutrition risk
- Examine health-related factors influencing malnutrition
- Analyze socioeconomic drivers of poor nutrition outcomes
- Highlight regional disparities
- Identify high-risk groups for intervention
- Support data-driven planning and policy decisions

## Dataset Used

<a href="https://github.com/Excel-sis/Child-Malnutrition-Powerbi-Dashboard/blob/main/malnutrition_children_ethiopia.xlsx">PowerBi Data</a>

## KPI Questions

The Key Performance Indicators were designed to answer the following questions;

1.What is the total number of children assessed?
2.What proportion of children under five are malnourished?
3.How many children are currently at nutritional risk?
4.What percentage of children have normal nutritional status?
5.How many children are suffering from anemia?

## Dataset Description

The dataset includes anthropometric measures (height, weight), health indicators (anemia, diarrhea, TB), socioeconomic variables (wealth index, maternal education), region, and nutrition status classified as Normal, At Risk, or Malnourished.


## Process

The following steps were carried out to build the report:

**1.	Data Preparation**
   
    - Data loading
    - Imported raw data into Power Bi Desktop
    - Confirmed data structure and inspected column types 

**2. Data Cleaning & Transformation (Power Query)**

    - Removed blank rows and columns
    - Converted age from months to years
    - Standardized categories
    - Created DAX measures and KPIs

**3.	Data Modelling**

Created calculated columns and DAX measures for;

    - Total Children
    - % At Risk
    - % Normal
    - % Malnourished
    - % High Risk
    - % Combined Risk
    - High Risk Children
    - Vulnerability Score
    - Priority Level

**4.	Visualization**

    - Designed a clean, NGO-Standard and user- friendly dashboard
    - Included slicers for gender and level of maternal education to enable dynamic analysis
    - Added KPI cards for quick review
    - Used column charts, bar charts, pie charts, donut chart, matrix, tables, filled map and text boxes.

**5.	Formatting & Branding**

    - Applied a consistent theme for visual clarity.
    - Used layout alignment, colors and icons to enhance readability.

## Dashboard Pages Summary

**Page 1: Nutrition Overview**

Provides a high-level snapshot of nutrition outcomes, showing proportions of normal, at-risk, and malnourished children.

**Page 2: Health Factors**

Analyzes the role of anemia, diarrhea, and TB in increasing malnutrition risk.

**Page 3: Socioeconomic Drivers**

Examines the impact of household wealth and maternal education on nutrition outcomes.

**Page 4: Regional Disparities**

Highlights geographic inequalities and identifies high-priority regions.

**Page 5: Risk & Action**

Identifies high-risk groups and translates insights into recommended actions.

## Insights Implied by the Objectives

Based on the objectives, the study revealed that:

  - A significant proportion of children are either malnourished or at risk.
  - Lower height and weight are strongly associated with malnutrition.
  - Children with anemia, diarrhea, or TB have worse nutrition outcomes.
  - Poverty and low maternal education significantly increase malnutrition risk.
  - Certain regions carry a disproportionate burden of malnutrition.
  - A combination of health and socioeconomic disadvantages greatly increases vulnerability.
  
## Recommended Actions

  - Prioritize malnourished and at-risk children
  - Focus interventions in high-burden regions
  - Integrate nutrition and health services
  - Strengthen social protection for vulnerable households
  - Promote maternal education and awareness
  - Use dashboard insights for monitoring and decision-making

## Tools Used

Power BI, Power Query, Excel

## Conclusion

The project demonstrates the value of data-driven dashboards in understanding and addressing child malnutrition. It supports targeted interventions, efficient resource allocation, and evidence-based policy formulation.

## Dashboard

![Nutrition_Overview](https://github.com/Excel-sis/Child-Malnutrition-Powerbi-Dashboard/blob/main/Nutrition_Overview.png)

![Health_Factors](https://github.com/Excel-sis/Child-Malnutrition-Powerbi-Dashboard/blob/main/Health_Factors.png)

![SocioEconomic_Drivers](https://github.com/Excel-sis/Child-Malnutrition-Powerbi-Dashboard/blob/main/SocioEconomic_Drivers.png)

![Regional_Disparities](https://github.com/Excel-sis/Child-Malnutrition-Powerbi-Dashboard/blob/main/Regional_Disparities.png)

![Risk & Action](https://github.com/Excel-sis/Child-Malnutrition-Powerbi-Dashboard/blob/main/Risk%20%26%20Action.png)







