# akkiblockyassignment
Assignment: Frontend Developer Intern – Vehicle Movement on a Map
Objective
Build a frontend-only web application that simulates a vehicle moving on a map. The
application should display the vehicle's live position and draw its route using dummy
data. You may use any modern frontend framework or vanilla JavaScript, along with a
mapping library of your choice.
Expectations
You can refer to this video for a visual idea of what is expected:
https://www.youtube.com/watch?v=0r0IMQvC1No
Requirements
1. Map Integration
● Use a mapping library such as Google Maps JavaScript API, Leaflet, Mapbox GL JS,
or similar.
● Display a map view centered on a predefined route.
● Place a vehicle marker on the map that updates its position in a simulated
real-time manner.
● Draw the route path using a polyline or equivalent.

2. Dummy Location Data
● Create a local static JSON file (dummy-route.json) that contains a list of latitude
and longitude points to simulate vehicle movement.
● Each entry can optionally include a timestamp.

Example format:
[
{ "latitude": 17.385044, "longitude": 78.486671, "timestamp": "2024-07-20T10:00:00Z" },
{ "latitude": 17.385045, "longitude": 78.486672, "timestamp": "2024-07-20T10:00:05Z" },
{ "latitude": 17.385050, "longitude": 78.486680, "timestamp": "2024-07-20T10:00:10Z" }
]
This data should be fetched from the frontend and processed to simulate movement
along the route.
3. Simulated Real-Time Movement
● Update the vehicle marker's location every few seconds.
● Animate the movement smoothly if possible.
● Extend the route path on the map as the vehicle moves forward.
4. Interface and Features
● Provide basic controls such as play/pause to control the movement simulation.
● Optionally display metadata such as:
○ Current coordinate
○ Elapsed time or timestamp
○ Speed (if timestamp data is used)
● Ensure the UI is responsive and works on both desktop and mobile browsers.

Suggestions (Optional Enhancements)
● Use the Google Polyline Utility or Valhalla Polyline Demo to generate
encoded polyline data.
● Consider mocking a directions response using APIs such as:
○ Google Maps Directions API
○ Mapbox Directions API

Evaluation Criteria
● Code Structure & Quality: Organized, modular, and well-documented code
● Functionality: Accurate and smooth simulation of vehicle movement
● User Interface: Clean, usable, and responsive frontend design
● Flexibility: Ability to extend the solution with additional features or vehicles
