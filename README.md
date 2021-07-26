# bikesharing
## Overview
This analysis utilizes user data for the CitiBike bikesharing program in New York City. The data contains all the rides from August 2019 and includes rider characteristics such as biological sex identity (since corresponding labels are Male and Female, biological sex is named to be more precise. If data utilized Man and Woman, the label gender would be used), user type (either pay-per-ride 'Customer' or flat-fee 'Subscriber'), as well as ride characteristics like start and end times and duration of ride. 

This analysis seeks to understand the usage of the CitiBike program as a way of determining feasibility and implementation of bikesharing programs for Des Moines, Iowa, or other cities and companies seeking to bring bikeshare programs to new communities. This analysis is also available in a little bit more detail on this Tablaeu Public Story page: [link to dashboard](https://public.tableau.com/app/profile/brandon.kroos/viz/BikesharingAnalysis_16273241374020/Story1?publish=yes)


## Results
[Ride Duration viz] (https://github.com/BKroos/bikesharing/blob/main/viz/Screenshot%20(35).png)
This graph demonstrates that the vast majority of rides are less than 15 minutes. 

[Ride Duration by Sex viz] (https://github.com/BKroos/bikesharing/blob/main/viz/Screenshot%20(36).png)
This graph further demonstrates the previous point, showing that regardless of gender the majority of rides are less than 15 minutes.

[Trips by Day of Week] (https://github.com/BKroos/bikesharing/blob/main/viz/Screenshot%20(37).png)
This heatmap shows that, as may be expected, the morning and evening commutes see the heaviest usage. On the weekends, you can see that there is more consistent usage throughout the day, but no spikes at the levels seen during the week. 

[Trips by Day of Week by Sex] (https://github.com/BKroos/bikesharing/blob/main/viz/Screenshot%20(38).png)
This heatmap furthers the previous point. For both Male and Female identifying riders, there is the heaviest usage during the morning and evening commutes. Further, there is much heavier usage by Male identifying users. 

[Trips by Gender by Day by User Type] (https://github.com/BKroos/bikesharing/blob/main/viz/Screenshot%20(39).png)
This heatmap continues to show the heavier usage by Male identifying riders. However, it also adds the very important dimension of user type. As detailed above, users can either pay on a per-ride basis (Customer) or on a flat-fee basis, with unlimited usage (Subscriber). This visualization shows that the largest majority of users are Male-identifying and Subscribers. Regardless of the day, they see heavier usage than Female-identifying Subscribers, who in turn see heavier usage than Male or Female identifying Customers. 

## Summary
In summation, this data reveals that for any new bikesharing programs to be successful, there will be a need to recruit dedicated, consistent users willing to pay a flat monthly or weekly fee. Additional analysis on the CitiBikes data could reveal the particular trips these heaviest users are taking. Given the times of day, it is our assumption that these are trips from and to work. However, additional geographic analysis on the subscriber-level data could give further clues. Are the pickup or dropoff sites consistent Monday to Friday? Overall geographic data on the weekend user trips could be additionally revelatory. Are these trips primarily locals navigating the town, or tourists in town and trying to see the sites? Understanding answers to these questions will help cities with and without major tourist appeal determine if bikesharing is feasible in their community. 

