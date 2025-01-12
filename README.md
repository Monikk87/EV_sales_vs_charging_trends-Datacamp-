# EV_sales_vs_charging_trends-Datacamp-

#### High level examination via a chart of EV sales vs charging trends in the US (2015-2018)

### Problem description:
With the EV market rapidly evolving, understanding trends in charging facilities and sales is essential to inform strategic planning.
As a data scientist working for a leading EV charging network operator, you recognize the potential in this data and start wrangling and visualizing the aggregated yearly data.

### Data 
The US Government's Alternative Fuels Data Center collects records of electric vehicle (EV) charging infrastructure, including charging ports and station locations, as well as sales of electric vehicles. This yearly data captured in December of each year encompasses a record of EV charging port installations and station localities spanning roughly ten years, capturing both public and private charging environments.

See the data sets and description in the data_sets file

### Motivation
I picked this project from Datacamp to practice:
- Visualization skills with Matplotlib
- Analysis of missing values
- Merging dataframes

### Thought process
- I conducted high level exploratorry analysis prior to working with data
- I analysed the missing values patterns and imputed them with 0 as they represented years w/o the specific EV model sales
- I prepared the sales data frame for merging by grouping on the year
- I did outer merge on the data frames since they included different years
- I ploted the EVs sales and ports installation trends as a line plot and 2 bar plots due to different scales
