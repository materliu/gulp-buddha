# gulp-buddha [![Build Status](https://travis-ci.org/materliu/gulp-buddha.svg?branch=master)](https://travis-ci.org/materliu/gulp-buddha)

> My awesome gulp plugin


## Install

```sh
$ npm install --save-dev gulp-buddha
```


## Usage

```js
var gulp = require('gulp');
var buddha = require('gulp-buddha');

gulp.task('default', function () {
	return gulp.src('src/file.ext')
		.pipe(buddha())
		.pipe(gulp.dest('dist'));
});
```


## API

### buddha(options)

#### options

##### foo

Type: `boolean`  
Default: `false`

Lorem ipsum.

## Release History

2014-12-21&nbsp;&nbsp;&nbsp;v0.0.1&nbsp;&nbsp;&nbsp;not published

## License

MIT © [materliu](https://github.com/materliu)
