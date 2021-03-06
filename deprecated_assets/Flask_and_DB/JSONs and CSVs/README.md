### Data files

- route_paths.json
  - Dataframe of laitude/longitude coordinates describing each bus route
  - 86 rows
  - columns: tag (rout id), path
  - same as jordan-sfmta-api/route_paths.json
- schedule_data.json
  - Dataframe of times each stop is scheduled to have a bus
  - 404 rows
  - columns: day, route_tag, times, direction
  - same as jordan-sfmta-api/schedule_data.json
- schedule_data_new.json
  - updated version of schedule_data.json, same columns
  - 416 rows
  - same as jordan-sfmta-api/schedule_data_new.json
- stop_data.csv
  - Dataframe of individual stops, same as route_info.csv but missing the dir column
  - 6420 rows
  - columns: lat, lon, stopId, tag, title, route_id
  - same as jordan-sfmta-api/stop_data.csv
- test_plot.json
  - JSON representation of a plotly map of one example route
  - similar to output of `create_graph()` in jordan-sfmta-api/app.py
