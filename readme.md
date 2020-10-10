# Explanatory visualizations for Ford gobike dataset

## by Mariam Ashraf


## Dataset

- In 2017 Ford gobike system was a re-launch of Bay Wheels which was a regional public bicycle sharing system in California's San Francisco Bay Area in a partnership with Ford Motor Company, like other bike share systems, consists of a fleet of specially designed, durable bikes. The bikes are available for use 24 hours/day, 7 days/week, 365 days/year and riders have access to all bikes in the network when they become a member(subscriber) or purchase a pass(customer).
- In data wrangling step, at first I checked if there are any missing values, nan values, or duplicated records and fortunately I didn't find, then checked the types of the features to make sure that all of them are in the proper datatype
I changed start time and end time to date time datatype, and user type to a category data type, I did this to can creat a new variables from it like start month and start weekday and do other operations, also I created a new feature "Duration in hours".


## Summary of Findings

From the Exploration step I found out that:
1- The two days that have the least number of rides(sunday and saturday), have the highest average of trip duration, and this shows us that no relationship between the average trip duration and the number of rides per day.
2- August, July, and June "summer months" have lower number of rides compared to the other recorded months, and October has the highest number of rides.
3-  customers spent much more time in their trips during summer months, but subscribers have almost constant trip duration through all months and this make us think if the subscribers have a more specific goals to achieve compared to customers who took the bikes for longer trip durations.


## Key Insights for Presentation

1- customers spent much more time in their trips during summer months, but subscribers have almost constant trip duration through all months and this make us think if the subscribers have a more specific goals to achieve compared to customers who took the bikes for longer trip durations.
2- Both types of users have different pattern of Trip durations through all the weekdays and months, we can see that for customers the number of rides reach its max and exceeds 4000 in september on saturdays and for subscribers only 2 days that have always small number of rides through all months.

## Sources:
1- https://stackoverflow.com/questions/43727278/how-to-set-readable-xticks-in-seaborns-facetgrid.
2- https://seaborn.pydata.org/generated/seaborn.FacetGrid.html.
3- https://seaborn.pydata.org/generated/seaborn.FacetGrid.map.html#seaborn.FacetGrid.map.
4- https://stackoverflow.com/questions/29813694/how-to-add-a-title-to-seaborn-facet-plot.