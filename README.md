# module-embarq_map
Drupal module and assets used in several Ross Center Cities sites. 

# Implementation
In addition to adding the embarq_map module to the usual module location, do this:

1. Put the 'map' dir with the map image assets in the theme directory at /images
2. Adjust the map-pin css in the theme screen.css as follows (leave other values unchanged) at approx lines 3979-4009:

```
}
.static-map-container .map-pin--usa {
  left: 30.3%;
}
.static-map-container .map-pin--china {
  right: 32.6%;
}
.static-map-container .map-pin--turkiye {
  left: 55%;
}
.static-map-container .map-pin--india {
  right: 42%;
}
.static-map-container .map-pin--brasil {
  left: 36.4%;
}
.static-map-container .map-pin--mexico {
  left: 17%;
}
```
