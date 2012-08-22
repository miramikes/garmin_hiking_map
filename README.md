garmin_hiking_map
=================

OSM hiking Garmin map

This mkgmap style files were created to build map with
as many as possible details useful for hiking and outdoor activities.
This map is not routeable. MAybe in future.

Many thanks to people on Garmin OSM forum for answering all my stupid questions.
http://forum.openstreetmap.org/viewforum.php?id=26

Thanks for inspiration to:

ligfietser
https://sites.google.com/site/openfietsmap/ 

Lambertus
http://garmin.openstreetmap.nl

Marko Mäkelä
http://www.polkupyoraily.net/osm/

csdf
http://www.cferrero.net

extremecarver
http://openmtbmap.org

vibrog
https://github.com/vibrog

aighes
http://www.aighes.de/OSM/index.php

Building a map
java -ea -Xmx6144m -jar mkgmap-r2316/mkgmap.jar mira.TYP --precomp-sea=/precompiled/sea/files/dir/ --style-file=mira-style/ -c mira-style/arguments LAND/6324*.osm.pbf CONTOUR/contour*.osm.pbf
