# fawn

A WordPress Starter Theme

### Summary

For use as a starting template for building custom themes. Uses SCSS and AutoPrefixr, HTML5 Boilerplate with Modernizr and Normalize.css, and Grunt for all processing tasks.

----

![fawn](screenshot.png?raw=true)

----

### Usage

The theme is setup to use [Grunt](http://gruntjs.com/) to compile SCSS (with source maps), run it through [AutoPrefixr](https://github.com/ai/autoprefixer), lint, concatenate and minify JavaScript (with source maps), optimize images, with flexibility to add any additional tasks via the Gruntfile.

Run `npm install` to pull in all Grunt dependencies. Run `grunt` to execute tasks.

- Compile `assets/styles/style.scss` to `style.css`
- Compile `assets/styles/editor-style.scss` to `editor-style.css`
- Compile `assets/styles/lte-ie9.scss` to `lte-ie9.css`
- Concatenate and minify plugins in `assets/js/vendor` and `assets/js/source/plugins.js` to `assets/js/plugins.min.js`
- Minify and lint `assets/js/source/main.js` to `assets/js/main.min.js`

To concatenate and minify your jQuery plugins, add them to the `assets/js/vendor` directory and add the `js` filename and path to the `Gruntfile` `uglify` task. Previous versions of the starter theme automatically pulled all plugins in the `vendor` directory, but this has changed to allow more granular control and for managing plugins and assets with bower.

### Bower

Supports [bower](https://github.com/bower/bower) to install and manage JavaScript dependencies in the `assets/js/vendor` folder.

### Features

1. Normalized stylesheet for cross-browser compatibility using Normalize.css version 3 (IE8+)
3. [Condensed Bootstrap Grid](https://github.com/whitetail/condensed-bootstrap-grid) - Full bootstrap grid experience packed into a 2kb Sass partial
5. SCSS partially setup with reset dependencies and base styles
6. Grunt for processing all SASS, JavaScript and images

### Credits

* [HTML5 Boilerplate](http://html5boilerplate.com)
* [Normalize.css](http://necolas.github.com/normalize.css)
* [Bootstrap](http://getbootstrap.com/)
* [SASS / SCSS](http://sass-lang.com/)
* [AutoPrefixr](https://github.com/ai/autoprefixer)
* [Underscores Theme](https://github.com/Automattic/_s)
* [Grunt](http://gruntjs.com/)
