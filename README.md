# Bike Sales Analysis

## Table Of Content

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendation](#recommendation)
- [References](#references)


### Project Overview
This project is to help us analyze sales trends by gender, age bracket and commute distance thereby tracking the sales progress, gathering insight to make informed decision

### Data Source

The dataset used fot this analysis is a csv file from Kaggle

### Tools
- Microsoft Excel
  - data cleaning
  - data visualization

### Data Cleaning and Preparation

I performed the following task
- data loading and inspection
- Duplicated the original dataset in a separate sheet for safety
- Observed and cleaned the dataset thoroughly
- Romoved duplicates (26 rows)
- Used Find and Replace to change the abbreviated M/S and M/F in the marital status and gender columns respectively to Married/Single and Male/Female
- Categorized age data into age brackets using Excel's IF function (=IF(L979>54,"Old",IF(L979>=31,"Middle Age",IF(L979<31,"Adolescent","Invalid"))))

### Exploratory Data Analysis

I explored the dataset to answer the following questions
1 How does average income influence bike purchase behavior?
2 Is there a significant income disparity between genders, and how does it affect bike buying patterns?
3 Does commute distance correlate with the likelihood of purchasing a bike?
4 Which age group has the highest rate of bike purchases?
5 Are certain demographic groups (e.g., age, gender, income) more likely to buy bikes than others?

### Data Analysis

- Used Excel's IF to categorized the age bracket
- Used Pivot table to organize and analyze the data
- Used the Excel Chart to Visualize my analysis
- Analyzed average income by gender and bike purchase status
- Assessed the influence of commute distance on purchase likelihood
- Identified the most common age group for bike buyers.

### Findings 

1. Carried out an exploratory data analysis on bike purchase behavior, uncovering that individuals with higher average incomes were more likely to buy bikes.
   - Using pivot tables, I identified a gender-based income disparity, with males earning more on average and accounting for a higher rate of bike purchases _ this means income is a strong predictor of buying bike.
2. Used pivot tables and data visualizations to analyze the impact of commute distance on bike purchases, revealing that shorter commutes were linked to higher purchase rates
3. Identified the 31–54 age bracket group as the most active bike buyers through age-based segmentation analysis.

### Recommendation 

- Focus marketing campaigns on higher-income individuals, particularly professionals in the 31–54 age bracket, as they are the most likely to purchase bikes.
- Design income-sensitive pricing strategies or financing options to encourage purchases among lower-income groups, potentially increasing market penetration.
- Target urban and suburban areas with shorter average commute distances, as these regions show a stronger likelihood of bike purchases.
- Address gender disparities by tailoring marketing and product offerings (e.g., design, messaging) to better appeal to female customers and promote inclusivity.
- Develop campaigns that highlight the benefits of biking for short commutes, leveraging environmental, cost-saving, and health angles to attract potential buyers regardless of income.

### Limitations

Nil

### References 

Leveraging 
- pivot tables
- dynamic charts
- interactive slicers
  
the analysis delivers a comprehensive and actionable data visualization experience


