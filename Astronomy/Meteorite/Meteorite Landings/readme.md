# Meteorite Landings

Data on over 45k meteorites that have struck Earth

## About Dataset

The Meteoritical Society collects data on meteorites that have fallen to Earth from outer space. This dataset includes the location, mass, composition, and fall year for over 45,000 meteorites that have struck our planet.

Notes on missing or incorrect data points:

- a few entries here contain date information that was incorrectly parsed into the NASA database. As a spot check: any date that is before 860 CE or after 2016 are incorrect; these should actually be BCE years. There may be other errors and we are looking for a way to identify them.
- a few entries have latitude and longitude of 0N/0E (off the western coast of Africa, where it would be quite difficult to recover meteorites). Many of these were actually discovered in Antarctica, but exact coordinates were not given. 0N/0E locations should probably be treated as NA.

This comprehensive data set from The Meteoritical Society contains information on all of the known meteorite landings. The Fusion Table is collected by Javier de la Torre and we've also provided an XLS file that consists of 34,513 meteorites and includes the following fields:

- place
- type_of_meteorite
- mass_g
- fell_found
- year
- database
- coordinate_1
- coordinates_2
- cartodb_id
- created_at
- updated_at
- year_date
- longitude
- latitude
- geojson

## What can we do with this data?

Here are a couple of thoughts on questions to ask and ways to look at this data:

- How does the geographical distribution of observed falls differ from that of found meteorites?

- this would be great overlaid on a cartogram or alongside a high-resolution population density map are there any geographical differences or differences over time in the class of meteorites that have fallen to Earth?

## Reference 

[Nasa Meteorite Landings](https://data.nasa.gov/Space-Science/Meteorite-Landings/gh4g-9sfh)  
[Kaggle Meteorite Landings](https://www.kaggle.com/datasets/nasa/meteorite-landings)
