# U.S. Macroeconomic Health Flexdashboard 

This flexdashboard is designed to provide an overview of macroeconomic conditions over time. 

The dashboard utilizes three pages: Labor Market, Housing Market, and National Growth. 

The Labor Market page includes two key graphics - the unemployment rate over time and percentage share of the population in the workforce. This page alows users to either filter by quarter or enter a custom date range. I included the option to filter by quarter here since there are seasonal dynamics in the job market. For example, some organizations, especially retail, will bring on more staff in the fourth quarter to fill season jobs and prepare for the holiday season. For the other graphic, the share of the population in the workforce is reported annually, so this data is smoothed. These charts are reactive and will update as the user changes the dates or quarter. 

The Housing Market page has one large graph and three numeric valueBoxes. The graph shows a U.S. national home price index. Again, the graph is reactive and changes for the user depending on the date input. However, this date input is a slider which also can operate as a ranged slider. The input also changes the valueBoxes which provide an average for an important macroeconomic health indicator. These are home supply (this is a montly statistic which is the supply of new houses for sale to new houses sold, presented as a ratio), the average mortgage interest rate, and the household income at the median. 

The last page is National Growth. This page has two annotated graphics which show inflation over time as well as gross domestic product. The table to the right of that is a data table conditionally formatted to have months which have an inflation rate above the target 2% colored red. I conditioned these rows by creating a dummy "too hot" variable to format the data. The charts and the datatable are reactive to the user. 

Data for this project was pulled from a popular Kaggle data set: https://www.kaggle.com/datasets/sagarvarandekar/macroeconomic-factors-affecting-us-housing-prices/code?resource=download. This dataset originated from the St. Louis Fed's FRED, with additional info from the Census and OECD.

