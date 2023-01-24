# Real-Time Bus Tracking Exercise

## This web page is an example of how to use JavaScript to (1) render a map on a web page and (2) build and manipulate maps on web pages.  

It's a good way to work with the DOM in JavaScript

Adding animation to maps mapbox is an open-source platform 
that allows a user to create and display maps on a web page. 
The mapboxgl JavaScript library is part of the Mapbox ecosystem. 
It allows a user to add all sorts of customizations to the map.
Examples are: animated pointers, markers, and all sorts of things.

To be more specific, we used the MBTA bus data to determine stops between Harvard and MIT. We then, added an animated marker on the map to 
highlight the bus routes. 

How?
(1) I created a Mapbox account and get the access token 
(2) I then added the access token to the mapboxgl instance
 defined in the mapanimation.js
(3) Lastly, I created a marker and add it to the map using the 
mapboxgl pre-built functions
 
 The function move() is called when the button 
 "Show stops between MIT and Harvard" is selected. 
 This is how we start the marker animation. 
 
 When the code is executed, we see a marker moving from one bus stop to 
 the next on the map. 
 
