# OSM Historic Map

Based on ideas of `https://osm-catalan.github.io/osmcatmap/` and `https://github.com/Ripollx/osmcatmap2` .
Developed with [OpenLayers](https://openlayers.org/) library  and with API from [Overpass Turbo](https://wiki.openstreetmap.org/wiki/Overpass_turbo) available on [Overpass Turbo website](https://overpass-turbo.eu/).

## Features:

-Map based on [Bicycle tags map](https://wiki.openstreetmap.org/wiki/Bicycle_tags_map)

-With modifications of [Ramiro Balado](https://github.com/Qjammer)

-New Openlayers version done by [Ripollx](https://github.com/Ripollx)

-Possibility of show outside JSONs by [Hugoren Martinako](https://github.com/Crashillo)

-Complex queries possibility done by [Ismael Luceno](https://github.com/ismaell)

-Collapsable background layers done by  [Gerald Kogler](https://github.com/geraldo)

-Additional ideas by [yopaseopor](https://github.com/yopaseopor)

## Tags

OSM Historic Map shows you all the tags refered to past, present and future nodes using [lifecycle prefix tags](https://overpass-turbo.eu/). 

* was
* abandoned
* razed
* proposed
* construction
* old
* name:date
* demolished
* removed
* disused


## Using

You can modify the page editing these files:
* index.html contains the structure of the page.
* index.js contains the orchestrator to use OpenLayers (only modify if toy want to add new functionalities).
* config.js contains definition of languages and characteristics you want to show.
* layers.json contains definition of background layers you want to use.

## Demo

You can see it [here](https://yopaseopor.github.io/osmhistoricmap)
