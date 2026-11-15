# Data licence

The code in this repo is MIT (see [LICENSE](LICENSE)). The data is split three ways, because it comes from different places.

## My datasets: CC BY 4.0

`data/A1_Procedures.csv`, `data/External_Airport_Runways.csv` and `data/README.md` are released under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/). Use them however you like, as long as you credit this repo (see [How to cite](README.md#how-to-cite)).

This covers the structure, cleaning, normalisation and derived fields. The underlying published values come from the SANS AIP, so the note on AIP material below still applies to them.

## OpenStreetMap-derived data: ODbL

The ground features (buildings, roads, aprons, taxiways, land use and place names) come from OpenStreetMap. Any file that contains that geometry stays under the [Open Database License](https://opendatacommons.org/licenses/odbl/), as OSM requires. That includes `sources/osm.json`, `map-1/OEJN-ground.gpkg`, the QGIS project data, and the ground layers in Map 1 and Map 2.

Rendered images such as the atlas PNGs are produced works: credit "© OpenStreetMap contributors".

## SANS AIP material

The files in `sources/` (AIP pages, tables and their renders) and the SANS logos are SANS material. They are kept here for verification and are not covered by the licences above. For anything operational, use the official AIP.

## Third-party code

three.js in `map-2/vendor/` is MIT, under its own [licence file](map-2/vendor/LICENSE.txt).
