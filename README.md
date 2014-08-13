# dojo-theme-flat

This theme framework is customized for Dojo dijits, dgrid, as well as some of the ArcGIS API for JS widgets using [Stylus](http://learnboost.github.io/stylus/).

## Sections

* [Features](#features)
* [Requirements](#requirements)
* [Instructions](#instructions)
* [Resources](#resources)
* [Issues](#issues)
* [Contributing](#contributing)
* [Licensing](#licensing)

## Features

This theme includes styles for the following components:

#### Dojo Dijits:

  * All "dijit/form" dijits
  * All "dijit/layout" dijits
  * All other Dojo dijits (Dialog, Menu, Calendar, Toolbar, etc.)
  * RTL supported
  
#### Dgrid:

  * Basic dgrid styles (dgrid.css)
  * One skin is included
  * All extensions
  * RTL supported
  
#### ArcGIS API for JavaScript Widgets:

Only these widgets are supported:

  * Fixed pan buttons
  * Zoom Slider
  * Basemap Gallery
  * Bookmarks
  * Geocoder
  * Legend
  * Measurement
  * Overview Map
  * Popup
  * Scalebar
  
## Requirements
* Using CSS files only:
* No requirements
* Using Stylus files:
  * [Nodejs](http://nodejs.org/)
  * [Stylus](https://www.npmjs.org/package/stylus) - CSS preprocessor used to compile .styl files 
  * [Nib](http://visionmedia.github.io/nib/) - a Stylus plugin that provides cross-browser CSS3 mixins . 
 
## How to use
  * CSS only:
    1. Download the "CSS" folder locally
    2. For Dojo dijits: Include dojo/flat.css
    3. For dgrid: Include dgrid/css/dgrid.css, dgrid/skins/skin.css, and other stylesheets for extensions in the "dgrid/css/extensions" folder if needed  
  
  * Using Stylus files
    1. TODO
    
## About This theme
  * Most icons are replaced with FontAwesome icon fonts. (http://fortawesome.github.io/Font-Awesome/get-started/)
  * Esri's branding colors are used as default.

## Browser Support
  Only tested with Chrome (v36), FireFox (v31), IE 11 and IE 8, 9 with IE 11's emulation tool.
  
