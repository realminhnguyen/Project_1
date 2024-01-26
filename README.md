# Project_1

## Project Proposal
### Cost of Living Index 1980 to 2023 Comparative Analysis

This Project serves to analyze and present the cost-of-living, inflation, and other economic trends from the 1980s to 2023 in a more aesthetic manner. Current tools from the US Bureau of Labor Statistics do not provide visually appealing means to view trends and numbers. We will bridge the gap between interesting data and presentability.

### Questions to Answer
1. How has the cost of living in the United States evolved over the past four decades, specifically from 1980 to 2023?

2. What are the significant fluctuations in commodity prices during the analyzed period, and are there any noticeable correlations with inflation trends?

3. How do specific commodity prices contribute to changes in the overall cost of living in the United States, and can these relationships be visually represented to enhance understanding?

4. Based on the analysis, what are the main drives of inflation and current cost of living?

### Datasets to be used
- [US Bureau of Labor Statistics](https://www.bls.gov/data/)
- [FiscalData.Treasury.Gov](https://fiscaldata.treasury.gov/datasets/historical-debt-outstanding/historical-debt-outstanding)
- [Federal Reserve Economic Data](https://fred.stlouisfed.org)

### Extra library to be used
**Plotly** for math and computation.

### Breakdown of Tasks
#### Hunt for Data
We are going to download various desired CSV files to paint the picture of the economic landscape over the past 4 decades. 

#### Data Cleanup & Analysis
##### Data Cleanup
Use Pandas to retrieve the csv files, explore the data, and clean it up. This includes:
- Removing nulls/rebuilding missing data with the.dropna() method when the amount of missing data is relatively small.
- Find duplicate values and remove them if they are deemed unnecessary.

##### Analysis
We will focus on analysis techniques such as aggregation, correlation, comparison, summary statistics, and financial analysis.

## Usage and Installation
Download the necessary modules and resource files and work your way through the notebooks.
As you work your way through, you will see the transform from pandas DataFrames to plots.

Note: 2 notebooks. Run the 'project_1' notebook first for data cleaning. Run the visualization notebook AFTER you set the notebook kernel to 'project_1'.

If help is needed, you can find resources online.

## Conclusion and Analysis
Compared to 1980 the cost of living increased by more than 200% percent in general. Even items like a cup of coffee would be unaffordable for someone earning 1980's dollars.

While the price of good steadily increased from 1980 to 2023, inflation rates has decreased. To go in more details the price of bread went up by 285%, Gasoline went up by 208% and electricity went up by 180%.

The median house price and mortgage rate have clear correlation. Since 1980 every time one goes  up the other tend to decrease at the same rate.

Although the median income increased by 232%, the price of housing increased two times faster.

The prices of commodities and essentials such as gasoline, food, electricity and shelter has increased significantly compared to income that it difficult for the average American to have the same quality of life they had in the 1980's.
