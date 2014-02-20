*This repository is a mirror of the [component](http://component.io) module [microjs/simplify-2d](http://github.com/microjs/simplify-2d). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/microjs-simplify-2d`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
[![Build Status](https://secure.travis-ci.org/microjs/simplify-2D.png?branch=master)](https://travis-ci.org/microjs/simplify-2D)
# simplify-2D

  simplify-2D is a high-performance JavaScript 2D polyline simplification library

  If you need a 3D simplification library, check out [microjs/simplify-3D](https://github.com/microjs/simplify-3D).

## Installation

    $ component install microjs/simplify-2D
    
    $ npm install simplify-2d

## API

  ```javascript
  var simplify = require('simplify-2D');
  simplify(points, tolerance, highQuality)
  ```

  Returns a simplified array of points

  - `points` - An array of points in the format: `{x: Number, y: Number}`
  - `tolerance` - Optional number (defaulting to 1) Affects the amount of simplification (in the same metric as the point coordinates).
  - `highQuality` - Optional boolean (defaults to false) - Excludes distance-based preprocessing step which leads to higher quality but runs ~10-20 times slower.

## License

  MIT
