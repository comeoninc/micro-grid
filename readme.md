# [Base Micro Grid](http://getbase.org)

Base Micro Grid is designed in a way where you can add it on top of the Base CSS framework or to your own custom project.

[![Travis Build Status][travis-img]][travis] [![David Dependencies Status][david-img]][david]

[travis-img]:   https://img.shields.io/travis/getbase/micro-grid.svg?branch=master
[david-img]:    https://img.shields.io/david/dev/getbase/micro-grid.svg?branch=master&label=dependencies
[travis]:       https://travis-ci.org/getbase/micro-grid
[david]:        https://david-dm.org/getbase/micro-grid?type=dev

* * *

## Table of contents

* [Overview](#overview)
* [Installation](#installation)
* [Documentation](#documentation)
* [Demo](#demo)
* [Support](#support)
* [Authors](#authors)
* [License](#license)

* * *

## Overview

Base Micro Grid contains styles for flex grids with rows and basic columns for all breakpoints.

* * *

## Installation

If you have an existing project and would like to include the Base micro grid module, run the following command:

```bash
npm install --save @getbase/micro-grid
```

Once you have the micro grid module installed, you can include it in your CSS/LESS/SCSS file with one of the following ways:

#### CSS Import:
  ```css
  import url("https://cdn.rawgit.com/getbase/micro-grid/master/css/index.css");
  ```

#### SCSS Import:

  ```scss
  /* Import Base Micro Grid */
  @import "node_modules/@getbase/micro-grid/scss/index";
  /* Your Other Styles */
  @import "main"
  ```


#### LESS Import:

  ```css
  /* Import Base Micro Grid */
  @import "node_modules/@getbase/micro-grid/scss/index";
  /* Your Other Styles */
  @import "main"
  ```

* * *

## Documentation

Base Micro Grid includes styles for flex grids with rows and basic columns for all breakpoints.

#### Micro Grid (Applies to SCSS/LESS)

| Class | Purpose | Example | Outcome |
| ----- | ------- | ------- | ------- |
| `.row` | Apply a `.row` when wrapping columns | `<div class="row">This needs to be wrapped around columns.</div>` | Applies a `.row` to a `div` element which has a negative margin left and right of the gutter spacing for all breakpoints |
| `.col-1-2` | Apply a `.col-1-2` | `<div class="col-1-2">Column</div>` | Applies a `.col-1-2` to a `div` element which has a padding left and right of gutter spacing and a width of 50% for all breakpoints |
| `.col-1-3` | Apply a `.col-1-3` | `<div class="col-1-3">Column</div>` | Applies a `.col-1-3` to a `div` element which has a padding left and right of gutter spacing and a width of 33.33333% for all breakpoints |
| `.col-2-3` | Apply a `.col-2-3` | `<div class="col-2-3">Column</div>` | Applies a `.col-2-3` to a `div` element which has a padding left and right of gutter spacing and a width of 66.66667% for all breakpoints |
| `.col-1-4` | Apply a `.col-1-4` | `<div class="col-1-4">Column</div>` | Applies a `.col-1-4` to a `div` element which has a padding left and right of gutter spacing and a width of 25% for all breakpoints |
| `.col-3-4` | Apply a `.col-3-4` | `<div class="col-3-4">Column</div>` | Applies a `.col-3-4` to a `div` element which has a padding left and right of gutter spacing and a width of 75% for all breakpoints |
| `.col-1-5` | Apply a `.col-1-5` | `<div class="col-1-5">Column</div>` | Applies a `.col-1-5` to a `div` element which has a padding left and right of gutter spacing and a width of 20% for all breakpoints |
| `.col-2-5` | Apply a `.col-2-5` | `<div class="col-2-5">Column</div>` | Applies a `.col-2-5` to a `div` element which has a padding left and right of gutter spacing and a width of 40% for all breakpoints |
| `.col-3-5` | Apply a `.col-3-5` | `<div class="col-3-5">Column</div>` | Applies a `.col-3-5` to a `div` element which has a padding left and right of gutter spacing and a width of 60% for all breakpoints |
| `.col-4-5` | Apply a `.col-4-5` | `<div class="col-4-5">Column</div>` | Applies a `.col-4-5` to a `div` element which has a padding left and right of gutter spacing and a width of 80% for all breakpoints |
| `.col-full` | Apply a `.col-full` | `<div class="col-full">Column</div>` | Applies a `.col-full` to a `div` element which has a padding left and right of gutter spacing and a width of 100% for all breakpoints |
| `.row-m` | Apply a `.row-m` when wrapping columns | `<div class="row-m">This needs to be wrapped around columns.</div>` | Applies a `.row-m` to a `div` element which has a negative margin left and right of the gutter spacing for medium devices and up |
| `.col-1-2-m` | Apply a `.col-1-2-m` | `<div class="col-1-2-m">Column</div>` | Applies a `.col-1-2-m` to a `div` element which has a padding left and right of gutter spacing and a width of 50% for medium devices and up |
| `.col-1-3-m` | Apply a `.col-1-3-m` | `<div class="col-1-3-m">Column</div>` | Applies a `.col-1-3-m` to a `div` element which has a padding left and right of gutter spacing and a width of 33.33333% for medium devices and up |
| `.col-2-3-m` | Apply a `.col-2-3-m` | `<div class="col-2-3-m">Column</div>` | Applies a `.col-2-3-m` to a `div` element which has a padding left and right of gutter spacing and a width of 66.66667% for medium devices and up |
| `.col-1-4-m` | Apply a `.col-1-4-m` | `<div class="col-1-4-m">Column</div>` | Applies a `.col-1-4-m` to a `div` element which has a padding left and right of gutter spacing and a width of 25% for medium devices and up |
| `.col-3-4-m` | Apply a `.col-3-4-m` | `<div class="col-3-4-m">Column</div>` | Applies a `.col-3-4-m` to a `div` element which has a padding left and right of gutter spacing and a width of 75% for medium devices and up |
| `.col-1-5-m` | Apply a `.col-1-5-m` | `<div class="col-1-5-m">Column</div>` | Applies a `.col-1-5-m` to a `div` element which has a padding left and right of gutter spacing and a width of 20% for medium devices and up |
| `.col-2-5-m` | Apply a `.col-2-5-m` | `<div class="col-2-5-m">Column</div>` | Applies a `.col-2-5-m` to a `div` element which has a padding left and right of gutter spacing and a width of 40% for medium devices and up |
| `.col-3-5-m` | Apply a `.col-3-5-m` | `<div class="col-3-5-m">Column</div>` | Applies a `.col-3-5-m` to a `div` element which has a padding left and right of gutter spacing and a width of 60% for medium devices and up |
| `.col-4-5-m` | Apply a `.col-4-5-m` | `<div class="col-4-5-m">Column</div>` | Applies a `.col-4-5-m` to a `div` element which has a padding left and right of gutter spacing and a width of 80% for medium devices and up |
| `.col-full-m` | Apply a `.col-full-m` | `<div class="col-full-m">Column</div>` | Applies a `.col-full-m` to a `div` element which has a padding left and right of gutter spacing and a width of 100% for medium devices and up |
| `.row-l` | Apply a `.row-l` when wrapping columns | `<div class="row-l">This needs to be wrapped around columns.</div>` | Applies a `.row-l` to a `div` element which has a negative margin left and right of the gutter spacing for large devices and up |
| `.col-1-2-l` | Apply a `.col-1-2-l` | `<div class="col-1-2-l">Column</div>` | Applies a `.col-1-2-l` to a `div` element which has a padding left and right of gutter spacing and a width of 50% for large devices and up |
| `.col-1-3-l` | Apply a `.col-1-3-l` | `<div class="col-1-3-l">Column</div>` | Applies a `.col-1-3-l` to a `div` element which has a padding left and right of gutter spacing and a width of 33.33333% for large devices and up |
| `.col-2-3-l` | Apply a `.col-2-3-l` | `<div class="col-2-3-l">Column</div>` | Applies a `.col-2-3-l` to a `div` element which has a padding left and right of gutter spacing and a width of 66.66667% for large devices and up |
| `.col-1-4-l` | Apply a `.col-1-4-l` | `<div class="col-1-4-l">Column</div>` | Applies a `.col-1-4-l` to a `div` element which has a padding left and right of gutter spacing and a width of 25% for large devices and up |
| `.col-3-4-l` | Apply a `.col-3-4-l` | `<div class="col-3-4-l">Column</div>` | Applies a `.col-3-4-l` to a `div` element which has a padding left and right of gutter spacing and a width of 75% for large devices and up |
| `.col-1-5-l` | Apply a `.col-1-5-l` | `<div class="col-1-5-l">Column</div>` | Applies a `.col-1-5-l` to a `div` element which has a padding left and right of gutter spacing and a width of 20% for large devices and up |
| `.col-2-5-l` | Apply a `.col-2-5-l` | `<div class="col-2-5-l">Column</div>` | Applies a `.col-2-5-l` to a `div` element which has a padding left and right of gutter spacing and a width of 40% for large devices and up |
| `.col-3-5-l` | Apply a `.col-3-5-l` | `<div class="col-3-5-l">Column</div>` | Applies a `.col-3-5-l` to a `div` element which has a padding left and right of gutter spacing and a width of 60% for large devices and up |
| `.col-4-5-l` | Apply a `.col-4-5-l` | `<div class="col-4-5-l">Column</div>` | Applies a `.col-4-5-l` to a `div` element which has a padding left and right of gutter spacing and a width of 80% for large devices and up |
| `.col-full-l` | Apply a `.col-full-l` | `<div class="col-full-l">Column</div>` | Applies a `.col-full-l` to a `div` element which has a padding left and right of gutter spacing and a width of 100% for large devices and up |
| `.row-xl` | Apply a `.row-xl` when wrapping columns | `<div class="row-xl">This needs to be wrapped around columns.</div>` | Applies a `.row-xl` to a `div` element which has a negative margin left and right of the gutter spacing for extra large devices and up |
| `.col-1-2-xl` | Apply a `.col-1-2-xl` | `<div class="col-1-2-xl">Column</div>` | Applies a `.col-1-2-xl` to a `div` element which has a padding left and right of gutter spacing and a width of 50% for extra large devices and up |
| `.col-1-3-xl` | Apply a `.col-1-3-xl` | `<div class="col-1-3-xl">Column</div>` | Applies a `.col-1-3-xl` to a `div` element which has a padding left and right of gutter spacing and a width of 33.33333% for extra large devices and up |
| `.col-2-3-xl` | Apply a `.col-2-3-xl` | `<div class="col-2-3-xl">Column</div>` | Applies a `.col-2-3-xl` to a `div` element which has a padding left and right of gutter spacing and a width of 66.66667% for extra large devices and up |
| `.col-1-4-xl` | Apply a `.col-1-4-xl` | `<div class="col-1-4-xl">Column</div>` | Applies a `.col-1-4-xl` to a `div` element which has a padding left and right of gutter spacing and a width of 25% for extra large devices and up |
| `.col-3-4-xl` | Apply a `.col-3-4-xl` | `<div class="col-3-4-xl">Column</div>` | Applies a `.col-3-4-xl` to a `div` element which has a padding left and right of gutter spacing and a width of 75% for extra large devices and up |
| `.col-1-5-xl` | Apply a `.col-1-5-xl` | `<div class="col-1-5-xl">Column</div>` | Applies a `.col-1-5-xl` to a `div` element which has a padding left and right of gutter spacing and a width of 20% for extra large devices and up |
| `.col-2-5-xl` | Apply a `.col-2-5-xl` | `<div class="col-2-5-xl">Column</div>` | Applies a `.col-2-5-xl` to a `div` element which has a padding left and right of gutter spacing and a width of 40% for extra large devices and up |
| `.col-3-5-xl` | Apply a `.col-3-5-xl` | `<div class="col-3-5-xl">Column</div>` | Applies a `.col-3-5-xl` to a `div` element which has a padding left and right of gutter spacing and a width of 60% for extra large devices and up |
| `.col-4-5-xl` | Apply a `.col-4-5-xl` | `<div class="col-4-5-xl">Column</div>` | Applies a `.col-4-5-xl` to a `div` element which has a padding left and right of gutter spacing and a width of 80% for extra large devices and up |
| `.col-full-xl` | Apply a `.col-full-xl` | `<div class="col-full-xl">Column</div>` | Applies a `.col-full-xl` to a `div` element which has a padding left and right of gutter spacing and a width of 100% for extra large devices and up |

### SCSS

#### Variables

| Variable | Purpose | Default | 
| -------- | ------- | ------- |
| `$grid-alignment` | Alignment of the grid layout | `left` |

#### Variables

| Variable | Purpose | Default | 
| -------- | ------- | ------- |
| `$grid-alignment` | Alignment of the grid layout | `left` |

### LESS

#### Variables

| Variable | Purpose | Default | 
| -------- | ------- | ------- |
| `@grid-alignment` | Alignment of the grid layout | `left` |

* * *

## Demo

[View page example](https://rawgit.com/getbase/micro-grid/master/index.html) with the micro grid and containers stylesheet applied.

* * *

## Support

* IE10+ and all other modern browsers.
* Please specify browsers you need to support in `package.json` according to [browserslist docs](https://github.com/ai/browserslist#queries).

* * *

## Authors

#### Matthew Hartman

* [https://twitter.com/matthewhartmans](https://twitter.com/matthewhartmans)
* [https://github.com/matthewhartman](https://github.com/matthewhartman)

* * *

## License

Code released under the [MIT Open Source](https://opensource.org/licenses/MIT) license.