# seed-tooltip [![npm version](https://badge.fury.io/js/seed-tooltip.svg)](https://badge.fury.io/js/seed-tooltip)

tooltip component pack for [Seed](https://github.com/helpscout/seed)!

## Install
```
npm install seed-tooltip --save
```


## Basic Usage

### SCSS
This seed pack needs to be imported into your sass pipeline. Below is an example using Gulp:


```javascript
var gulp = require('gulp');
var sass = require('gulp-sass');
var pack = require('seed-tooltip');

gulp.task('sass', function () {
  return gulp.src('./sass/**/*.scss')
    .pipe(sass({
      includePaths: pack
    }))
    .pipe(gulp.dest('./css'));
});
```

Once that is setup, simply `@import` *seed-tooltip* as needed in your `.scss` file:

```scss
// Packs
@import "pack/seed-tooltip/_index";
```

## Options

The following variables can be found in `_config.scss`

```scss
seed-tooltip config options
```
