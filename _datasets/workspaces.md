---
schema: default
title: workspaces
organization: Regeneration
notes: locations of gla listed workspaces in WGS84 projection
resources:
  - name: workspaces list
    url: >-
      https://maps.london.gov.uk/gla/rest/services/apps/Workspaces_service_editable_verified_service_01/MapServer/0/query?where=verified+%3D+1+AND+x+IS+NOT+NULL&geometryType=esriGeometryEnvelope&spatialRel=esriSpatialRelIntersects&returnGeometry=true&geometryPrecision=2&outSR=EPSG%3A4326&f=geojson
    format: geojson
license: 'https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/'
maintainer: ''
maintainer_email: ''
---