---
schema: default
title: music-facilities
organization: ''
notes: locations of gla listed music facilities
resources:
  - name: music-facilities list
    url: >-
      https://maps.london.gov.uk/gla/rest/services/apps/music_facilities_service_verified/MapServer/0/query?where=verified+%3D+1+AND+X+IS+NOT+NULL+AND+Y+IS+NOT+NULL&geometryType=esriGeometryEnvelope&spatialRel=esriSpatialRelIntersects&returnGeometry=true&geometryPrecision=2&outSR=EPSG%3A4326&f=geojson
    format: geojson
  - name: music-facilities list
    url: >-
      https://maps.london.gov.uk/geoserver/gis/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=gis:culture_music&maxFeatures=5000&outputFormat=csv&srsName=EPSG:4326&CQL_FILTER=verified=1
    format: csv
license: 'https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/'
category:
  - Culture
maintainer: ''
maintainer_email: ''
---