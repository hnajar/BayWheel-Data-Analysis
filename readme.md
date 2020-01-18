# Bay Wheel (Lyft) Bike share dataset
## by Hadi Najar


## Dataset

> The dataset I have analyzed is from Bay Wheel for the monthe of November 2019. It contains data like duration of the trip, user types, start and end latitude and longitude, and whether the user uses the bike share for the entire trip or not. I will be looking at a few of these variables and share my findings here. 


## Summary of Findings

> Most of the users, have an use duration of ~600 seconds or 10 min. Some users have used the bikes for as little as 1 min and as long as 86 ksec or 24 hrs.
> 77.4% of the users are members and the rest use the bike share casually.
> Only 7.5% of the users use bike share for their entire trip.
> Used Haversine formula to calculate the distance traveled using start and end latitude and longitude.
> Most users traveled an average of 1.5-2 km in this month.
> there is just a bit of correlation between the distance traveled and the duration when put in the log scale. This suggestions that, although weak, the speed at which the users travel are somewhat correlated.
> The distance traveled and the duration can be very small. Thus the tail of the violin plots are very stretched.
> There is much more variation in `Subscriber` user-type with distance traveled median almost the same for both user types. The large distance traveled variation for `Subscriber` was not surprising since 77.4% of the user type data are subscribers.
> The duration for `Subscriber` has a lower median than `Customer` and almost the same variation. However, the lateral size of the violin plot expresses that there is a lot more `Subscriber`with duration of about 100-1000 seconds compared with `Customer`.
> The distance traveled for most of the users who use bike share for all the trip, is around 1km where are it is more spread out for those who do not use bike share for all trip. Furthermore, the median of the distance traveled for the latter case is higher than the former case. Keep in mind that 92.5% of the users do NOT use bike share for all trip. 
> The users who do not use bike share for entire trip, on average spend longer time biking that those who do. This may mean that there is a small fraction of users that use bike share to get to their destination because their destination is very close to the starting point or they generally bike faster. 
> All the `Customers` use bike share system for their entire trip.
> For those who are not using bike share for the entire trip and are subscribers, the correlation seems to be the strongest and is the weakest for the subscribers who do not use bike share for their entire trip.

## Key Insights for Presentation

> I focused on summarizing and presenting duration distribution of users. The duration of most users are ~600 seconds or 10 min. Some users have used the bikes for as little as 1 min and some other as long as 86 ksec or 24 hrs.
> I also presented Proportions of user types and proportion of those who use bike share for their entire trip or not. It turns out 77.4% are Subscribers and only 7.5% use the share system for their entire trip.
> I also looked at distance to duration correlation.