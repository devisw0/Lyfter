# minor-project-group25
minor-project-group25 created by GitHub Classroom 

Lyfter is an app-based personal vehicle system (i.e., ride-hailing), and they approach your team for help in designing a system that allows 
them to efficiently match riders to drivers. They want your team to help them claim “the wait time is never more than 5 minutes”, and thus 
in determining how many drivers they should recruit if they anticipate 100 riders at any instant of time.  

The code that was written takes in a random coordinate that it picks from a given range with in a city in this example it is San Jose in California, 
and assigns that to a rider and repeats that 100 times.
Then the alogrithim takes another random coordinate and assigns it to a driver and repeats it more times than the riders inorder to have more
drivers than riders so that there is closer drivers to choose from for each rider

Then the algorithim takes all 100 riders in an array and goes through each and goes through all of the drivers one by one and matches the closest
driver and goes on to the next rider until each rider is matched with the closest rider.

Then the shortest route is found using osmnx to track on actual roads not just using a stright line to connect two points.
The length of the trip is found in meters and from it the time is calculated in minutes.
The loop and calculations are run 100 times to account for the 100 riders.

There could be many ways this algorithim can be used for example using geopy to be able to search for locations using normal names and not having to use
coordinates. Or using a csv file instead of having the alogrithim pick randomly itself. There can be different types of maps printed out for the routes, 
there can be different modes to calculate travels by for example here it was optimized by time, it can be optimized by distance, or it can be made to 
use bike ways or walking instead of driving.
