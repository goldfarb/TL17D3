## Mistakes I've Made
##  while trying to make a map ##
## _and you can too_ ##

****

What you'll need:  
+ a terminal runnin  `python -m SimpleHTTPServer`  
+ data -- try   
  + https://www.capitalbikeshare.com/system-data
  + https://www.census.gov/geo/maps-data/data/tiger-line.html

What you'll want:  
+ to use the console in chrome

****

minimum viable geojson:

`{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {},
      "geometry": {
        "type": "Point",
        "coordinates": [
          -77.0112927,
          38.8901562
        ]
      }
    }
  ]
}`


****

_I'm sure this worked before_

having access to my own github repository

matching [], {}, and so forth

= ≠ ==

lon, lat vs. lat, lon

***


_incredibly useful resources_

Testing geojson - http://geojson.io/

More than you want to know about D3 - https://d3js.org/
