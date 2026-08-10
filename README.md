# Surf City Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Surf City municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01409146, Ship Bottom
- PETSS / NOAA station: 8533935
- NAVD88 thresholds: 2.06 ft minor, 3.06 ft moderate, 4.06 ft major
- MLLW thresholds: 3 ft minor, 4 ft moderate, 5 ft major
- MLLW = NAVD88 + 0.94 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Surf City Borough boundary at 5-foot resolution.
