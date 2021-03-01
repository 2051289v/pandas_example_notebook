Dataset description:

The attached dataset contains mockup data for a mobile game.
In the CSV file you will find, for both iOS and Android Platforms, the following measure by date: -
ActiveUsers: the number of users active on that date -
Revenue: the revenue generated on that date, in USD -
Day 1, Day 2, …, Day 29: the return rate (also known as retention) on the n-th day after install. 
Example: Day 1 = 0.50 (50%) on the 15th of April 2019, means that 50% of users who 
installed the game on 15th of April returned on the 1st day (Day 1) after install (which 
would be the 16th of April) 

The script - 
1. Calculates the monthly averages of the daily active users (DAU) for all the months included in the dataset by platform and visualises it in a chart.
2. Calculates the ARPDAU (Average Revenue per Daily Active User) per each day, separately for each platform, then visualises ARPDAU over time.
3. Calculates the cumulative revenue of the “average” user (by platform) that installed the game on the launch date of 1st of April for the first week after launch (using Return Rate and ARPDAU), visualised in a bar chart.
