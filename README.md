# Coursera_Capstone
Coursera_Capstone

Capstone Project - Food Delivery from Restaurants
In recent times the restaurant's food delivery model has changed drastically. The online ordering facility offered more options and convenience, so more and more consumers are opting for the online ordering.This has affected the operations of the restaurants and has given different new challenges to the restaurant owners.Now it is hardly possible for restaurant owner alone to handle the orders and also to provide the logistics, to deliver the consumers demand.so they are outsourcing the delivery activities to third party.

In traditional online delivery system, The online platform simply take orders from consumers and route them to restaurants which handle the delivery themselves.In contrast, recently new-delivery players build their own logistics networks, providing delivery for restaurants that don’t have their own drivers.In this new delivery system there are many challenges we can think of, examples are as below.

Orders consolidation
Orders clustering based on the restaurant and consumer locations
Fleet optimization
Route optimization
Business scenario validations
Drivers management etc.
Business Problem: As mentioned above,In this project I would like to address the following challenges faced by the restaurants logistics service providers.

Orders clustering based on the restaurant and consumer locations : After consolidating the orders from different online portals for the different restaurants, the orders needs to be clustered so that they can be assigned to the drivers/bike riders taking into consideration the vehicle carrying capacity,time required to deliver the food item, locations of the restaurants and consumers.The scope this project will be restricted to the clustering based on the locations only.
Route Optimization : As the service provides will have more number of restaurants( source) and consumer(destinations) locations, to meet the demand of the consumer the traveling path needs to be optimized in real time to keep the delivery cost as low as possible.

Data and Assumptions: To simplify the problem complexity , following assumptions are made.The solution developed in this project can be used as the basis to add on additional requirements based on different scenarios.

In order clustering the k-mean method is used to cluster the restuarant and consumers based on the locations.No other considerationsare done like food quality, food temparature zone , priority order etc, These can be taken while enhancing the model in future.

The consumer locations are dummy for for this project , This information could be taken from the online platform for the different restaurants while implementing in the real time scenarios.

The restaurant locations are taken from the Foresqare API , depending on the scope of the delivery of the logistics provider company

unlimited vehicle carrying capacity is assumed for route optimization.

Euclidian distances are considered for the calculations, this problem can be enhanced by taking the driving distances also.

delivery windows are assumed to be at any hour of the day
References:https://www.mckinsey.com/industries/high-tech/our-insights/the-changing-market-for-food-delivery