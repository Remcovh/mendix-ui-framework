Mendix UI Framework
========================

This is the SCSS framework that is the basis for the Mendix UI Framework, introduced with the [Mendix DX Release](https://www.mendix.com/blog/drive-digital-innovation-with-the-mendix-dx-release/).

You can explore all the features and see them in actions via the [Mendix UI Framework Showcase App](https://ux.mendix.com/)

## Features

 * Uses Bootstrap framework
 * Uses SCSS partials to help structure the CSS
 * Uses Compass to take advantage of CSS3 mixins (no prefixes needed)
 * Styled Page Templates that are available in mendix version 5.18

## How To Use Custom CSS

Want to add or change styling? Use the files located in the custom directory.

## How To Use SCSS

Want to use SCSS and use all the variables and mixins? Remove the stylesheet url lib.css in the index.html to prevent double loading the css in your application. The libary will be included in the custom.scss file which you can extend to create your scss framework.

Mendix Framework uses SASS and Compass, which rely on Ruby. However you can install [Scout](http://mhs.github.io/scout-app/) to run Sass and Compass in a self-contained Ruby environment, letting you effortlessly manage all of your Sass projects with a handful of clicks. 

View the full documentation [Here](https://ux.mendix.com/index.html?profile=desktop#!/MyFirstModule/How_to_customize)

#### Setup Scout

Add your Mendix project in Scout and select the styles folder as the input and output folder for the stylesheet directory. Press play!

#### Edit the SCSS files

When you make changes to any of the scss files, your lib.css file will be automatically updated. You don't edit lib.css directly, compass takes care of that for you.

## Further Documentation

 * [Bootstrap](http://getbootstrap.com)
 * [Compass Framework](http://compass-style.org/)
 * [SASS](http://sass-lang.com/)
 * [Scout](http://mhs.github.io/scout-app/)
