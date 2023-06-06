# Precipitation-temporal-clustering-and-Italian-landslides
This repository contains results about the spatial and temporal distribution of temporal clustering of precipitation and analysis of landslides triggers based on movement types over Italy.

## Content and file descriptions

- `clustering.nc`: this is a netcdf file containing 1 when there is a temporal clustering of precipitation events higher than the 80th quantile of wet days in a 30 days window centered on the specific day. Time range: 01 Dec 1950 - 30 Nov 2020. Spatial domain: Italy. Resolution: 0.1°x0.1°. Coordinate system: latlon WGS84
- `slides.csv`: this is a text file containing information about slides occurred over the Italian territory, from 1950. Columns 1-4: location. Columns 5-7: date of occurrence. Column 8: movment type. Column 9-10: coordinates. columns 11-12: number of landslide events occurred in that date around the location and ID of the group. Columns 13-17: trigger (in order, precipitation event above the 90th quantile, temporal clustering of precipitation over 15, 30, or 90 days or none of the previous ones.



