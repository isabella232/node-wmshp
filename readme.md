# node-wmshp

[![Build Status](https://travis-ci.com/mapbox/node-wmshp.svg?branch=master)](https://travis-ci.com/mapbox/node-wmshp)

Reproject shapefiles into EPSG:3857 using [node-gdal](https://github.com/naturalatlas/node-gdal).

## Usage

As a shell script:

```
wmshp <infile> <outfile>
```

In Node.js

```js
var wmshp = require('wmshp');
wmshp('/path/to/input.shp', '/path/to/output.shp');
```
