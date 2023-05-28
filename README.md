# ExcelProject
# >> CASE STUDY : Driving Sales Success:A Data-Driven Journey through our Dynamic Sales Dashboard

>> TABLE OF CONTENT :
 
# 1. TASK-

* Sales Performance Monitoring: Track and analyze sales data in real-time, including overall sales, individual product performance, and sales trends over time.

* Customer Insights: Gain valuable insights into customer behavior, preferences, and purchase patterns to target marketing efforts, optimize promotions, and enhance customer satisfaction.

* Store Performance Analysis: Analyze sales data across different store locations, compare performance metrics, and identify top-performing stores as well as areas requiring improvement.

* Revenue and Profit Analysis: Track revenue and profitability metrics, identify areas of high or low profitability, and make data-driven decisions to maximize profits.

* Product Performance Analysis: Analyzing the sales data to identify top-selling products, best-performing categories, and trends to optimize inventory management and sales strategies.

* Data Visualization and Reporting: Create visually appealing and easy-to-understand dashboards, charts, and reports to effectively communicate sales performance and insights to stakeholders.

# DATA SHEET OVERVIEW
1. We have 2 sheets to view, Set the Data in both Table with Table Name: MASTER DATA and INPUT DATA under TABLE DESIGN TAB .
![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/6dddf744-74db-4ea8-9a0d-321a461e714a)

2. For data cleaning check for any duplicates, null value. Since data we have is sorted.
 
3. Apply VLOOKUP at input data to extract data from master data. In reference to product ID.
 
 ![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/eb17701a-5217-4b41-b6f3-80fe0423fcec)
 
 ![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/25fa4957-68d6-46d1-9b68-7783122b31d9)
 
4. we have created few additional column:
TOTAL SELLING PRICE,![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/773f8ab5-e26c-40ae-847d-43f441c5af31)

TOTAL COST PRICE,![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/888842d9-0174-4766-a398-eb81b2a69e23)
 
DAY ,![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/15d32ab0-a9cf-466e-bb74-747814383053)

MONTH ,![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/343270d4-37f3-44de-9d54-70e41be0c354)

YEAR ![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/8e82b880-7a29-4b1b-89ac-be5897a0283d)

As we are done with preparing database > we need to create Pivot tables.

# DATA VISUALISATION - ADDING PIVOT TABLES

1.Go to ANALYSIS New Sheet> Insert Pivot Table> Name each Pivot Table Accordingly.

2.Create Pivot Table As Follow:
* DAILY : Days with respect to Total selling price.
![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/9b0c20dd-efd1-46ed-9b20-9e5176b2bdc9)

* TOTAL PROFIT : To calculate total profit and profit percentage from given price > LINKING VALUE TO PIVOT TABLE WILL MAKE IT DYNAMIC .
 
![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/da92d742-53b8-461f-861c-da9c5f866083)

* MONTHLY EXPENSES

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/c6b3e4a5-ff60-4ba8-8f45-bdf0003550da)

* PRODUCT ANALYSIS : Product is shown with respect to theie unit of measurement, selling price and quantity > keep pivot table in TABULAR FORM under Report Layout.

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/8f016c49-8f1b-4785-98f2-226d4a06a457)

* YEARLY ANALYSIS 
     
![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/2884202b-6456-4294-a161-503d7d66b7fd)

* CATEGORY ANALYSIS
   
![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/800354c9-bcd1-4687-b69c-4557f3222c9e)

* PAYMENT MODE AND SALES TYPE

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/b2720038-7790-47e2-b882-66bb898002b1)

*PREPARE VISUALS
1. Add SLICERS IN DASHBOARD > LINK ALL SLICERS TO EVERY PIVOT TABLE
2. Go To Slicer Tab> Report Connections> Select All Pivot Table We Want To Link.

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/fae364a8-ee7d-40ac-a2b7-a7ca95a98079)


![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/8759c445-c4bd-49bb-b9a8-4c64ae23a18a)

3. ADD AREA CHART FOR DAY WISE SALES :

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/691c7b54-7905-4959-8c60-fa43d917d063)

4. CALCULATE TOTAL SALES, TOTAL PROFIT, PROFIT PERCENTAGE AND FORMAT CELL ON MONTHLY BASIS BY CONNECTING IT TO MONTHLY PIVOT TABLE :

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/62715af2-ce59-4780-acb4-839eb0ce2f94)
To add bar chart with total sales, total profit and profit percentage we need to connect all values for dynamic use.
From INSERT(DEVELOPER TAB)> Add 3 Checkboxes, so that we can show or hide sales, profit or profit%. We need to add if function into our cell to link true or false condition with the table value so that our column chart look presentable.

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/2d1fce17-735f-440a-8336-aa7dcc26698a)

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/ca73c4b7-ebb2-4ba5-af07-ab6eafa6356e)

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/f58b09d0-a963-4250-adc9-d355dfd0a9e7)

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/160f4af8-030e-4bc8-b3b2-f963b7d9f694)

NOW INSERT THE CHART> FORMATTING>CONNECT WITH TABLE>FORMAT CHART

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/0d9467db-e0bd-43bb-b7f7-a4aa68ab4362)

5. FROM PRODUCT ANALYSIS: WE USE RANK FUNCTION TO GET TOP PRODUCT
 
*usage of offset function is highly recommended to connect everything with pivot table and make it dynamic.

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/ce52d8de-79c9-4615-b7cd-288697fe4de4)

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/811da57a-bdcb-438e-abbc-fe27a990afdf)

*rank in reference to sales, don't forget to lock the range by using F4 KEY .

>> EACH PRODUCT ON SALES BASIS :  

6. FROM CATEGORY ANALYSIS: INSERT HIERARCHY CHART , As Hierarchy chart doesn't work with pivot table we again need to use offset function and make seperate chart to link it with dynamic hierarchy chart > find Rank with respect to sales.

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/9edfb19d-d80c-4124-a78c-587354ad7153)
![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/ca0a0813-0f3b-45eb-beec-b283bd5f4c88)

7. ADDING YEARLY PRESENTER: In form of pie chart for year 2021 and 2022.

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/1b4804db-2a39-4a94-8df8-996151893f6d)

8. ADDING SALES TYPE :

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/88a6d4a4-6d84-4a3b-b64d-b717b935296b)

9. ADDING PAYMENT MODE :

![image](https://github.com/ishanimahajan20/ExcelProject/assets/134215344/5961a3ad-7f2a-49c7-ad6c-d0121ee8b29e)

10. 

















DATA ANALYSIS - ADDING CHARTS, SLICERS ETC. AND LINKING EACH CHART TO EACH OTHER FOR DYNAMIC VIEW.

