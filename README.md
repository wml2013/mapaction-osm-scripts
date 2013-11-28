mapaction-osm-scripts
=====================
This contains the first couple of scripts that downloads OpenStreetMap Planet Files (PBF) from Geofrabrik. It then performs a difference between the hourly planet files, generate a change-only file called a 'difference file'. This diff file is then extracted and compressed ready to be sent to a MapAction field team to apply the difference file, to their copy of OSM in order to update it. 
