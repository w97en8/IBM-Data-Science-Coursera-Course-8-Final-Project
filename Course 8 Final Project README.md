# IBM-Data-Science-Coursera-Course-8-Final-Project
This is the final project in course 8 of the IBM Data Science Course on Coursera. In this project, we take on the role of a data scientist working at XYZAutomotives. The goal is to examine historical data and to provide the company with a comprehensive analysis on how automobile sales are impacted during recession periods. The historical data includes automobile sale information from the years 1980-2020.

The dataset includes the following variables which will be used for the analysis portion of this lab: 
1. Date: The date of the observation.
2. Recession: A binary variable indicating recession perion; 1 means it was recession, 0 means it was normal.
3. Automobile_Sales: The number of vehicles sold during the period.
4. GDP: The per capita GDP value in USD.
5. Unemployment_Rate: The monthly unemployment rate.
6. Consumer_Confidence: A synthetic index representing consumer confidence, which can impact consumer spending and automobile purchases.
7. Seasonality_Weight: The weight representing the seasonality effect on automobile sales during the period.
8. Price: The average vehicle price during the period.
9. Advertising_Expenditure: The advertising expenditure of the company.
10. Vehicle_Type: The type of vehicles sold; Supperminicar, Smallfamiliycar, Mediumfamilycar, Executivecar, Sports.
11. Competition: The measure of competition in the market, such as the number of competitors or market share of major manufacturers.
12. Month: Month of the observation extracted from Date.
13. Year: Year of the observation extracted from Date.

This project is split into two parts:
- Part 1: Data visualization with Matplotlib, Seaborn, & Folium
- Part 2: Use Plotly and Dash to create a dashboard of the data from 1980-2020

The following skillset/criteria is covered in each part of the project:
1. Develop line chart using pandas to illustrate yearly fluctuation in automobile sales
2. Plot different lines for each vehicle type and analyze whether there is a significant difference between different vehicle types during recession periods
3. Seaborn to create visualizations to compare automobile sales for each vehicle type in recession vs. non-recession periods
4. Subplotting to compare GDP variation in recession vs. non-recession periods
5. Bubble plots to see if seasonality has any effect on automobile sales
6. Create scatter plots using Matplotlib to see if there is a correlation between average vehicle price and whether that has any relation to the sales volume during recession periods
7. Create a pie chart to visualize advertising expenditure for each vehicle type of the company during recession vs. non-recession periods
8. Create line plot to analyze effect of unemployment rate on vehicle type and thus automobile sales during recession periods
Dashboard (PART 2)
9. Create a Dash application with drop-down menus
10. Add divisions for output display
11. Create callbacks and update the input container based on selected statistics and output container
12. Create and display graphs for recession report and yearly report statistics
