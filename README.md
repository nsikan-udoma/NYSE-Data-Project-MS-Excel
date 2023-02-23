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
As a seasoned Data Analyst, the main goal of the project was to showcase my ability to:
- Interpret the measures of central tendency and spread (mean, median, standard deviation, range).
- Use a combination of Excel functions (e.g., IF statements, INDEX, and MATCH, calculating descriptive statistics with the IF statement, dropdowns, data validation, VLOOKUP).
- Develop a dashboard for a Profit and Loss Statement (Income Statement), that calculates the Gross Profit, Operating Profit, or EBIT for a company selected from a drop-down list of all companies. The P&L statement was designed to include the Gross Profit, Operating Profit, or EBIT values for all the years there is historical data available for that company in the dataset.
- Create a dynamic financial model for one (1) company at a time, that forecasts out the Gross Profit, Operating Profit, or EBIT for two more years using three scenarios (Best case, Weak case, and Base case). Forecasting assumptions for revenue growth, gross margin, and operating margin was designed to change for each scenario. Also the forecasting model was designed to be dynamic for the selection of the case (Weak, Base, Strong). However, the forecasting model can be static for the chosen company sticker symbol.

## Main Insights

Between 2013 and 2015, PepsiCo earned the highest average revenue of $65.38 billion, followed by Coca-Cola in 2nd position with $45.71 billion. Dr Pepper ranks third with $6.13 billion, while Monster Beverages comes in lastly with $2.48 billion. PepsiCo also generated the highest operating profit of $9.67 billion on average, followed closely by Coca-Cola with $9.55 billion, while Dr Pepper and Monster Beverages made significantly less operating profit. However, PepsiCo had the highest cost of revenue of approximately $30.40 billion, followed by Coca-Cola, Dr Pepper, and Monster Beverages. These figures suggest that while PepsiCo earned significantly more revenue than its competitors, it also incurred significantly higher costs.

## Recommendations

- Despite having the highest revenue and operating profit, PepsiCo also had the highest cost of revenue. Therefore, Pepsico's senior management team (SMT) and relevant stakeholders should focus on reducing the cost of revenue to increase profitability.

- Coca-Cola had a significant market share and generated a substantial amount of revenue and operating profit. Coca-Cola's SMT and relevant stakeholders should consider strategies to increase revenue and reduce cost of revenue to further enhance profitability.

- Dr Pepper and Monster Beverages had much lower revenue and operating profit compared to PepsiCo and Coca-Cola. The SMT and relevant stakeholders of both beverage manufacturers should evaluate the reasons for this and develop strategies to increase revenue and improve profitability.

- To further improve profitability for all beverage manufacturers, their respective SMTs and relevant stakeholders should consider exploring opportunities for cost-cutting, streamlining operations, and optimizing resource utilization. This involves keeping a close eye on industry trends and developments to ensure that their companies remain competitive and innovative in the marketplace.

- Overall, all 4 beverage drinks companies should focus on strategies that enhance revenue growth, reduce costs, and increase profitability to remain competitive and successful in the beverage industry.

## Accessing the Excel Dasboard

Below is the link to the Excel File. Please download and view the dynamic dashboards locally on your computer using Microsoft Excel (Note: Excel dashboards do not open properly in google sheets). 

[Excel Financial Forecast Model & Dashboard](../main/projectdata-nyse%20(main).xlsx)

