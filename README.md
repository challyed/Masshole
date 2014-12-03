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
## Accidents information
* 8090 items
* Monday = 830
* Tuesday = 867
* Wednesday = 841
* Thursday = 966
* Friday = 1004
* Saturday = 731
* Sunday = 574
* The most accidents happen on Friday with the least on Sunday
* 2550 accidents happen in AM
* 3790 accidents happen in PM
* Cars vs Vans = 10
'''
select count(*) as AutoVVAN from TestCambridgeData
where `Object 1` = "Auto" and `Object 2` = "Van"
'''
