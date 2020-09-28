## 1.2.1 (TBD)

* extend TMS beyond TMS Document max zoom level (28)

## 1.2.0 (2020-06-01)

* add TileMatrixSet minzoom/maxzoom properties
* fix TileMatrixSet.tile calculation
* add TileMatrixSet.tiles function (replicat from mercantile)
* add buffer and projected options to TileMatrixSet.feature method
* removes mercantile as dependencies
* add CLI
* renamed `morecantile.TileMatrixSet.point_towgs84` to `morecantile.TileMatrixSet.lnglat` (matches mercantile)
* renamed `morecantile.TileMatrixSet.point_fromwgs84` to `morecantile.TileMatrixSet.xy` (matches mercantile)
* add `truncate` option in `morecantile.TileMatrixSet.tile` (matches mercantile)
* re-order buffer and precision options in `morecantile.TileMatrixSet.feature` (matches mercantile)
* uses mercantile's tests

## 1.1.1 (2020-05-15)

* Fix bad default TMS files (#13)
* Add regex in model for identifier validation

## 1.1.0 (2020-05-13)

* better submodule definition
* add `morecantile.tms` object to access and register defaults TileMatrixSet
* Add depreciation warning for `morecantile.TileMatrixSet.load` method

## 1.0.0 (2020-05-11)

Major refactor of Morecantile, which is now based on OGC TileMatrixSet JSON documents.

* use pydantic model to validate TMS JSON documents (#6, author @geospatial-jeff)
* morecantile methods are part of the TMS model (#7)

## 0.1.0 (2020-02-03)

* Rename defaults grids (#1)

## 0.0.1 (2020-01-23)

* Initial release