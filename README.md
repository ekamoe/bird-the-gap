_Interactive web maps to **inspire** engagement with the natural world, **inform** scientific research, and **support** conservation action_

## Goals of the Outreach Platform

Bird the Gap is an outreach-oriented web mapping project to direct birdwatchers to locations currently underrepresented in crowdsourced data compiled by [eBird](https://ebird.org/about/) and the [Cornell Lab of Ornithology](https://www.birds.cornell.edu/home).

## Datasets

My sponsor, GIS Developer Tom Auer, and his team developed two statistical models to identify geographic gaps in data contributed from citizen scientists around the world in 2018.

The resulting two sets of raster data demonstrate (1) relative **data sufficiency** to model abundance by administrative regions. This layer and (2) the **probability** of receiving data from a given pixel (or habitat configuration).

## Map Prototypes

The scalable prototypes use Mapbox and its JavaScript library to visualize data from the week of July 6, 2018. Each prototype includes three map layers: one Mapbox base layer and two custom layers.

- Mapbox base layer

![Mapbox base layer image](images/Mapbox-base-layer.png)

- data sufficiency layer

![data sufficiency layer image](images/data-sufficiency-layer.png)

- probability layer

![probability layer image](images/probability-layer.png)

## Prototype Views

These maps are best viewed in a desktop browser.

### Zoom Switch

In this prototype, both custom layers. The data sufficiency layer is visible first. As the user zooms in, the map switches to reveal the probability.

This prototype requires only one map load, making it less expensive to scale.

Click [here](https://ekamoe.github.io/zoom-switch/) to view the zoom switch prototype.

### Radio Toggle

This prototype contains radio buttons that allow the user to toggle between three custom styles. When the map loads, the user will see the same map as the Zoom Switch prototype. The user can then toggle to view only one layer at a time: data sufficiency only or probability only.

Because this version pulls three separate map styles, this would be more expensive to scale.

Click [here](https://ekamoe.github.io/radio-toggle/) to view the radio toggle prototype.

### Full documentation coming soon.

![bird the gap logo](images/bird-the-gap-logo-170.png)
