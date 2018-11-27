---
schema: default
title: workspaces
organization: Regeneration
notes: locations of gla listed workspaces
resources:
  - name: workspaces list
    url: >-
      https://maps.london.gov.uk/gla/rest/services/apps/Workspaces_service_editable_verified_service_01/MapServer/0/query?where=verified+%3D+1+AND+x+IS+NOT+NULL&geometryType=esriGeometryEnvelope&spatialRel=esriSpatialRelIntersects&returnGeometry=true&geometryPrecision=2&outSR=EPSG%3A4326&f=html
    format: geojson
  - name: workspaces list
    url: >-
      maps.london.gov.uk/geoserver/gis/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=gis:regen_open_workspaces_web&maxFeatures=5&outputFormat=csv&srsName=EPSG:4326&propertyName=workspace_provider,site_id,site_name,address,post_code,borough,site_type,company_status,year_established__site_,photo,website,site_telephone,facebook,twitter,contact_email,generic_email__space_enquiries_,gross_internal_area__sqft_,number_of_occupants,occupant_type,number_of_desks__studios__workb,provision_type,cost_month__exact_,cost_month_type,tenure_type,if_lease___sublease_how_many_ye,do_you_expect_to_be_able_to_ren,contacted,contact___complete_priority,known_contact,completed_,update_date,description,sectors_catered_for,services
    format: csv
license: 'https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/'
category:
  - Regeneration
maintainer: ''
maintainer_email: ''
---