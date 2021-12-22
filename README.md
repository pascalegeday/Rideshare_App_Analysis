# Rideshare App "Pyber" Analysis
In this project, I was tasked with assisting data analyst at Pyber by producing analysis and visualizations of Pyber data from January to early May of 2019 and create a compelling visualization for the CEO of Pyber. Thus, giving insight on way in which Pyber can improve access to ride-sharing services and determine affordability for under-served neighborhoods. 

# Resources
* Data Source: Pyber_ride_data.csv & city-data.csv & ride_data.csv
* Software: Python 3.8.9, Jupyter Notebook 6.4.6
* Tools: Matplotlib Library

# Results
Key components of this project were to create a ride-sharing summary by city type and a multiple-line chart of total fares for each city type (see below). 
By analyzing these components, among many, we can make business recommendations to the Pyber CEO for addressing any disparities among the city types. 

## Pyber Summary By City Type
![Pyber_summary_df](https://user-images.githubusercontent.com/94571150/147039398-d8cead27-c7b9-4f30-ae60-f0ee1d39ab69.png)
## Pyber Chart By Total Fare By Each City Type
![Pyber_fare_summary](https://user-images.githubusercontent.com/94571150/147039421-229bfe5d-c038-41a0-bf96-185ef46e8e8e.png)
##
![Fig1](https://user-images.githubusercontent.com/94571150/147041816-8c1bc9fe-70e9-4484-a95a-2f93f4b976de.png)

# Summary
* Rural cities have the least total rides(125) and number of drivers (78) among the three city types. However, the average fare per ride($34.62) and the average fare per driver($55.49) is significantly higher than suburban and urban cities. This may be due to the fact that riders in rural cities need to travel farther distances, hence, the increase in fare. Another notable finding is that due to there being a small number drivers, there is less access to rides in rural cities so they are not creating as much revenue. Also, when rides do take place, they come at a significantly more expensive fare rate. This could prevent future riders, as some may not be willing to pay higher fares. 
* Suburban cities have a relatively low total rides (625) in comparison to the number of drivers(490). However, the average fare per ride ($30.97) in comparison to the average fare per driver ($39.50) is shows healthier balance in revenue in suburban cities than in urban or rural cities. This may mean that there are other driving factors to riders not having access to Pyber in Suburban areas. 
* Urban cities have a significantly higher amount of drivers(2,405) than any other city type. When looking at this number, you may assume that the total rides for urban cities must be significantly higher in comparison, however, that is not the case. In urban and rural city types, total rides is always more than total drivers, showing a somewhat balanced demand. However, urban cities have almost double the amount of drivers than they do rides. Also, the average fare per driver is significantly lower in comparison to the average fare per ride. 
# Business Recommendations
1. Increase the number of drivers in rural cities. If there are more drivers, riders will have increased access to Pyber and the total fares may increase. Also, if there is more access to drivers, it may drive the fare per ride down as well which may lead to more riders willing to pay fares. 
2. Increase advertising in suburban cities to draw in a bigger market of potential riders. This may increase the amount of total rides and increase revenue for Pyber. 
3. Decrease the number of drivers in urban cities. There is a surplus of supply and not enough demand. This is most likely causing Pyber to lose money and driver retention. By decreasing the number of drivers, each driver will also receive better pay per ride and will be more likely to remain in his/her job as a driver. 

