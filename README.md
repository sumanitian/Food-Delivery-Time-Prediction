# Food-Delivery-Time-Prediction

An Machine Learning algorithms to predict the food delivery time based on how much time the delivery partners took for the same distance in the past.

We must determine the distance between the location of food preparation and the location of consumption in order to anticipate the timing of food delivery in real time. After determining the distance between the restaurant and the delivery sites, we must establish links between the lengths of time that previous delivery partners spent travelling the same distance to deliver meals.

The dataset lacks a characteristic that would distinguish between the delivery location and a restaurant. All we have are the restaurant's and the delivery location's latitude and longitude points. Based on two places' latitudes and longitudes, we may use the haversine formula to determine how far apart they are from one another.

Finding the relationship between the features.

Relationship between Distance and Time taken
![newplot](https://user-images.githubusercontent.com/70560551/231452338-fc62af6c-34d6-48ac-8a73-2cbed9b146a8.png)

The duration and distance travelled to deliver the food are consistently correlated. It implies that regardless of distance, the majority of delivery partners provide food in 25–30 minutes.

Relationship between time taken to deliver the food and the age


![newplot1](https://user-images.githubusercontent.com/70560551/231453865-03144810-4482-4483-889d-f510d15f2d13.png)

The age of the delivery partner and the time it takes to deliver the food are inversely correlated. It indicates that younger delivery partners need less time to deliver the food than do older ones.

Relationships between Time taken and Ratings

![newplot2](https://user-images.githubusercontent.com/70560551/231454281-8b86470a-5685-41a3-bb10-6653fd0ef7a0.png)

The amount of time it takes to deliver the food and the delivery partner's evaluations are inversely correlated. It implies that delivery services with higher ratings provide food faster than those with lower ratings.

![newplot3](https://user-images.githubusercontent.com/70560551/231457033-58120ae5-badb-4936-9371-5560bf30cf96.png)

Therefore, the amount of time required by delivery partners varies very slightly depending on the type of food they are delivering and the vehicle they are driving.
According to our data, the factors that affect meal delivery time the most are:

Age, rating and distance between the restaurant and the delivery location of the delivery partner


