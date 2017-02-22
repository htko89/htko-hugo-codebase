---
type: project
draft: false
date: '2017-01-15'
title: HTKO.ca Site Base V1
topics:
  - code
  - gfx
tools:
  - hugo
  - node
  - gulp
  - sass
  - foundation
link: 'http://www.htko.ca'
code: 'https://github.com/htkoca/htko-site-base/tree/1.0.0'
photos:
  - mockup-surface.jpg
  - screenshot-ipadpro-landscape.jpg
  - screenshot-ipadpro.jpg
path: code/htko/site-base-legacy
---
# Personal Project
Hugo base for personal portfolio at htko.ca. An experiment in static site generation, using [Hugo](http://gohugo.io/) as the engine and [Foundation](http://foundation.zurb.com/) as the grid framework. Dynamic sites are heavy in resource usage are vulnerable to attacks. Static sites are fast, efficient and most of all, provide minimal avenues of attack. However, they are difficult to maintain, and do not scale well with large sets of data.

## Project Criteria:
* `gulp` task engine
* `gulp-sass`,`gulp-cssnano`,`gulp-autoprefixer` to compile scss files to css.
* `babel`,`gulp-concat`,`gulp-uglify` to compile js files.
* `gulp-sourcemaps` for sourcemapping.
* `globby`,`minimatch`,`fs-extra` for portfolio projects compilation.
* `js-beautify` for linting.
* `hugo` (`livereload`) or `browser-sync` for debug rendering.