# Production
## Overview
The tool converts feature stream to vector tiles packaged in [mbtiles](https://github.com/mapbox/mbtiles). We aim at daily update of vector tiles from the combination of OSM and organization-specific data. 

## Existing software used
- [tippecanoe](https://github.com/mapbox/tippecanoe): a tool to produce vector tiles from newline-delimited GeoJSON.

## Developed scripts
- [pnd](https://github.com/hfu/pnd): a tool to get features from PostGIS and calls tippecanoe to produce vector tiles. This tool integrates the concept of what3numbers modules to divide-and-counquer the large scale data. 

## Developed specifications
- [modify-spec](https://github.com/hfu/modify-spec): a specification for a script what takes a GeoJSON feature and outputs a GeoJSON feature.

## Developed concept
- what3numbers
