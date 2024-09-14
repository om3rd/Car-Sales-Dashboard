# Car-Sales-Dashboard
A Power BI dashboard to visualize sales(amount of sales, profit-loss) of car brands by region.

### Dashboard Link : https://app.powerbi.com/groups/me/reports/7d248b01-25a3-4a34-9316-a8542aab234c?ctid=755de9ae-86f9-4909-b1a5-f092c48533f1&pbi_source=linkShare

## Problem Statement

In this dashboard, a financial report was created according to the sales amounts of seven car brands selling in Turkey in 2018-2019, the revenues they generated, their total costs on a vehicle basis, as well as their profit-loss situations, the dealers owned by each region and the brands that these dealers sell.

The dataset consists of 60,000 rows of data in total and the photos of the dealers were randomly taken from the internet.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a CSV file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on the entire dataset".
- Step 4 : Created a new measurements table to save further measurements on this table.
- Step 5 : Measures were created for each loan type as target and sales, a measure was created as total sales and total sales amount, and a total cost and a profit-loss measure were created to see the cumulative results. 
- Step 6 : In the report view, I have created my own canvas.
- Step 7 : To facilitate the use of the dashboard, two different pages were created and they are; Sales by Regions, and Sales by Brands.
- Step 8 : Added visual filters (Slicers) named 'Year-Month', 'Regions', and 'Brands'.
- Step 9 : Added cards; depending on the profit and loss situation, the card is colored green or red. Added donut chart to visualize total brand usage percentage between those seven brands(BMW, Audi, Mercedes, Ford, Jeep, Mini, Porsche). Added sparkline so that the highest and lowest values are shown according to the information on the cards. Shape map was added so that the selected region automatically zooms on the map according to the car and dealer, and the provinces are displayed on the color palette from red to green (red is a low and bad financial result, while green is the opposite), and information such as how much cars each province sells, how much profit-loss and income it generates. A filtering screen consisting of dealer photos has been added so that you can see which dealer is in which region and province.

- # Screenshots of Dashboard

- ![Screenshot 1](images/Screenshot%20(1157).png)
- ![Screenshot 1](images/Screenshot%20(1158).png)
- These screenshots were taken from the page named Sales by Region
- ![Screenshot 1](images/Screenshot%20(1159).png)
- ![Screenshot 1](images/Screenshot%20(1160).png)
- ![Screenshot 1](images/Screenshot%20(1161).png)
- ![Screenshot 1](images/Screenshot%20(1162).png)
- ---------
These screenshots were taken from the page named Sales by Brands
- ![Screenshot 1](images/Screenshot%20(1163).png)
- ![Screenshot 1](images/Screenshot%20(1164).png)
- ![Screenshot 1](images/Screenshot%20(1165).png)
- ![Screenshot 1](images/Screenshot%20(1166).png)
- ![Screenshot 1](images/Screenshot%20(1168).png)
- ![Screenshot 1](images/Screenshot%20(1169).png)
