# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Upcoming changes][unreleased]

## [1.0.3]

### Added

* `L.esri.Vector.layer` object added so that developers can point at any arbitrary ArcGIS Online hosted vector tile source

### Fixed

* trapped situation in which vector style json defines path of sprites/glyphs using fully qualified paths.

### Changed

* made dependency on Leaflet fixed at `1.0.0-beta.2` (until [#47](https://github.com/mapbox/mapbox-gl-leaflet/issues/47) is resolved)
* started linting all the `.js` in the repo

## [1.0.2]

### Fixed

* Added three new Vector basemaps.  [Mid-Century](http://www.arcgis.com/home/item.html?id=763884983d3544c0a418a97992881fce), [Newspaper](http://www.arcgis.com/home/item.html?id=4f4843d99c34436f82920932317893ae) and [Spring](http://www.arcgis.com/home/item.html?id=267f44f08a844c7abee2b62b00600540).

## [1.0.1]

### Fixed

* added .npmignore file to ensure built library is included in npm package.

## 1.0.0

### Added

* Initial Release

[unreleased]: https://github.com/esri/esri-leaflet-vector/compare/v1.0.3...HEAD
[1.0.3]: https://github.com/esri/esri-leaflet-vector/compare/v1.0.2...v1.0.3
[1.0.2]: https://github.com/esri/esri-leaflet-vector/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/esri/esri-leaflet-vector/compare/v1.0.0...v1.0.1