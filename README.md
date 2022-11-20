# Solution Overview
This solution helps a user in finding driving/walking directions between point A and point B.

# Description
User has to provide following inputs-Start Location ( Origin Lat, Origin Lng), Destination Location ( Destination Lat, Destination Lng), travel mode. Based on user input driving/walking directions between Origin Location and Destination Location are showcased on the maps interface.
Sequence-
1.	User provides input for Origin Lat and Origin Lng.
2.	User then provides input for Destination Lat and Destination Lng.
3.	User then chooses travel mode by clicking on relevant button against- Walking/Driving. 
4.	After that user clicks ‘Calculate Directions’.

To provide Start Location as input, user has 3 ways-
a.	Provide Origin Lat and Origin Lng manually
b.	Click on ‘Current Location’ button to get browser location.
c.	Click on the maps interface and the corresponding lat/long gets filled in the Origin Lat and Origin Lng.

 To provide Destination Location as input, user has 2 ways-
a.	Provide Destination Lat and Destination Lng manually
b.	Click on the maps interface and the corresponding lat/long gets filled in the Origin Lat and Origin Lng.

# Testing Requirements
This solution needs a web server to run the file DirectionsServiceExample2.html. It has been tested on Google Chrome.

# Assumptions
User will refresh the application after completion of each successful transaction when directions are fetched between Origin and Destination.
User will follow only one method unilaterally to provide inputs- 
a. If current location is pressed then Destination Lat and Destination Lng will be given manually.
b. Provide   Origin Lat and Origin Lng manually
c. Click on maps interface for Origin Lat ,Origin Lng and Destination Lat, Destination Lng. 


