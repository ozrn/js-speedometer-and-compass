# JS30 #21: js-speedometer-and-compass
This is one of the JS30 projects by Wes Bos. It demonstrates how to get a user's location using Geolocation API.
## Overview
* In this project, there is a compass that indicates how many degrees of north are we currently at and also a speed indicator showing the kilometers per hour that we're running on.
* We'll be able to track data as frequently as we need it because watchPosition method will watch our location over time using navigator.geolocation.watchPosition(). In other words, it will provide us with GeolocationPosition object that will give us heading and speed values for our compass and speed indicator.
* The heading is the number of degrees relative to north that we are and the speed is at kilometers per hour. After we retrieve this info, we will rotate the compass based on the heading value and set the text content of speed to the speed value.
* By providing a callback function, we will be able to handle an error in case there is any error.
