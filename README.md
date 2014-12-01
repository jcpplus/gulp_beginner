gulp_beginner
=============

a gulp file demo

##### plugins
- gulp-sass
- [gulp-autoprefixer](https://github.com/postcss/autoprefixer#browsers)
- gulp-sourcemaps

##### thanks 
- [Getting Gulp Plugins To Play Nice With SCSS and Sourcemaps](http://www.devworkflows.com/posts/getting-scss-auto-prefixer-and-source-map-to-play-nice/) 
- [Introduction to Gulp.js 4: Creating CSS with Sass (and Compass)](http://stefanimhoff.de/2014/gulp-tutorial-4-css-generation-sass/)


###### F#*k!ng Source Maps
```
Generating source maps, which actually work and point to the correct file is a real pain. There is a known bug in sass, which will mess up the paths. It took me literally hours to find out how to use gulp-ruby-sass and gulp-sourcemaps in combination to get working source maps. 
*by Stefan Imhoff*
```


---------------
The autoprefixer API:
#####autoprefixer(options)

#####options

###### browsers

Type: array
Default: ['> 1%', 'last 2 versions', 'Firefox ESR', 'Opera 12.1']

[Browsers](https://github.com/postcss/autoprefixer#browsers) you want to target.

###### cascade

Type: boolean
Default: true

Changes the CSS indentation to create a nice [visual cascade](https://github.com/postcss/autoprefixer#visual-cascade) of prefixes.

###### remove

Type: boolean
Default: true

Remove unneeded prefixes.
