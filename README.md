# Creating Maps Online: A Guided Tour of Felt
Outline for my Central PA GIS Day (2023) presentation on Felt maps.  Event website is https://summits.harrisburgu.edu/gis/.  

## What is Felt?
- A web browser platform for creating maps
- https://felt.com/
- Free and paid plans (starting in 2024)
- Some features reviewed in this presentation (2023) will only be available on [paid plans in 2024](https://felt.com/pricing)

## Navigating the Website
- Recent maps, Draft maps, and Shared maps
- You can create a Team to collaborate on maps
- Create a new Map

## Navigating the Map Interface
- Zoom In/Out; Locate Me (current location); Scale bar
- Help and Resources: you can submit a bug or request a feature
- Change background (basemap)
- - Can toggle labels
  - Additional default options
  - Option for solid color
  - Can add a custom URL from various providers (please [read the docs](https://feltmaps.notion.site/Custom-Map-Backgrounds-30f85a712250421fa53a193cdf097b6a))
  - PennDOT: https://gis.penndot.gov/arcgis/rest/services/basemaps/penndotbasemap/MapServer/tile/{z}/{y}/{x}
  - Stamen Water Color (requires Stadia Maps account): https://tiles.stadiamaps.com/tiles/stamen_watercolor/{z}/{x}/{y}.jpg 
- View Menu
- Address Search
- Comments
- Felt (The Hidden Menu)
- - Download / Share / Embed
  - Draw various shapes on map
  - Duplicate or Delete map
  - Export to image file, pdf file, or geojson file
- Mark up the Map
- - Circle / Line / Polygon
  - Text / Note / Link
  - Pin / Route / Marker
  - Add Layers
  - Upload Anything (please [read the docs](https://feltmaps.notion.site/Upload-Anything-b26d739e80184127872faa923b55d232))

## Working with Layers
- Categories include General, Boundaries, Climate, Infrastructure, Nature & Exploration, and Science
- Can request a layer via a form
- Add layer via URL (Felt Menu > File > Upload from URL) ([read the docs](https://feltmaps.notion.site/Upload-Anything-b26d739e80184127872faa923b55d232#3e37f06bc38c4971b435fbff2f4da6cb)
- - As docs reference "Upload Anything," this may technically count as an "Upload Anything" item.
  - PA State Park Hiking Trails: https://www.gis.dcnr.state.pa.us/agsprod/rest/services/Parks/State_Parks/MapServer/4
  - PA State Health Centers: https://mapservices.pasda.psu.edu/server/rest/services/pasda/DepHealth/MapServer/13
  - USGS Hydrography: https://basemap.nationalmap.gov/arcgis/rest/services/USGSHydroCached/MapServer
- Upload Anything
