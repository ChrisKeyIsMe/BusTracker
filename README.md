# BusTracker
A program that tracks a bus route in real time.
This program requires the use of MapBox, an open-source platform that allows you to create and display maps on a web page.
In order to access the map data, you will need to create a Mapbox account (it's free!) by going to Mapbox.com
Create an account, then go to 'Tokens' to access your Default Public Token. Copy this token and paste it in mapanimation.js where it says "mapboxgl.accessToken"
After saving the mapanimation.js file with your own token, load it in a browser. You should see a map and a single blue marker. 
Click the "Show stops between MIT and Harvard" button to begin your journey!
Future fixes: I'd like to do various other maps, though I will need to find the coordinates. You can change the location by editing the coordinates in the busStops constant. Just make sure you know where you're going!
