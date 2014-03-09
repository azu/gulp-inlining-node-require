# gulp-inlining-node-require

[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url]  [![Coverage Status][coveralls-image]][coveralls-url] [![Dependency Status][depstat-image]][depstat-url]

> inlining-node-require plugin for [gulp](https://github.com/wearefractal/gulp)

## Usage

First, install `gulp-inlining-node-require` as a development dependency:

```shell
npm install --save-dev gulp-inlining-node-require
```

Then, add it to your `gulpfile.js`:

```javascript
var inlining = require("gulp-inlining-node-require");
gulp.src("./src/*.js")
	.pipe(inlining())
	.pipe(gulp.dest("./dist"));
```

## API

### inlining-node-require(options)

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)