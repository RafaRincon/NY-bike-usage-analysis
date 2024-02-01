<b>Description</b>

<p align="center">
<img align="center" width="400" height="300" src="https://images.ctfassets.net/1aemqu6a6t65/3OarGhpmhAjQSgd6fixGkH/3db0d25107cac87f9c9150429f155f1c/citibike_joebuglewicz_3315?w=1200&h=800&q=75">
</p>

<p align="justify">In Los Angeles, there exists a shared bicycle system that provides anonymous data about the usage of the service it offers. The provided table contains the historical records of trips conducted over approximately 9 months, with a particular column of interest that will be analyzed in greater depth: Passholder_type. Below are the columns present in the table:

* trip_id: Unique identifier for the trip
* duration: Trip duration in minutes
* start_time: Day/hour when the trip begins in ISO 8601 local time format
* end_time: Day/hour when the trip ends in ISO 8601 local time format
* start_station: The station where the trip started
* start_lat: The latitude of the station where the trip originated
* start_lon: The longitude of the station where the trip originated
* end_station: The station where the trip ended
* end_lat: The latitude of the station where the trip ended
* end_lon: The longitude of the station where the trip ended
* bike_id: A unique integer identifying the bicycle
* plan_duration: Number of days the user will have the pass. 0 means a single trip (Walk-up plan)
* trip_route_category: "Round trip" refers to trips that start and end at the same station
* passholder_type: The name of the passholder plan
  
Data is available in https://www.kaggle.com/competitions/ds-programming-test/data

For the analytical problem, the goal is to determine if it is possible to infer whether the pass type is a "Monthly Pass" considering the other travel variables. 
 
 <b>Note</b>: This challenge is part of a Kaggle competition.</p>
