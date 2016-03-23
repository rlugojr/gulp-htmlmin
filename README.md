# gulp-htmlmin [![NPM version](https://badge.fury.io/js/gulp-htmlmin.svg)](http://badge.fury.io/js/gulp-htmlmin)  [![Build Status](https://travis-ci.org/jonschlinkert/gulp-htmlmin.svg)](https://travis-ci.org/jonschlinkert/gulp-htmlmin) 

> gulp plugin to minify HTML.

*Issues with the HTML parser and output should be reported on the [html-minifier](https://github.com/kangax/html-minifier/issues) issue tracker.*

## Install with [npm](npmjs.org)

```sh
npm i gulp-htmlmin --save-dev
```

## Usage

```js
var gulp = require('gulp');
var htmlmin = require('gulp-htmlmin');

gulp.task('minify', function() {
  return gulp.src('src/*.html')
    .pipe(htmlmin({collapseWhitespace: true}))
    .pipe(gulp.dest('dist'))
});
```

See the [html-minifier docs](https://github.com/kangax/html-minifier) for options.

## Run tests

Install dev dependencies:

```sh
npm i && mocha
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/gulp-htmlmin/issues)

## Authors

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

**Shinnosuke Watanabe**

+ [github/shinnn](https://github.com/shinnn)
+ [twitter/shinnn_tw](http://twitter.com/shinnn_tw) 

## License

Copyright (c) 2014-2015 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb](https://github.com/assemble/verb) on January 10, 2015._
