# jordan-data-analysis-ds

This folder contains a Flask app that pulls data from the AWS database and serves it to the web front end through API calls.

### Data files

- route_data_new.json
  - Dataframe of routes
  - 86 rows
  - columns: route_id, route_name, type, lat, lon, stopId, tag, title, dir
- route_paths.json
  - Dataframe of latitude/longitude coordinates describing each bus route
  - 86 rows
  - columns: tag (rout id), path, name
- schedule_data.json
  - Dataframe of times each stop is scheduled to have a bus
  - 404 rows
  - columns: day, route_tag, times, direction
- schedule_data_new.json
  - updated version of schedule_data.json, same columns
  - 416 rows
- route_info.csv
  - Dataframe of individual stops
  - 6290 rows
  - columns: route_id, lat, lon, stopId, tag, title, dir
- stop_data.csv
  - Dataframe of individual stops, same as route_info.csv but missing the dir column
  - 6420 rows
  - columns: lat, lon, stopId, tag, title, route_id