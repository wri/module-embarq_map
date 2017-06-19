# module-embarq_map
Drupal module and assets used in several Ross Center Cities sites. 

# Implementation
In addition to adding the embarq_map module to the usual module location, do this:

1. Put the 'map' dir with the map image assets in the theme directory at /images
2. Adjust the map-pin css in the theme screen.css as follows (left and right are the only changed values) at approx lines 3979-4009:

```
}
.static-map-container .map-pin--usa {
  bottom: 61%;
  left: 30.3%;
  margin-left: -56px;
}
.static-map-container .map-pin--china {
  bottom: 59.5%;
  right: 32.6%;
  margin-right: -165px;
}
.static-map-container .map-pin--turkiye {
  top: 38%;
  left: 55%;
  margin-left: -238px;
}
.static-map-container .map-pin--india {
  top: 51.6%;
  right: 42%;
  margin-right: -190px;
}
.static-map-container .map-pin--brasil {
  top: 73.2%;
  left: 36.4%;
  margin-left: 7px;
}
.static-map-container .map-pin--mexico {
  top: 47.3%;
  left: 17%;
  margin-left: -156px;
  width: 300px;
}
```
