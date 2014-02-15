Project-Russia
==============

Scenery of Russia for FlightGear Flight simulator.

Installation:
1. Open "Custom_materials" folder and merge data inside it with $FGDATA folder. It will not overwrite any data in your $FGDATA folder.
2. For better aeronavigation, freshest data on airports, presented in this scenery pack it's better to merge data in folder aeronav/fgdata. In this step some data in $FGDATA will be overwritten, but with equal or more fresh data.

Running:
If you run FG via commandline, you need to add 2 things:
1. Add path to scenery: --fg-scenery=/home/path-to-scenery/Project-Russia (my example with terrasync data: --fg-scenery=/home/soitanen/Project-Russia:/home/soitanen/Terrasync)
2. Add custom materials (textured roads, railroads and some other) for use: --materials-file=/Materials/regions/russia.xml

Information:
Scenery is based on OSM linear and polygonal data. Currently it have this list of airports (may be different degree of quality):
* UG23 - Gudauta, Abkzhazia
* UL0A
* ULDA
* ULLI - Saint-Petersburg, Pulkovo
* ULLP
* ULLV
* ULLY
* ULSC
* ULSG
* ULSK
* ULSM
* URKG - Gelendzhik
* URMT
* URRR - Rostov-na-Donu
* URRW
* URSS - Sochi, Adler
