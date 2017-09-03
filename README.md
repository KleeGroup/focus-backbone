[Focus](https://kleegroup.github.io/focus-docs)
=======
[![Build Status](https://travis-ci.org/KleeGroup/focus.svg)](https://travis-ci.org/KleeGroup/focus.svg)

**Currently in dev**

Fmk for spa application.

## What's inside
See our [wiki](https://github.com/KleeGroup/focus/wiki)
See our [documentation](https://kleegroup.github.io/focus-docs)


## How to build the lib
The build system is made with `gulp` which is a node base build system. `npm install -g gulp`
Then you have to launch the following command: `npm run build` which generates two outputs: one for the browser, one for node js (expecially for unit tests purpose).

### Browser
The browser build is inside the `dist/browser/fmk.js`

### Node js

Focus is publish under the name [focusjs](https://www.npmjs.com/package/focusjs) on npm.

## Unit tests
All unit tests are written with mocha, and can be launched using the `npm run test` command.
It uses **mocha**.

## How to use the fmk.js file

You have to configure the `build.json` file which is at the root directory in order to copy the fmk.js dile into your **vendor** directory insode your application.
Then in your project, [brunch](http://brunch.io) should use it automatically.
_Tip:_ Remember in order to launch brunch: `brunch w` in  the directory of your SPA project.
You can look at the [focus-starter-kit](https://github.com/KleeGroup/focus-starter-kit) project to have an example application using this fmk.

## Dependencies:

### Browser

- [jQuery](http://jquery.com)
- [Underscore.js](http://underscorejs.org/)
- [Backbone.js](http://backbonejs.org/)
- [Moment.js](http://momentjs.com/timezone/docs/)
- [Handlebars](http://handlebarsjs.com/)
- [Numeral](http://numeraljs.com/)


### Node
- [Underscore.js](http://underscorejs.org/)
- [Backbone.js](http://backbonejs.org/)
- [Mocha](http://mochajs.org/)
- Promises with [Bluebird](https://github.com/petkaantonov/bluebird)

## [Contributors](https://github.com/KleeGroup/focus/graphs/contributors)
