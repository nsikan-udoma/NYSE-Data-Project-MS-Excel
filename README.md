![NYSE Data Analysis](https://github.com/nsikan-udoma/NYSE-Data-Project/blob/main/Project%20Cover%20Image.png)

# Analyzing the NYSE Data for the “Soft Drinks” GCIS Sub Industry to Understand Financial Performance from 2013 to 2015

Analyzing real-life data from the New York Stock Exchange (NYSE). A subset of a large dataset provided by Kaggle was used in this analysis. The dataset contained historical financial data from S&P 500 companies listed on the NYSE between 2013 and 2015, and sometimes 2016 if available.

Background:
Two (2) datasets Fundamentals.csv and Securities.csv files were downloaded from Kaggle. The Fundamentals file provides the fundamental financial data gathered from SEC 10K annual filings from 448 companies listed on the S&P 500 index. The Securities file provided the industry or sector information for the companies under their respective categories in the S&P 500 index.
Both datasets were cleaned and combined to one dataset for the purpose of this project.

Tasks to be performed included: calculating summary statistics, drawing inference from the statistics, measuring business metrics, and using financial models to forecast future growth projects for the 448 companies listed in the NYSE.

The cleaned dataset contains the following information:
- Ticker symbol: Stock symbol
- Years: Number of years for which data is provided
- Period ending
- Total revenue
- Cost of goods sold
- Sales, General, and Administrative expenses
- Research and Development expenses
- Other Operating expense items
- Global Industry Classification Standard (GICS) Sector: The industry sector the company is categorized under (e.g., American Airlines with the ticker symbol AAL is categorized under Industrials.)
- GICS Sub Industry: Sub-industry sector the company is categorized under (e.g., AAL is further categorized under the sub-category of the "Airlines" industry.)

Skills to be Demonstrated:
As a seasoned Data Analyst, I wanted to showcase my ability to:
- Interpret the measures of central tendency and spread (mean, median, standard deviation, range).
- Use a combination of Excel functions (e.g., IF statements, INDEX, and MATCH, calculating descriptive statistics with the IF statement, dropdowns, data validation, VLOOKUP).
- Develop a dashboard for a Profit and Loss Statement (Income Statement), that calculates the Gross Profit, Operating Profit, or EBIT for a company selected from a drop-down list of all companies. The P&L statement was designed to include the Gross Profit, Operating Profit, or EBIT values for all the years there is historical data available for that company in the dataset.
- Create a dynamic financial model for one (1) company at a time, that forecasts out the Gross Profit, Operating Profit, or EBIT for two more years using three scenarios (Best case, Weak case, and Base case). Forecasting assumptions for revenue growth, gross margin, and operating margin was designed to change for each scenario. Also the forecasting model was designed to be dynamic for the selection of the case (Weak, Base, Strong). However, the forecasting model can be static for the chosen company sticker symbol.


## Accessing the Excel Dasboard

Below is the link to the Excel File. Please download and view the dynamic dashboards locally on your computer using Microsoft Excel (Note: Excel dashboards do not open properly in google sheets). 

[Excel Financial Forecast Model & Dashboard](../main/projectdata-nyse%20(main).xlsx)


## Analyzing the Data using Research Questions
Data cleaning using Excel functions (NULL functions, IF statements, INDEX, MATCH, VLOOKUPs) was necessary to fix data quality and tidiness issues. I conducted exploratory data analysis to understand trends, patterns and correlations between variables in the dataset. And then I conducted an explanatory data anlysis using research questions derived from EDA of the dataset. These research questions include:

### 1. How did the NYSE soft drinks sub industry perform in terms of average total revenue earned between 2013 & 2015?
![Avg Total Revenue btw 2013 and 2015](https://user-images.githubusercontent.com/24312721/220990100-c1abfb46-c5ad-4aa2-86c2-63dac173ec18.png)

On average, PepsiCo (PEP) earned the highest revenue of $65.38 billion between 2013 and 2015 , followed by Coca-Cola (KO) in 2nd position with $45.71 billion. Dr Pepper (DPS) ranks third with $6.13 billion average revenue between 2013 & 2015, while Monster Beverages (MNST) comes in lastly with $2.48 billion.  
The mean of the average revenue earned by all 4 companies between 2013 and 2015 was $29.93 billion with a standard deviation of $30.69 billion. This is because the gap or range between PEP (the highest earner) and MNST (the lowest earner) was $62.9 billion. The chart indicates that PEP earned approximately 26.4 times more than MNST; and when compared to the others, PEP earned approximately 10.7 times more than DPS, and 1.4 times more than KO.

### 2. How did the NYSE soft drinks sub industry perform in terms of average operating profit generated between 2013 & 2015?
![Avg Total Revenue btw 2013 and 2015](https://user-images.githubusercontent.com/24312721/220990922-ef94c4c1-2c1a-4285-9658-6f97345671fb.png)

On average between 2013 and 2015, PepsiCo (PEP) generated the highest operating profit of $9.67 billion, followed by Coca-Cola (KO) with $9.55 billion, then Monster Beverages (MNST) with $1.38 billion, and finally Dr Pepper (DPS) with $1.17 billion. 
The mean of the average operating profit by all 4 companies between 2013 and 2015 was $5.44 billion with a standard deviation of $4.81 billion. This is because the gap or range between PEP (the highest) and DPS (the lowest) was $8.49 billion. The chart indicates that PEP made approx. 8 times more operating profit than DPS, 7 times more than MNST, and almost the same amount with KO. This suggests that although PEP earned significantly more revenues between 2013 and 2015 (as seen from the previous slide), there may be a lot of contributing factors such as costs and expenditures taking away from their profits.

### 3. How did the NYSE soft drinks sub industry perform in terms of average cost of revenue between 2013 & 2015?
![Average Cost of Revenue between 2013   2015 for Soft Drinks Companies in the NYSE](https://user-images.githubusercontent.com/24312721/220991867-a6c77794-3c57-4e1f-8c64-bdd80f88fee2.png)

On average between 2013 and 2015, PepsiCo (PEP) had the highest cost of revenue of approx. $30.40 billion, followed by Coca-Cola (KO) with $17.93 billion, then Dr Pepper (DPS) with $2.52 billion, and finally Monster Beverages (MNST) with $1.10 billion. 
The mean of the average cost of revenue by all 4 companies between 2013 and 2015 was $12.99 billion with a standard deviation of $13.89 billion. This is because the gap or range between PEP (the highest) and MNST (the lowest) was $29.31 billion. The chart indicates that PEP spent approx. 28 times more on cost of revenue than MNST, 12 times more than DPS, and almost 2 times more than KO.

## Summary of Main Insights

Between 2013 and 2015, PepsiCo earned the highest average revenue of $65.38 billion, followed by Coca-Cola in 2nd position with $45.71 billion. Dr Pepper ranks third with $6.13 billion, while Monster Beverages comes in lastly with $2.48 billion. PepsiCo also generated the highest operating profit of $9.67 billion on average, followed closely by Coca-Cola with $9.55 billion, while Dr Pepper and Monster Beverages made significantly less operating profit. However, PepsiCo had the highest cost of revenue of approximately $30.40 billion, followed by Coca-Cola, Dr Pepper, and Monster Beverages. These figures suggest that while PepsiCo earned significantly more revenue than its competitors, it also incurred significantly higher costs.

## Recommendations

- Despite having the highest revenue and operating profit, PepsiCo also had the highest cost of revenue. Therefore, Pepsico's senior management team (SMT) and relevant stakeholders should focus on reducing the cost of revenue to increase profitability.

- Coca-Cola had a significant market share and generated a substantial amount of revenue and operating profit. Coca-Cola's SMT and relevant stakeholders should consider strategies to increase revenue and reduce cost of revenue to further enhance profitability.

- Dr Pepper and Monster Beverages had much lower revenue and operating profit compared to PepsiCo and Coca-Cola. The SMT and relevant stakeholders of both beverage manufacturers should evaluate the reasons for this and develop strategies to increase revenue and improve profitability.

- To further improve profitability for all beverage manufacturers, their respective SMTs and relevant stakeholders should consider exploring opportunities for cost-cutting, streamlining operations, and optimizing resource utilization. This involves keeping a close eye on industry trends and developments to ensure that their companies remain competitive and innovative in the marketplace.

- Overall, all 4 beverage drinks companies should focus on strategies that enhance revenue growth, reduce costs, and increase profitability to remain competitive and successful in the beverage industry.

## Challenges & Next Steps
![All 4 companies](https://user-images.githubusercontent.com/24312721/220993005-b7fddaaa-c8ac-41e1-a739-0aef80b61e4a.png)

The NYSE-Data dataset only contained data about the total revenue generated, the amounts spent on cost to generate the revenue, and the operating profit before deduction of income taxes and interest payments. However, to better understand how these soft-drinks companies performed between 2013 and 2015, data enrichment is necessary to gather data on other financial metrics such as the profit margin, operating margin, debt-to-asset ratio, and net profit margin, to better understand performance and measure profitability for these soft-drinks companies. 

As an extension to this project, I plan on gathering data on the other financial metrics listed above from the financial statements of Pepsi, Coca-Cola, Dr Pepper and Monster Beverages. The assumption is that these data points are readily available through their respective financial statements for the years 2013 - 2015 from their respective websites. If not, I will have to use websites that provide publicly available datasets such as:
- The U.S Government's Open Data Portal: https://www.data.gov/
- Kaggle Datasets: https://www.kaggle.com/datasets
- Data World: https://data.world/
- AWS Public Datasets: https://aws.amazon.com/public-datasets/
- Google's Dataset Search: https://datasetsearch.research.google.com/

... just to name a few.

## How to Access the Excel Dashboard

Once again you can download the Excel Dashboard using the link below. Please download and view the dynamic dashboards locally on your computer using Microsoft Excel (Note: Excel dashboards do not open properly in google sheets). 

[Excel Financial Forecast Model & Dashboard](../main/projectdata-nyse%20(main).xlsx)

