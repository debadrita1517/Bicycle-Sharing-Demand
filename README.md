# Bicycle-Sharing-Demand
### |Domain –Transportation Industry|

## Business challenge/requirement :
With the spike in pollution levels and the fuel prices, many Bicycle Sharing Programs are
running around the world. Bicycle sharing systems are a means of renting bicycles where
the process of obtaining membership, rental and bike return is automated via a network
of joint locations throughout the city. Using this system people can rent a bike from one
location and return it to a different place as and when needed.

## Data Set :
Data contains hourly rental data spanning two years. Training set comprised of the first
19 days of each month while the test set is the 20th to the end of month.

## Considerations :
You are building a Bicycle Sharing demand forecasting service that combines historical
usage patterns with weather data to forecast the Bicycle rental demand in real-time. To
develop this system, you must first explore the dataset and build a model. Once it’s done
you must persist the model and then on each request run a Spark job to load the model
and make predictions on each Spark Streaming request.
