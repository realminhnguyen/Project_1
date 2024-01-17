# Project_1

### Project Proposal
#### Cost of Living Index 1980 to 2023 Comparative Analysis

This Project serves to analyze and present the cost-of-living, inflation, and other economical trends from the 1980s to 2023 in a more aesthetic manner. Current tools from the US Bureau of Labor Statistics do not provide visually appealing means to view trends and numbers. We will bridge the gap between interesting data and presentability.

#### Questions to Answer
1. How has the cost of living in the United States evolved over the past four decades, specifically from 1980 to 2023?

2. What are the significant fluctuations in commodity prices during the analyzed period, and are there any noticeable correlations with inflation trends?

3. How do specific commodity prices contribute to changes in the overall cost of living in the United States, and can these relationships be visually represented to enhance understanding?

4. Based on the analysis, what are the main drives of inflation and current cost of living?

#### Datasets to be used
- [US Bureau of Labor Statistics](https://www.bls.gov/data/)
- [FiscalData.Treasury.Gov](https://fiscaldata.treasury.gov/datasets/historical-debt-outstanding/historical-debt-outstanding)
- [Federal Reserve Economic Data](https://fred.stlouisfed.org)

#### Breakdown of Tasks
##### Hunt for Data
We are going to download various desired CSV files to paint the picture of the economic landscape over the past 4 decades. 

##### Data Cleanup & Analysis
###### Data Cleanup
Use Pandas to retrieve the csv files, explore the data, and clean it up. This includes:
- Removing nulls/reubilding missing data with .dropna() method when the amount of missing data is realtively small.
- Find duplicate values and remove them if they are deemed unnecessary.

###### Analysis
We will focus on analysis techniques such as aggregation, correlation, comparison, sum,ary statistics, and financial analysis.