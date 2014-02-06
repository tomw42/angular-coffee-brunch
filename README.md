### angular-coffee-brunch
## A starter project for AngularJS using
* [Brunch](http://brunch.io)
* Coffeescript
* [Stylus](http://learnboost.github.io/stylus/)
* [Jade](http://jade-lang.com/)


This boilerplate is based on [angular-brunch-seed](https://github.com/scotch/angular-brunch-seed) incorporating some modifications, updates and changes.

Features:
* Coffeescript / Jade / Stylus automatically compiled on save
* auto-reload during development saves you from manually refreshing the page
* Javascript / CSS minification for production
* [karma](https://github.com/karma-runner/karma) integration for
  unit tests
* Integration of [Bootstrap 3.1.0](https://github.com/twbs/bootstrap/)
* Integration of [angular-bootstrap](http://angular-ui.github.io/bootstrap/)
* Integration of [font-awesome icons](http://fontawesome.io/)
* Source map support

## How to use angular-coffee-brunch

Most likely you have **Brunch** installed. In this case the approach is pretty straight forward:

1. `brunch new https://github.com/tomw42/angular-coffee-brunch  myapp`
2. `npm install`
3. `bower install`

After building the sources the first time it may happen that brunch throws a an error concerning the bower support of Font-Awesome which is currently lacking a bower.json file. To fix this, edit the .bower.json file in the font-awesome directory in brunch_components like this:

`
{
  "name": "font-awesome",
  "homepage": "https://github.com/FortAwesome/Font-Awesome",
  "version": "4.0.3",
  "main": "css/font-awesome.css",
  "_release": "4.0.3",
  "_resolution": {
    "type": "version",
    "tag": "v4.0.3",
    "commit": "dc23a94e16a8daa3cbb3c7fa34d63e2812637b8f"
  },
  "_source": "git://github.com/FortAwesome/Font-Awesome.git",
  "_target": "4.0.3",
  "_originalSource": "font-awesome"
}
`

