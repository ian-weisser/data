data
====

This repository is probably what you are looking for.

The data repository contains weather database tables for you to import.

metar.csv - A lookup table of worldwide METAR weather observation sites,
organized by latitude/longitude.
Source: http://weather.noaa.gov/data/nsd_cccc.txt
Converted to this format by: weather/nws_databse_creator.py

radar.csv - A lookup table of US weather radar sites, organized by
latitude/longitude.
Source: http://www.ncdc.noaa.gov/oa/radar/nexrad.kmz
Converted to this format by: weather/nws_databse_creator.py

zones.csv - A lookup table of US forecast/alert zones, organized by the
latitude/longitude of the zone centroid.
Source: http://www.nws.noaa.gov/geodata/catalog/wsom/html/cntyzone.htm
Converted to this format by: weather/nws_databse_creator.py

For an example application that uses these tables, see
weather/closest_weather_location.py

Please report data errors directly to the source proponent at NOAA.
Please report conversion & formatting errors to the weather/
nws_databse_creator.py proponent.

INSTALLATION

Download the CSV files, and start using them. Encoding is UTF-8.

ADDING NEW COUNTRIES

See the README in weather/nws_databse_creator.py

CAN I MIRROR THE DATA?

Sure. Public domain; all based on non-copyrightable US GOVT data.
The weather/nws_databse_creator.py script updates the database once each
week.
