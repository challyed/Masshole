Masshole
===========

# Street Safety Challenge aka Masshole.io
## Project Due Date: 12/30/2013

Using the public data provided design a web application that provides street safety information about the city of Boston.

This is being graded on creativity and how informative the application is.

### Sample questions reverb application could answer
* Where are unsafe intersections in Cambridge?
* What are the safest routes for cyclist with low levels of comfort riding a bicycle
* Where is it safe for children to bike or walk  to school

### More questions the application could answer
* What day or times do the most accidents happen?
* What type of mode of transportation is the most hazardous?
* What was the weather like? Was it raining, snowing?
* Do most accidents happen at night or day?
* What was traffic like?

#Design


# Day 1 thoughts

The opening page should talk about accidents and how they occur. Then we move on to the meat of the project. The final page should talk about how to prevent  accidents.

In addition, it would be cool if you can add Google map views (map view and Google car view)

# Day 3? thoughts
 Find the information 1st and then plan layout.
## Accidents information
* 8090 items

### Days of Accidents
* Monday = 830
* Tuesday = 867
* Wednesday = 841
* Thursday = 966
* Friday = 1004
* Saturday = 731
* Sunday = 574
* The most accidents happen on Friday with the least on Sunday

### Times of Accidents
* 2550 accidents happen in AM
* 3790 accidents happen in PM
* Most Accidents happen at night
### Years of Accidents
* ['2010',  1593],
* ['2011',  1708],
* ['2012',  1522],
* ['2013',  1517]

### Auto vs Object 2
* ['null',  3],
* ['Auto',  2385],
* ['Bicycle',  669],
* ['Bus (Other)',  8],
* ['Fixed Object',  297],
* ['MBTA Bus',  2],
* ['Miscellaneous',  32],
* ['Moped',  20],
* ['Motorcycle',  13],
* ['Parked Vehicle',  1778],
* ['Pedestrian',  389],
* ['School Bus',  8],
* ['Taxi',  72],
* ['Truck',  92],
* ['Van',  10]

### Van vs Object 2
* ['null',  0],
* ['Auto',  4],
* ['Bicycle',  669],
* ['Bus (Other)',  8],
* ['Fixed Object',  297],
* ['MBTA Bus',  2],
* ['Miscellaneous',  32],
* ['Moped',  20],
* ['Motorcycle',  13],
* ['Parked Vehicle',  1778],
* ['Pedestrian',  389],
* ['School Bus',  8],
* ['Taxi',  72],
* ['Truck',  92],
* ['Van',  10]

### Truck vs Object 2
* ['null',  1],
* ['Auto',  65],
* ['Bicycle',  13],
* ['Bus (Other)',  0],
* ['Fixed Object',  41],
* ['MBTA Bus',  0],
* ['Miscellaneous',  0],
* ['Moped',  0],
* ['Motorcycle',  1],
* ['Parked Vehicle',  61],
* ['Pedestrian',  7],
* ['School Bus',  0],
* ['Taxi',  3],
* ['Truck',  5],
* ['Van',  1]

### Taxi Vs Object 2
* ['null',  0],
* ['Auto',  66],
* ['Bicycle',  39],
* ['Bus (Other)',  4],
* ['Fixed Object',  10],
* ['MBTA Bus',  1],
* ['Miscellaneous',  0],
* ['Moped',  2],
* ['Motorcycle',  0],
* ['Parked Vehicle',  20],
* ['Pedestrian',  15],
* ['School Bus',  1],
* ['Taxi',  5],
* ['Truck',  4],
* ['Van',  2]

### School Bus vs Object 2
* ['null',  0],
* ['Auto',  9],
* ['Bicycle',  0],
* ['Bus (Other)',  0],
* ['Fixed Object',  0],
* ['MBTA Bus',  0],
* ['Miscellaneous',  0],
* ['Moped',  0],
* ['Motorcycle',  0],
* ['Parked Vehicle',  8],
* ['Pedestrian',  3],
* ['School Bus',  0],
* ['Taxi',  0],
* ['Truck',  0],
* ['Van',  0]

