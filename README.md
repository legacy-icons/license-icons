
# license-icons

[![NPM version](https://img.shields.io/npm/v/license-icons.svg)](https://www.npmjs.org/package/license-icons)
[![Bower version](https://img.shields.io/bower/v/license-icons.svg)](http://bower.io/search/?q=license-icons)
[![Packagist version](https://img.shields.io/packagist/v/legacy-icons/license-icons.svg)](https://packagist.org/packages/legacy-icons/license-icons)
[![Nuget version](https://img.shields.io/nuget/v/license-icons.svg)](https://www.nuget.org/packages/license-icons/)

[![Dependency Status](https://img.shields.io/david/dev/legacy-icons/license-icons.svg)](https://david-dm.org/legacy-icons/license-icons)
[![Build Status](https://img.shields.io/travis/legacy-icons/license-icons.svg)](https://travis-ci.org/legacy-icons/license-icons)


## About

Icons and logos from various vendors of the coding community.

This project just provides icons from various licenses. All icons are made available through the following dimensions (in pixels):

* 16x16
* 32x32
* 48x48
* 64x64
* 96x96
* 128x128
* 256x256


## CSS spritesheets

You can insert the icons directly into your HTML with a common IMG tag:

```html
<img alt="Github logo" src="dist/32x32/mit.png" width="32" height="32">
```


In addition to the icons by themselves, this project also ships a CSS spritesheet for the icon-pack. This spritesheet allows to load the entire icon-pack in just 1 image, and thus reduce HTTP calls.

This is what it actually looks:

![Spritesheet](https://raw.githubusercontent.com/legacy-icons/license-icons/master/dist/sprite-32x32/license-icons.png)
![Spritesheet](https://raw.githubusercontent.com/legacy-icons/license-icons/master/dist/sprite-16x16/license-icons.png)


All the positioning of the icons inside this alone image is made through CSS, which allows you to just add block-type tags with the proper class and get the same result:

```html
<div class="license-icons mit"></div>
```

Just remember to add the CSS stylesheet to the HEAD of your HTML page!


## Install

### Get the package with NPM

> npm install license-icons


### Get the package with Bower

> bower install license-icons


### Get the package with Composer / Packagist

> composer require legacy-icons/license-icons


### Get the package with NuGet

> Install-Package license-icons


## Build the whole project or your custom project

We use [Gulp](http://gulpjs.com/) to build the project, so if you want to re-build or customize this project, you'll need Gulp.

After gulp is installed, and your CLI is pointed to your work directory, first install the dependencies:

**with NPM 2.x.x**

> npm install

**with NPM 3.x.x** (resolve dependencies for `node-spritesheet` before this module's ones)

> npm install grunt grunt-contrib-coffee grunt-contrib-clean

> npm install

then be sure that you have *[ImageMagick](http://www.imagemagick.org/script/binary-releases.php)* installed for building spritesheet.

then, you can run the `gulp build` task to build the project:

> gulp build


### What the build task does?

First, it takes PNG files from the `src` folder, and pastes them to the `dist` folder.

Then it creates a spritesheet from the PNG images located in the `src` folder, and thus creates the `sprite` folder in `dist`.

If, for example you just want `bsd` and `mit` icons in a spritesheet, you just have to fork this project, point your CLI to the working directory, 
empty the `src` directory, except `bsd` and `mit` icons in PNG format, and then run the `gulp build` task.

You'll get the proper spritesheet and copies of the icons directly in the `dist` folder.


## License

Each icon in this project belong to its original author, and for most of them, they are copyrighted. Some of these icons may not match their project's official icon/logo.

Actually, this icon set is quite opinionated, but is definitely open to improvements, or critics.

Please note that the project "license-icons" does not consider these icons as free-to-use by default: 
if you want to use these icons in your project, you may|shall|should|must check with the rightful owners that your use of the icon is OK.


The icons are borrowed from the following projects:

* [![Apache](https://raw.githubusercontent.com/legacy-icons/license-icons/master/dist/32x32/apache.png) Apache](https://www.apache.org/licenses/LICENSE-2.0)
* [![BSD](https://raw.githubusercontent.com/legacy-icons/license-icons/master/dist/32x32/bsd.png) BSD](http://opensource.org/licenses/BSD-3-Clause)
* [![Copyleft](https://raw.githubusercontent.com/legacy-icons/license-icons/master/dist/32x32/copyleft.png) Copyleft](https://www.gnu.org/copyleft/copyleft.en.html)
* [![GPL](https://raw.githubusercontent.com/legacy-icons/license-icons/master/dist/32x32/gpl.png) GPL](https://www.gnu.org/licenses/gpl-3.0.en.html)
* [![MIT](https://raw.githubusercontent.com/legacy-icons/license-icons/master/dist/32x32/mit.png) MIT](http://opensource.org/licenses/MIT)
* [![Mozilla MPL](https://raw.githubusercontent.com/legacy-icons/license-icons/master/dist/32x32/mozilla.png) Mozilla MPL](https://www.mozilla.org/MPL/)
* [![Open Source](https://raw.githubusercontent.com/legacy-icons/license-icons/master/dist/32x32/open-source.png) Open Source](http://opensource.org/licenses)
* [![Public domain](https://raw.githubusercontent.com/legacy-icons/license-icons/master/dist/32x32/public-domain.png) Public domain](http://en.wikipedia.org/wiki/Public_domain)
* [![WTFPL](https://raw.githubusercontent.com/legacy-icons/license-icons/master/dist/32x32/wtfpl.png) WTFPL](http://www.wtfpl.net/)


### About the rest (all this repository but the icons)

All the content of this repository (excepted the icon pack) 
is licensed under the [MIT license](http://opensource.org/licenses/MIT).

Though, it is just composed a few trivial json files and a Readme.
