# Bike Sharing Analysis

Using Tableau and CSVs to visualize bike sharing data

## Overview of Project

Information downloaded from NYC CitiBike for all bike sharing data in August 2019. Results visualized using Tableau.

### Purpose

Using real data from New York City's CitiBike, information is gathered about how bike sharing functions. Information may be used for a potential bike sharing company in Des Moines, Iowa. Investors will need compelling visualizations to greenlight the new bike sharing program for Des Moines. 

## Results

### Deployed Tableau Analysis

[link to dashboard](https://public.tableau.com/views/NYCCitiBikeChallenge_16652593091080/NYCStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

#### *Most popular starting locations of bikes*

![starting_locations](https://user-images.githubusercontent.com/108373151/194726674-ad5f3f19-3c07-4689-b11f-e0f9c19fc52f.jpg)

This map shows the most popular starting locations of bikes. Of course, the most popular locations are in Manhattan, as it not only includes a lot of tourist attractions, but it also includes a lot of high-rise office buildings. Bike locations in the outlying communities still see usage, but at a much lesser rate.

#### *Start time of trips by hour*

![peak_times](https://user-images.githubusercontent.com/108373151/194726686-4c10b741-923b-4296-9311-59217a480c10.jpg)

This bar graph shows the peak time of starting trips is during the evening commute or as users begin to look for dinner locations. Usage is typically higher during the daytime hours, so a suggested maintenance period would be between 2 and 5am.

#### *Duration of trips separated by hour*

![duration_trips_hour](https://user-images.githubusercontent.com/108373151/194726694-b537c405-27a9-4ab1-984f-f8f4a487c61e.jpg)

This interactive graph shows the trip duration separated by hour. The snapshot included above suggests that the majority of trips taken between 12 and 1am are 5 minutes long. Investors will be able to easily change the default table shown for other times during the day.

#### *Duration of trips separated by hour and gender*

![duration_trips_hour_gender](https://user-images.githubusercontent.com/108373151/194726702-3a55d5c7-8a6b-4fa5-852b-716d715c1eda.jpg)

This interactive graph takes a similar approach to the graph above, but filters the data even more by gender. Of these 5 minute trips taken between 12 and 1am, the majority of users identify as male.

#### *User trips separated by weekday and hour*

![trips_weekday](https://user-images.githubusercontent.com/108373151/194726708-31f78b1f-ce03-4643-a794-fa398e5007fe.jpg)

This interactive heatmap shows the peak usage as it compares from a weekday to a weekend. Weekends see more evenly distributed usage throughout the day, while weekdays have high usage during commute times and less usage during the day..

#### *User trips separated by gedner, weekday and hour*

![trips_weekday_gender](https://user-images.githubusercontent.com/108373151/194726713-1ac312f2-4208-4c54-a2a4-a5b3ed10ae5e.jpg)

Again, this interactive heatmap takes a similar approach to the heatmap above, but takes it one step further by filtering on gender. It shows that individuals who identify as male are the heaviest users, not only during commute times, but also on the weekends.

#### *User trips separated by gender and type of user*

![trips_weekday_gender_type](https://user-images.githubusercontent.com/108373151/194726720-c746717f-adea-4fbb-afe3-8e64e49d4c76.jpg)

This interactive heatmap takes a similar approach to the two heatmaps above, but it focuses on those users who are subscribers versus regular customers. This heatmap shows the majority of users who identify as male are also subscribers.

## Summary

Considering the results of this data, I would recommend the majority of the bike shares be placed at or near downtown Des Moines, Iowa and popular attractions in the area. Tourists may want to use the bikes to get around rather than other available methods of transport. However, it seems like the majority of users are subscribers who use the bikes for regular commute to and from their workplace. Because of this, I would also recommend placing bike share stops around the community to be used for those regular commuters.

### Further Recommendations

- Separate the duration of trips into buckets. Suggested buckets could be 5 minutes or less, then in 10 minute increments after that. A bar graph of these buckets could determine how long of a bike ride that users are willing to take, and help identify any outliers. This analysis would create a radius of how far from downtown out into the suburban community to place bikes.

- Separation of starting locations of trips into hours. This would assist in determining the flow of bikes as people commute and the needed availability in specific locations during peak times and in peak locations.