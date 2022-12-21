# DS102/DS104-Final-Project
**A simple project on data analysis and visualization

The prices of HDB flats is in the spotlight recently, after news of HDB flats being transacted at record prices and of more million dollar HDB flats being transacted. This draws into question on whether HDB flats are still currently affordable and what are the finances one must have in order to afford a HDB flat of their desired specifications. 

This project aims to visualize and provide insights into the following questions that potential buyers might have:

1. Are more resale flats being transacted and any general price trend which can be identified? 

2. What are the average prices of HDB flats in the different areas/towns of Singapore?

3. Which locations are the most and least desirable based on price?

4. Is there a correlation between floor area and price transacted? (Do I always pay more for a larger flat?)

5. Is there a relationship between remaining lease and resale price? (Do I pay more for a newer flat?)

6. How has the prices of resale flats changed compared to 5 years ago?

7. If I am looking for a 4-room flat in the west of Singapore, how much am I looking at?

The relevant dataset was downloaded from data.gov.sg in the form of a csv file and read as a Pandas Dataframe. Only data from 2017 onwards was looked at in this project as it represents the most recent price trends, developments and overall economic situation in Singapore.

Simple data cleaning was performed by checking for missing values or duplicated rows. Data pre-processing was then performed by converting datetime columns such as 'remaining_lease' & 'month' from string objects to datetime objects. 

Simple data visualization was then performed using a mixture of matplotlib pie charts, bar charts and scatter plots and seaborn heatmaps to gain insights into the questions mentioned above, which can be used as a guide for potential buyers or sellers looking to transact a resale flat.
