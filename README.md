# SUMMARY
Description
“Inverse coverage” polygon dataset (absence of coverage/no coverage)-- Invert Mosaik marketed coverage data to show locations where no data connectivity is available

Mosaik geoprocessor should be able to handle country-by-country.

Geoprocessor is in high demand, so may need to spin up another one >= 2G

Need to union all patterns for all operators in a country, and then create inverse

use OSM for coastline+country clipping?

License PM: does that create issues with ODBL

Confirm there aren’t issues with disputed territories

Make sure we exclude patterns we can’t re-distribute (e.g. Sprint/TMUS by-band from Ting)

Universal level of simplification:

to explore/prototype by POC team

Additional holes in coverage are added/removed based on Availability tiles from Ookla Speedtest data

Use verified tiles?

ZL18

Update frequency and period

12 months updated quarterly?

Format (POC team to experiment with different output formats)

Shapefiles?

GeoDB?

GeoJSON?

Probably too bloated

global dataset (one file, so we don’t have to deal with disputed territories etc)
