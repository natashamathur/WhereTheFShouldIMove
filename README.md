# MapBuilder

The code in this repo pulls together information from [Chicago](https://data.cityofchicago.org/) and [NYC](https://opendata.cityofnewyork.us/) Open Data Portals as well as the [Yelp API](https://www.yelp.com/developers/documentation/v3). For each neighborhood in Chicago and NYC, a separate API call to Yelp is made based on longitude and latitude. The Yelp search returns up to 48 businesses (categories include restaurants, other food-related businesses, transportation, and health) per neighorhood. The Yelp business data is then merged with reformatted library and school data from the Chicago and NYC Open Data Portal as well as the [SNAP/EBT](https://www.fns.usda.gov/snap/supplemental-nutrition-assistance-program) dataset which comes from the U.S. Department of Agriculture website. 

Hosted on [JKAN](https://sun-kev.github.io/jkan/) using [Mapbox](https://www.mapbox.com/).

- [`Chicago Map`](https://sun-kev.github.io/jkan/map_of_chicago/) [`Code`](https://github.com/Sun-Kev/jkan/tree/gh-pages/map_of_chicago)
- [`NYC Map`](https://sun-kev.github.io/jkan/map_of_nyc/) [`Code`](https://github.com/Sun-Kev/jkan/tree/gh-pages/map_of_nyc)
- [`JKAN Code`](https://github.com/Sun-Kev/jkan)

Built by [Kevin Sun](https://github.com/Sun-Kev) and [Natasha Mathur](https://github.com/natashamathur)

If there are any issues opening a notebook, please enter the link into the renderer at the following site: https://nbviewer.jupyter.org/
