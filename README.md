# Northeastern News WordPress Theme

2016 Re-design

## Dependencies

- [npm](https://www.npmjs.com/)
- [Bower](https://bower.io/)
- [Composer](https://getcomposer.org/)

## Setup

- Navigate to your theme directory
- To install WordPress dependencies run `composer install`.
- To install front-end dependencies run `npm install` and `bower install`.
- To compile and bundle front-end assests run `gulp dev`.

An npm package called [browsersync](https://www.browsersync.io/docs/gulp) is used within the `gulp dev` task to watch files and reload the page when a file is changed. A local development url will have to be provided as a proxy in order for browsersync to work. The proxy can be changed on line 120 of `gulpfile.js`.

The following front end assets built into the repository can be found in `static/js/vendor`:

- [jquery.smoothState.js](https://github.com/miguel-perez/smoothState.js)
- [quickshare.js](https://github.com/Upstatement/quickshare)

For more information on dependencies, plugins, and directory structure see the home section of this repositories [wiki](https://github.com/Upstatement/neu-news-wp-theme/wiki/Northeastern-News-Wiki).
