# Online Trip Reports

This will generate online trip reports based on available GPX data and images with GPS tagging.
The maps are generated with [`R`](https://www.r-project.org/) and the [`leaflet`](https://rstudio.github.io/leaflet/) package.

## Processing Steps

*None of these steps are currently implemented.
These are here to guide my development.*

1. Edit configuration file to point to the location of GPX files and GPS-tagged image files.
2. Run `clean_gpx.R` to prepare GPX files for mapping in leaflet.
3. Run `gen_map.R` to generate a web page for the trip, using all of the GPX files and GPS-tagged images in the specified directory.


## Requirements

* [`R`](https://www.r-project.org/) (tested with version 3.5.3).
* ['leafelet'](https://rstudio.github.io/leaflet/) (tested with version 2.0.2)

