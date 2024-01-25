# Haut  Supermarket Sales Report (2013 and 2014)

![Slide1](https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/Slide1.PNG)

##  Introduction
This is a Power BI project on sales analysis of an hypothetic Supermarket, Haut Super market for 2 consecutive years (2013 and 2014). The project is to clean, analyze and draw insights in order to answer some critical question and help stake holders of Haut make informed decisions.


## Data Source:
The data used in this project is a modified microsoft dataset known as Financial Samples;  
* Microsoft Financial Sample Data [DownloadMicrosoftData](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download)
* Modified Dataset used in this Project [DownloadModifiedDataset](https://docs.google.com/spreadsheets/u/2/d/1xkWC6Jlk_YZECHbpUtoc8AEiPb9jfcld/edit?usp=drive_web&ouid=114068862415751566917&rtpof=true)

## Problem Statement
This project is aimed at improving business performance of Haut supermarket and hence, answer the following questions;
1. What is the monthly trend of Profit?
2. What is the ratio of profit of the years under review?
3. What is the profit ratio on quarterly basis?
4. Which product category is the most and least profitable?
5. Where does most sales comes from in terms of region?
6. Does discount has an effect on Sales?
7. What is the performance of the Africa market relative to other continent?
8. Which country is most profitable?

## Power BI and Analytics Technical Skills:
+ Project Planning and Documentation
+ Data Gathering
+ Power Query
+ Data Modelling
+ Report Design
+ Data Visualization
+ Data Analysis Expression (DAX)
+ Page Navigation and Button
+ Business and Analytics Reporting
+ Performance Optimization
+ Deployment and Power BI Service
+ Scalability
+ Feedback and Continuous Improvement
  
## Data Modelling
To optimize the performance of the data model, a calendar table was created using the DAX function. The data model follows a star schema with one fact table and three dimension tables. The dimension tables have PRIMARY KEYS that connect to the corresponding FOREIGN KEYS in the fact table, forming a one-to-many relationship between each dimension table and the fact table. The diagram below shows the data model.  
<img src="https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/Data%20Modelling.PNG" width=50% height=50%>

## Report Design and Visualization
The Report Canvas was designed in Power Point and imported to PowerBI as canvas background. Here is a sample of the slide in Power Point   
<img src="https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/Slide2.PNG" width=50% height=50%>  
5 pages were created; Home, Consolidated, Stationery, Cosmetics and Electronics. 
_Home_ page is the landing page while _Consolidated_ has the general report without filter while other pages has filtered reports accroding to their page name.
On each page, the new card visual is used to hold Total Sales, Gross Sales and Profit, Line Chart is used for the series analysis while a column and bar chart are adopted for the Continental and Country analysis respectively. The last image is the button for page navigation. 

| Visuals             |  Visuals |
:-------------------------:|:-------------------------:
<img src="https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/Card1.PNG" width=90% height=90%>|<img src="https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/button1.PNG" width=40% height=40%> 
<img src="https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/columnbarchart.PNG" width=60% height=60%> |<img src="https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/Linechart.PNG" width=100% height=100%> 

## Analytics abd Insights
The data analysis revealed that;

1. There is a zig-zag trend of profit across the months, however, October records the highest profit of ($3.74M) which is 15% of the total profit and April records the least profit of ($1.4M), 6% of total profit
2. There exist an increase in profit from 2013 to 2014 with a ration of 4:6
3. Q4 record the highest profit of ($8.4M) with Q1 with the lowest ($5M), this shows steady increase in profit across the quarter from 1 to 4
4. The most and least profitable product category are Stationery and Cosmetics which amounts to 44% and 28% of the total profits respectively 
5. By region continent is intended, therefore Haut supermarket makes the most sales from America region ($98M) with 47% of the total Gross Sales
6. This is achieved with the help of the slicer; which shows that product with discount band to 96% of the total Gross sales while only 4% don't have discount with High band of discount amounting to 41% of the Gross Sales
7. Africa pull 9% of the total Gross sales and 6% of the total Profit from the 202,286 Units solds from South Africa and Nigeria. This is can be visualised when clicking on Africa in the column chart 
8. France is the most profitable Country among the Haut Stores with 20% ($4.9M) of the total profit


## Conclusions and Recommedations


## Deployment to Power BI Service
This Report is deployed to Power BI service from my developer Microsoft account and publish to the web for everyone to have access to it.
[HautSupermarketAnalysis](https://app.powerbi.com/groups/me/reports/66ab0071-4b25-41c8-99fd-fd006603aacd/ReportSection6239a8326550e132bae6?ctid=32796be2-60fb-4da2-8d26-06e5938e6e6b&experience=power-bi)
To Open a developer Microsoft account, kindly check this article



