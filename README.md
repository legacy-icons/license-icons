license-icons
============


[![NPM version](https://img.shields.io/npm/v/license-icons.svg)](https://www.npmjs.org/package/license-icons)
[![Bower version](https://img.shields.io/bower/v/license-icons.svg)](http://bower.io/search/?q=license-icons)
[![Packagist version](https://img.shields.io/packagist/v/t1st3/license-icons.svg)](https://packagist.org/packages/t1st3/license-icons)


[![Dependency Status](https://img.shields.io/david/dev/T1st3/license-icons.svg)](https://david-dm.org/t1st3/license-icons)
[![Build Status](https://img.shields.io/travis/T1st3/license-icons.svg)](https://travis-ci.org/T1st3/license-icons)



About
--------

Icons and logos from various vendors of the coding community.


This project just provides icons from various licenses. All icons are made available through the following dimensions (in pixels):

* 16x16
* 32x32
* 48x48
* 64x64
* 96x96
* 128x128
* 256x256


CSS spritesheets
----------

You can insert the icons directly into your HTML with a common IMG tag:

```
    <img alt="Github logo" src="dist/32x32/mit.png" width="32" height="32">
```


In addition to the icons by themselves, this project also ships a CSS spritesheet for the icon-pack. This spritesheet allows to load the entire icon-pack in just 1 image, and thus reduce HTTP calls.

This is what it actually looks:

![Spritesheet](https://raw.githubusercontent.com/T1st3/license-icons/master/dist/sprite-32x32/license-icons.png)
![Spritesheet](https://raw.githubusercontent.com/T1st3/license-icons/master/dist/sprite-16x16/license-icons.png)


All the positioning of the icons inside this alone image is made through CSS, which allows you to just add block-type tags with the proper class and get the same result:

```
    <div class="license-icons mit"></div>
```

Just remember to add the CSS stylesheet to the HEAD of your HTML page!


The icons are borrowed from the following projects:

* [![BSD](https://raw.githubusercontent.com/T1st3/license-icons/master/dist/32x32/bsd.png) BSD](http://opensource.org/licenses/BSD-3-Clause)
* [![Copyleft](https://raw.githubusercontent.com/T1st3/license-icons/master/dist/32x32/copyleft.png) Copyleft](https://www.gnu.org/copyleft/copyleft.en.html)
* [![GPL](https://raw.githubusercontent.com/T1st3/license-icons/master/dist/32x32/gpl.png) GPL](https://www.gnu.org/licenses/gpl-3.0.en.html)
* [![MIT](https://raw.githubusercontent.com/T1st3/license-icons/master/dist/32x32/mit.png) MIT](http://opensource.org/licenses/MIT)
* [![Open Source](https://raw.githubusercontent.com/T1st3/license-icons/master/dist/32x32/open-source.png) Open Source](http://opensource.org/licenses)
* [![WTFPL](https://raw.githubusercontent.com/T1st3/license-icons/master/dist/32x32/wtfpl.png) WTFPL](http://www.wtfpl.net/)



License
---------

Each icon in this project belong to its original author, and for most of them, they are copyrighted. Some of these icons may not match their project's official icon/logo.

Actually, this icon set is quite opinionated, but is definitely open to improvements, or critics.

Please note that the project "license-icons" does not consider these icons as free-to-use by default: 
if you want to use these icons in your project, you may|shall|should|must check with the rightful owners that your use of the icon is OK.




About the rest (all this repository but the icons)
----------

All the content of this repository (excepted the icon pack) 
is licensed under the [MIT license](http://opensource.org/licenses/MIT).

Though, it is just composed a few trivial json files and a Readme.





