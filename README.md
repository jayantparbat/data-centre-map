This little map experiment uses Turf.js and Mapbox to create dynamic hub and spoke maps. It uses code written by William B. Davis and then adapted by Garrett Dash Nelson - and then tweaked by me. 
I compiled the data centre location list myself and I used AI to format the data into a geojson file. 

If you want to make your own, all you need to do is put a json file in the folder with data you want to use, change the name of the json file in index.html to match the name of your own file, and then edit line 81 so that it references a unique column in your json file.

Note: the data centre locations data was last updated on June 2025. The location data was obtained from the DataCenterMap website and the coordinates were obtained OpenCage API.
