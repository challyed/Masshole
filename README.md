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

### Object 1 vs Vans
* Cars vs Vans = 10
* sql select count(*) as AutoVVAN from TestCambridgeData
where `Object 1` = "Auto" and `Object 2` = "Van"
* Trucks vs Vans = 1
* select count(*) as TruckVVAN from TestCambridgeData
where `Object 1` = "Truck" and `Object 2` = "Van"
* Taxi vs Vans = 2
* select count(*) as TaxiVVAN from TestCambridgeData
where `Object 1` = "Taxi" and `Object 2` = "Van"
* School bus vs Van = 0
* select count(*) as SchoolbusVVAN from TestCambridgeData
where `Object 1` = "School Bus" and `Object 2` = "Van"
* Pedestrian vs Van = 0
select count(*) as PedestrianVVAN from TestCambridgeData
where `Object 1` = "Pedestrian" and `Object 2` = "Van"
* Motorcycle v Vans = 0
* select count(*) as MotorcycleVVAN from TestCambridgeData
where `Object 1` = "Motorcycle" and `Object 2` = "Van"
* Moped vs Van
* select count(*) as MopedVVAN from TestCambridgeData
where `Object 1` = "Moped" and `Object 2` = "Van"
* Miscellaneous vs Van = 0
* select count(*) as MiscellaneousVVAN from TestCambridgeData
where `Object 1` = "Miscellaneous" and `Object 2` = "Van"
* MBTA Bus vs Van = 0
* select count(*) as MBTAbusSVVAN from TestCambridgeData
where `Object 1` = "MBTA Bus" and `Object 2` = "Van"
* Bus (Other) vs van = 0
* select count(*) as busotherVVAN from TestCambridgeData
where `Object 1` = "Bus (Other)" and `Object 2` = "Van"
* Bicycle vs Van = 0
* select count(*) as BicycleVVAN from TestCambridgeData
where `Object 1` = "Bicycle" and `Object 2` = "Van"

### Object 1 vs Auto
* Auto v Auto = 2385
* select count(*) as AutoVAuto from TestCambridgeData
where `Object 1` = "Auto" and `Object 2` = "Auto"
* Bicycle v Auto = 6
*  select count(*) as BicycleVAuto from TestCambridgeData
where `Object 1` = "Bicycle" and `Object 2` = "Auto"
* Bus (Other) v Auto = 24
*  select count(*) as BusOtherVAuto from TestCambridgeData
where `Object 1` = "Bus (Other)" and `Object 2` = "Auto"
* MBTA Bus V Auto = 4
*  select count(*) as MBTABusVAuto from TestCambridgeData
where `Object 1` = "MBTA Bus" and `Object 2` = "Auto"
* Miscellaneous V Auto = 1
* select count(*) as MiscellaneousVAuto from TestCambridgeData
where `Object 1` = "Miscellaneous" and `Object 2` = "Auto"
* Moped V Auto =
*  select count(*) as MopedVAuto from TestCambridgeData
where `Object 1` = "Moped" and `Object 2` = "Auto"
* =




# Day 4 Thoughts
I have no idea how to approach this project like a data scientist. Im going to stop by the hardvard book store.
