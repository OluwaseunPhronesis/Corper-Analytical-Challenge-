# Corper-Analytical-Challenge-
### Project Documentation BY Arowosola Oluwaseun 
### Using Power Pivot and Pivot Table to create Dashboard in Excel 

# Outline
- Introduction 
- The workflow
- Data Gathering and Transformation
- Data analysis
- Summary of the report and dashboard 
- Recommendation
- Conclusion


## Introduction
This project is an Analytics Corper Excel Project Challenge organized by Adewale Yususf for all Corper on creating a beautiful dashboard in Excel. 

## The Workflow
This analysis is challenge for all Corper member to add to their existing knowledge on excel to show a dynamic dashboard 
Identifying the process and steps taken is very important in each stage to make a meaningful, useful pieces from the report and which brings about an interactive insight.

The Documentation includes:
- Data Gathering and Transformation
- Data Modelling 
- Recommendation
- Conclusion

## Data Gathering and Transformation
The data was gotten from Kaggle .com which are (Restaurant and Order Data) and it was accomplished by Adewale Yusuf.

The Order data has 5,010 records: 10Columns and 5,010Rows.  The data includes Order ID, Customer Name, Restaurant ID, Order Date, Quantity of items, Order Amount, Payment Mode, Delivery Time Taken, Customer Rating-Food, Customer Rating-Delivery which will allow me to properly visualize and dimension the data.

The Restaurants Data is a small table that has a primary key (Restaurant ID) that I used to connect to the Order Data. It has 147 data records: 7Columns and 21 Rows. The data includes Restaurant ID (Primary Key), Restaurant Name, Cuisine, Zone, Category, State and Target.

The two data were connected using Power Pivot (File-Option-Add ins- Com add ins-Power Pivot), click on manage-Data sources -Excel file- browse- check use first row as column headers.

From data source -Excel file- browser – Restaurant data- use first row as headers- Restaurant Details.

Diagram view and link them together and save in power pivot.

After connecting the data, I proceed into building my report and Dashboard.

## The results of the analysis
***NB: The analysis below is for Zone B only***
1. Zone slicer is use to interact in the dashboard by Zone 
2. All Text card visualize the of Cumulative order amount 77001, Transaction count 132, Quality of items 593, Average delivery time 30.30, Average customer ranking delivery 2.9.
3. The Rectangle shape visualize the Category, order of amount and % of grand total for order of amount where Ordinary category has the highest order of amount of 45085 in 58.55% while Pro category has the least order of amount of 31916 in 41.45%.
4. The Bar chart 1 visualization shows that chew Restaurant has the highest Target of 23000 with Order amount of 17596 while The Cave Hotel has the lowest Target of 9980 with highest Order amount of 18934 and Ruchi has the lowest Order amount of 13674 with 16083 Target.
5. Bar chart 2 visualize Order amount by Cuisine, French has highest order of amount of 26797 follow by Continental has order amount of 18934 while the lowest is Chinese has order amount of 13674.
6. Line chart visualize Hourly % Change in Orders and Transaction.
7. Area chart visualize hours by Orders amount.
8. Map chart showing the State and Order amount. ***NB the Africa map used was not the right map to use but just used for sample purpose.*** 
