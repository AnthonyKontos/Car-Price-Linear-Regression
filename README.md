# Car-Price-Linear-Regression
In this analysis we will be building a linear regression model to understand the drivers which influence car prices. 

## Conclusion
diesel vehicles sold by individual sellers have the most kms driven of all groups, perhaps because diesel vehicles
appeal to long distance drivers who rely on disel to travel on a single tank. On the other hand Manual drivers of Petrol
vehicles have the least Kms_Driven -- likely because manual transmission vehicles are not as common anymore and appeal
more to car enthusiasts rather than everyday drivers. In the case of diesel vehicles, there is a clear preference for older vehicles.

Most cars -- new or old -- have a current used value between 0 and 7k euros. However there are significantly more newer used cars worth 7k+ than older cars worth the same amount.
Older cars have more kms driven than newer cars as we should expect, while newer cars are generally more costly than older cars when sold brand new however
a few more older cars than newer cars sell for 16-27k euros, possibly due to rarity or vintageness. As kms driven increase, sellling price decreases -- the biggest drop occuring past 40k kms driven for New cars
In old cars there is more variability or more anomalies due to the fact that cars might become more rare, more 'vintage', and thus worth more.

## How This Model Can Be Made Better
We could make the model better by incorporating other variables related to assumptions or conclusions made in our explanatory analysis.
For instance, we might want to first exclude outliers of old cars that have a high selling price due to rarity or vintageness as opposed to 
their intrinsic worth (i.e., quality of mechanical system, technological upgrades, more safety features). In this instance, some other variables 
we might want to include in our analysis is 'Car rarity'. As a car's rarity increases we should find that its selling price also increases.
However we should excercise caution when considering new variables for our regression as the model may become overfitted and its predictive power will decrease. 
