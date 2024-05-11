# Rousay Parish Place-Names
Search and explore the places recorded in Volume 16 of the Orkney Ordnance Survey Object Name Books.
The Name Books digitized at [Scotland'sPlaces](https://scotlandsplaces.gov.uk/) are a fantastic resource but searching them can be difficult. This map enables detailed searching and querying of a subset of that data. See the screenshots below for examples. <i>I've made no attempt to correct transcription errors in the scraped text.</i>

## Features
* Simple search
* Advanced searching and filtering
* Split view, map view, table view
* Feature info popup (click a point on the map or the 'i' icon in the Action column)
* 5 basemap layers:
  * [Ordnance Survey, Six-inch to the mile, 1st edition](https://maps.nls.uk/os/6inch/)
  * [Ordnance Survey, Six-inch to the mile, 2nd edition](https://maps.nls.uk/os/6inch-2nd-and-later/)
  * [Ordnance Survey, Geological Survey of Britain, One-inch to the Mile](https://maps.nls.uk/geological/one-inch/)
  * [OpenStreetMap](https://www.openstreetmap.org/)
  * [Esri Satellite](https://www.arcgis.com/home/item.html?id=c03a526d94704bfb839445e80de95495/)

## Sources
* The map is built on [Bryan McBride's](https://github.com/bmcbride) excellent [geojson-dashboard](https://github.com/fulcrumapp/geojson-dashboard).
* The Ordnance Survey Name Book transcriptions were scraped from [Scotland'sPlaces](https://scotlandsplaces.gov.uk/) using the [county_scraper script](https://github.com/dgplacenames/osnb).
* I used the geolocated 2nd ed. OS names from the [GB1900 Gazetteer](https://www.visionofbritain.org.uk/data/) as a first pass.

## Troubleshooting
* Clicking the magnifying glass icon in the Action column will zoom to a feature. The National Library of Scotland map layers don't permit this level of zoom. Zoom out to see the feature on the map.
* If a filter isn't showing any results, it might be because a) you're zoomed into a location with no results (click Feature Extent to zoom out) or b) because there is text entered in the Search box.

## Screenshots

### Feature Info popup

![Info](https://raw.githubusercontent.com/dgplacenames/rousay/main/screenshots/popup.png)

### Filter: 'Name' contains 'geo', Map View

![Filter: 'Name' contains 'geo', Map View](https://raw.githubusercontent.com/dgplacenames/rousay/main/screenshots/geo.png)

### Filter: 'Authorities for spelling' contains 'Robert Logie'

![Filter: 'Authorities for spelling' contains 'Robert Logie'](https://raw.githubusercontent.com/dgplacenames/rousay/main/screenshots/robert_logie.png)

### Filter: thatched houses in good repair on Rousay, Map View, satellite layer

![Filter: thatched houses in good repair on Rousay, Map View, satellite layer](https://raw.githubusercontent.com/dgplacenames/rousay/main/screenshots/filters.png)

## To do
* Change marker colour to high contrast for Satellite layer
