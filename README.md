# CLEAN_WRANGLE
## First Take on Cleaning and Wrangling Raw Data

The task was meant to explore the dataset and try to fix any irregularities and anomalies presented in the data as much as we can. It was done with some statistical tests, Exploratory Data Analysis, and trying to predict a missed-match column with machine learning algorithm. 

## The Dataset
The dataset in this project consists of delivering packages using drones in Victoria, Australia. The description of
each data column is shown below.

* Id: A unique id for the delivery
* Drone type: A categorical attribute for the type of the drone. We know that
each type of drone has three phases of flight ( namely takeOff ,
onRoute , and Landing ). The drone may have different speeds at
different phases. takeOff and Landing phases only take five
minutes.
* Post type: A categorical attribute for the type of delivery (0:normal,
1:express)
* Package weight: The weight of the package
* Origin region: A categorical attribute representing the region for the origin of the
delivery
* Destination region: A categorical attribute representing the region for the destination
of the delivery
* Origin latitude: Latitude of the origin
* Origin longitude: Longitude of the origin
* Destination latitude: Latitude of the destination
* Destination longitude: Longitude of the destination
* Distance: Distance of the journey
* Departure date: Date of the departure
* Departure time: Time of the departure. We know that the delivery company has a
specific rule to define morning (6:00:00 - 11:59:59), afternoon
(12:00:00 - 20:59:59), and night (21:00 - 5:59:59)
* Travel time: Travel time (i.e., duration) of the journey
* Delivery time: The time of the delivery
* Delivery price: Delivery fare. We know that the fare has a linear relation with
some of the attributes of the dataset.

## Some hints on the data
1. The radius of the earth is 6378 km.
2. There is at least one error in the dataset from each category of the data anomalies (i.e.,
syntactic, semantic, and coverage).
