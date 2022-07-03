
# bikesharing
Analysis with Tableau

## Analysis Overview     

### Analysis Purpose

This analysis looked at Citibike riding data in New York City across August 2019. The data included user demographics such as age & gender as well as bike & ride data. 

## Results

[Link to Dashboard](https://public.tableau.com/app/profile/tommie.brechbill/viz/CitibikeAugust2019DataHomeworkAnalysis/August2019CitibikeHomeworkAnalysis "link to dashboard") 


### Visualization Descriptions

![Checkout Times](https://github.com/tbrech4/NYC-Bikesharing/blob/main/Resources/Viz1.png)

This visualization looks at average length of citibike rides. A vast majority of the rides are under an hour in length. The average length is around just five minutes.

![Checkout Times by Gender](https://github.com/tbrech4/NYC-Bikesharing/blob/main/Resources/Viz2.png)

This visualization is very similar to the first one, but includes the information broken out by gender. Males are more frequent citibike riders, but their average trip length appear to be mostly the same. 

![Start Times Heatmap](https://github.com/tbrech4/NYC-Bikesharing/blob/main/Resources/Viz3.png)

On Weekdays, it looks like Peak times are around the start and end of the workday. On weekends, it looks like it more of a distribution centered around the middle of the day i.e. noon. This would suggest that more rides during the weekday are for commuting & rides during the weekend are more for leisure.

![Start Times Gender Heatmap](https://github.com/tbrech4/NYC-Bikesharing/blob/main/Resources/Viz4.png)

This visualization again shows that males are more frequent riders, and the timing of rides appear to peak around the start & end of the workday on Weekdays and around the afternoon on Weekends.

![User Trips by Gender](https://github.com/tbrech4/NYC-Bikesharing/blob/main/Resources/Viz5.png)

Male subscribers are the most frequent riders. One interesting thing to note is that it appears that there are no subscribers with an Unknown Gender. This makes sense since you likely have to give your gender in order to signup as a subscriber. 

![Starting Stations](https://github.com/tbrech4/NYC-Bikesharing/blob/main/Resources/Viz6.png)

This map of starting station popularity shows that most of the popular stations are in Manhattan, especially south of Central Park. This would suggest that most of the people working in Manhattan work south of Central Park. 

![Starttime Frequency Hour and Weekday](https://github.com/tbrech4/NYC-Bikesharing/blob/main/Resources/Viz7.png)

This breakout shows riding frequency by Subscriber Type & Whether the rides occurred on a weekday vs weekend. 

Subscribers appear to ride the bikes mostly at the end & beginning of the workday. Customers don't show a ton of variance in ridership trends on Weekend vs Weekdays aside from average ride time on Weekdays starting a few hours later. Subscribers & customers appear to have the same Weekend riding trends.

A calculated field was used to determine if the ride occurred on Weekday or Weekend.


## Summary

After doing this analysis we can conclude that many Citibike subscribers use bikes at the beginning & end of the workday - likely to commute to work. We also determined that males are more frequent riders, but both genders have similar average ride lengths. Most of the popular stations are on Manhattan, specifically south of Central Park. 

Additional visualization opportunities include mapping out the most popular routes i.e. starting & stopping station combinations. You could possibly do this via Heatmap overlayed on a real map. Another visualization could be looking at average age of subscriber vs customer to see if there is a relationship between age and likelihood to become a Citibike member. If there is a relationship i.e. younger people are more likely than older people to get a membership, than marketing could be done to help get more older people to sign-up. 
