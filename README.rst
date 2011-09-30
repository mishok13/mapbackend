This is an experiment in building map backends over a weekend

What's to implement
===================

* Tiles
* Geocoding
* Reverse geocoding
* Free-form geocoding
* Place tagging (through JS libs)
* Routing for bikes and pedestrian
* Routing for cars
* Staticmaps

How to start
============

All of these have to use OpenStreetMap data. Links for getting OSM data (huge amounts):

http://downloads.cloudmade.com/europe/
http://download.geofabrik.de/osm/europe/

How to load data into PostGIS (or any other data storage of your liking):
http://wiki.openstreetmap.org/wiki/Planet.osm#Technical_notes

Common building blocks:

Mapnik
  Rendering library

Nominatim
  Structured geocoding framework

Open Source Routing Machine
  Good example of Contraction Hierarchies algorithm implementation. Unfortunately, license is as bad as it can be (AGPL).
