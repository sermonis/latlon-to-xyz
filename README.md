# latlon-to-xyz

[![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)

Convert latitude,longitude to x,y,z position on a unit sphere.

## Usage

```javascript
var latLonToXyz = require('latlon-to-xyz')

var pos = latLonToXyz(51.507222, -0.1275)
// [ 0.3205275104690484, 0.9463475651510074, -0.04109015654964044 ]
```

## API

### `latLonToXyz(lat, lon, [out])`

Converts latitude,longitude to x,y,z position

- `lat`: Number, latitude
- `lon`: Number, longitude
- `out`: vec3

Returns out or new `vec3` point on a unit sphere

## License

MIT, see [LICENSE.md](http://github.com/vorg/latlon-to-xyz/blob/master/LICENSE.md) for details.
