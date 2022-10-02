# Analysis of Ford GoBike System Data from Feb 2019
## by Aryan Talathi


## Dataset

> Ford GoBike) is a regional public bike sharing system in the San Francisco Bay Area, California. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States with nearly 500,000 rides since the launch in 2017 and had about 10,000 annual subscribers as of January 2018. This data set includes information about individual rides made in a bike-sharing system, covering the greater San Francisco Bay area, in the month of February 2019. The dataset is available in .csv format.

> Some of the important features present in the dataset are:

> - Trip Duration
> - Trip Start Time
> - Trip End Time
> - Member Birth Year
> - Member Gender
> - User Type
> - Bike Sharing status

## Summary of Findings

> The distribution of Trip Duration is heavily right-skewed. Applying Log scale transformation helped to normalise the distribution.
> The distribution of member age is also slightly right-skewed. Most of the members are younger: 18-40 years.
> People take more trips during peak hours of the day, which are 7-10 in the morning and 16-19 in the evening. Very less trips are taken during night hours.
> More trips are taken on week-days compared to weekends.
> Most of the users are subscribers and most common gender is Male.
> 90% of the rides are not shared.

> No significant correlation between any numeric variables.
> Younger people tend to take longer trips.
> The trip-duration is normally distributed wrt hour of the day. Most longer trips are taken during mid-day 8-20 hours & peaking at 14-15 hours.
> Bike rides during weekends have longer durations.
> Older people tend to take more rides during day time. Rides during night hours are mostly taken by younger people.
> Female users ride bikes for slightly longer duration compared to Males. And, other genders also have longer rides compared to Males.
> Customer do longer rides than Subscribers.
> Naturally Shared rides are somewhat shorter than non-shared rides. People who are younger take shared rides more.
> For Saturdays and Sundays, bike rides don't have any peak hours. More rides occur during mid-day hours for these days. But for weekdays, bike rides are more during peak hours.

> Subscribers use the system heavily on work days i.e. Monday through Friday whereas customers ride a lot on weekends. Male Subscribers take trips mostly on week-days, Male customers take trips on all days. Female subscribers also take trips on all days (relatively less on weekends)
> For weekdays the duration of trip is longer and more number of rides take place during the 8-10 and 15-20 hours intervals. For weekends rides are evenly distributed between 8-20 hour interval in general.
> Younger Females take longer rides than younger Males, whereas more older Males take longer rides than older Females. Males take longer rides on Saturdays, whereas Females take longer rides on Sundays.

## Key Insights for Presentation

1)  Distribution of Trip Duration
> The distribution of Trip Duration has a heavy right skew. Durations range from less than 1 minute to 1400+ minutes with median at around 9 min and mean at around 12 min. (Applied Log transformation has made the plot telligible.)

2) Trip Duration for rides taken at every Hour of the Day
> The trip duration differs significantly wrt the hour of the day. The distribution here is almost a uni-modal one with a major peak in between 14th - 15th hour of the day. The duration is the least at around 2nd - 3rd hour at night. Bike rides between 8 am to 9 pm are the longest and nightime has the shortest rides.

3) Number of rides per Hour of the Day for Subsribers and Customers
> For Saturdays and Sundays, bike rides don't have any peak hours. More rides occur during mid-day hours for these days. But for weekdays, bike rides are more during peak hours. Subscribers take more trips on peak hours during week days. They take relatively less trips on weekends comapred to peak hours of week-days. Customers tend to take more trips on weekends and peak during mid day hours.

4) Duration against Member Age for each User Type
> There isn't any linear relation between Age and Duration. Although, it is seen that most of the high duration trips are done by people from 20-60 years age. Customers take long duration rides than Subscribers of relatively same age. Customers are generally younger than subscribers. Subscribers vary from 18-60yrs, whereas customers vary from 18-45yrs

5) Trip Duration for every 24 Hours against 7 Days of the week, for each gender
> Duration of the rides is longer on weekends overall. For weekdays the duration is longer and more number of rides take place during the 8-10 and 15-20 hours intervals. For weekends rides are evenly distributed between 8-20 hour interval in general. Female bikers bike longer on average compared to male bikers.
