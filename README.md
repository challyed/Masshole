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




# Day 4 Thoughts
I have no idea how to approach this project like a data scientist. Im going to stop by the hardvard book store.

select count(*) as AutoVAuto from TestCambridgeData
where `Day of Week` = "Auto" and `Object 1` = "Van"
