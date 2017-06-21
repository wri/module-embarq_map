# module-embarq_map
Drupal module and assets used in several Ross Center Cities sites. 

# Implementation

1. Copy the embarq_map module files to the usual module location (for the Cities sites it is usually /sites/all/modules/custom/)
2. Put the 'map' dir with the map image assets in the theme directory at /images
3. Adjust the map-pin css in the WRI theme (leave other values unchanged). The sass component is wri/sass/components/\_embarq-static-map.scss. Note: if sass is not running/updating then you should also update wri/css/screen.css at approx lines 3979-4009:

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
