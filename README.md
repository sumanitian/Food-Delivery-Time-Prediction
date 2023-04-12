# Food-Delivery-Time-Prediction

An Machine Learning algorithms to predict the food delivery time based on how much time the delivery partners took for the same distance in the past.

To predict the food delivery time in real time, we need to calculate the distance between the food preparation point and the point of food consumption. After finding the distance between the restaurant and the delivery locations, we need to find relationships between the time taken by delivery partners to deliver the food in the past for the same distance.

The dataset doesn’t have any feature that shows the difference between the restaurant and the delivery location. All we have are the latitude and longitude points of the restaurant and the delivery location. We can use the haversine formula to calculate the distance between two locations based on their latitudes and longitudes.

Relationship between Distance and Time taken
![newplot](https://user-images.githubusercontent.com/70560551/231452338-fc62af6c-34d6-48ac-8a73-2cbed9b146a8.png)

There is a consistent relationship between the time taken and the distance travelled to deliver the food. It means that most delivery partners deliver food within 25-30 minutes, regardless of distance.