### Pedestrian vs Object 2
* ['null',  0],
* ['Auto',  1],
* ['Bicycle',  4],
* ['Bus (Other)',  0],
* ['Fixed Object',  0],
* ['MBTA Bus',  0],
* ['Miscellaneous',  0],
* ['Moped',  0],
* ['Motorcycle',  0],
* ['Parked Vehicle',  0],
* ['Pedestrian',  0],
* ['School Bus',  0],
* ['Taxi',  0],
* ['Truck',  0],
* ['Van',  0]

###  Motorcycle Vs Object 2
* ['null',  0],
* ['Auto',  13],
* ['Bicycle',  1],
* ['Bus (Other)',  0],
* ['Fixed Object',  4],
* ['MBTA Bus',  0],
* ['Miscellaneous',  4],
* ['Moped',  0],
* ['Motorcycle',  0],
* ['Parked Vehicle',  6],
* ['Pedestrian',  2],
* ['School Bus',  0],
* ['Taxi',  0],
* ['Truck',  0],
* ['Van',  0]

### Moped vs Object 2
* ['null',  1],
* ['Auto',  5],
* ['Bicycle',  1],
* ['Bus (Other)',  0],
* ['Fixed Object',  1],
* ['MBTA Bus',  0],
* ['Miscellaneous',  1],
* ['Moped',  0],
* ['Motorcycle',  0],
* ['Parked Vehicle',  2],
* ['Pedestrian',  0],
* ['School Bus',  0],
* ['Taxi',  0],
* ['Truck',  0],
* ['Van',  0]

### Miscellaneous Vs Object 2
* ['null',  0],
* ['Auto',  1],
* ['Bicycle',  0],
* ['Bus (Other)',  0],
* ['Fixed Object',  1],
* ['MBTA Bus',  0],
* ['Miscellaneous',  0],
* ['Moped',  0],
* ['Motorcycle',  0],
* ['Parked Vehicle',  0],
* ['Pedestrian',  0],
* ['School Bus',  0],
* ['Taxi',  0],
* ['Truck',  0],
* ['Van',  0]

### MBTA Bus Vs Object 2
* ['null',  0],
* ['Auto',  4],
* ['Bicycle',  1],
* ['Bus (Other)',  0],
* ['Fixed Object',  2],
* ['MBTA Bus',  0],
* ['Miscellaneous',  0],
* ['Moped',  0],
* ['Motorcycle',  0],
* ['Parked Vehicle',  3],
* ['Pedestrian',  3],
* ['School Bus',  0],
* ['Taxi',  0],
* ['Truck',  0],
* ['Van',  0]

### Bus (other) Vs object 2
* ['null',  0],
* ['Auto',  24],
* ['Bicycle',  7],
* ['Bus (Other)',  1],
* ['Fixed Object',  7],
* ['MBTA Bus',  0],
* ['Miscellaneous',  0],
* ['Moped',  0],
* ['Motorcycle',  0],
* ['Parked Vehicle',  23],
* ['Pedestrian',  4],
* ['School Bus',  0],
* ['Taxi',  1],
* ['Truck',  0],
* ['Van',  0]

### Bike Vs Object 2
* ['null',  3],
* ['Auto',  6],
* ['Bicycle',  1],
* ['Bus (Other)',  0],
* ['Fixed Object',  0],
* ['MBTA Bus',  0],
* ['Miscellaneous',  2,]
* ['Moped',  0],
* ['Motorcycle',  0],
* ['Parked Vehicle',  9],
* ['Pedestrian',  4],
* ['School Bus',  0],
* ['Taxi',  2],
* ['Truck',  0],
* ['Van',  0]

# Day 4 Thoughts
I have no idea how to approach this project like a data scientist. Im going to stop by the hardvard book store.

select count(*) as AutoVAuto from TestCambridgeData
where `Day of Week` = "Auto" and `Object 1` = "Van"
