# data
====

## This repository is probably what you are looking for.

The data repository contains weather database tables for you to import.

### metar.csv
A lookup table of worldwide METAR weather observation sites, organized by latitude/longitude.
- Easy download: https://raw.githubusercontent.com/ian-weisser/data/master/metar.csv
- Source: http://weather.noaa.gov/data/nsd_cccc.txt
- Converted to this format by: ian-weisser/weather/nws_databse_creator.py

### radar.csv
A lookup table of US weather radar sites, organized by latitude/longitude.
- Easy download: https://raw.githubusercontent.com/ian-weisser/data/master/radar.csv
- Source: http://www.ncdc.noaa.gov/oa/radar/nexrad.kmz
- Converted to this format by: ian-weisser/weather/nws_databse_creator.py


### zone.csv
A lookup table of US forecast/alert zones, organized by the latitude/longitude of the zone centroid.
- Easy download: https://raw.githubusercontent.com/ian-weisser/data/master/zone.csv
- Source: http://www.nws.noaa.gov/geodata/catalog/wsom/html/cntyzone.htm
- Converted to this format by: ian-weisser/weather/nws_databse_creator.py

## Install and Use

To install, download the CSV files (try the 'Easy download' links), and start using them. Encoding is UTF-8.

For an example application that uses these tables, see ian-weisser/weather/closest_weather_location.py

These tables are updated weekly.

Please report data errors directly to the source proponent at NOAA.
Please report conversion & formatting errors to the ian-weisser/weather/nws_databse_creator.py proponent.

If you want to help add a new country or a new lookup table, please see the README in ian-weisser/weather/nws_databse_creator.py
