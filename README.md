# StickyFooter.js

[![NPM](https://nodei.co/npm/sticky-footer.js.png?downloads=true&downloadRank=true&stars=true)](https://npmjs.org/package/sticky-footer.js)

[![CodeFactor](https://www.codefactor.io/repository/github/jahidulpabelislam/sticky-footer.js/badge?style=flat-square)](https://www.codefactor.io/repository/github/jahidulpabelislam/sticky-footer.js)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/fc77f05e8d0743729ef31d7da9e09ed6)](https://www.codacy.com/app/jahidulpabelislam/sticky-footer.js?utm_source=github.com&utm_medium=referral&utm_content=jahidulpabelislam/sticky-footer.js&utm_campaign=Badge_Grade)
![npm](https://img.shields.io/npm/v/sticky-footer.js.svg)
![npm](https://img.shields.io/npm/dm/sticky-footer.js.svg)
![jsDelivr hits (GitHub)](https://img.shields.io/jsdelivr/gh/hm/jahidulpabelislam/sticky-footer.js.svg)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/jahidulpabelislam/sticky-footer.js/master.svg?label=last%20release)![npm bundle size](https://img.shields.io/bundlephobia/min/sticky-footer.js.svg)
![NPM](https://img.shields.io/npm/l/sticky-footer.js.svg)

## What?

A small library to create a sticky footer effect using JavaScript & jQuery.

If the length of the normal/original height of the page is smaller than the height of the window, the library will then extent the 'main content' element to to fill the remaining space.

## Why?

I had decided to create this library as I has found my self creating and using this effect/code in all my projects, so thought it will be nice to have it in one place only.
This way maintenance all use of this effect can be done easily. While also helping the developer community, with this nice small helper library for the front-end.

## How?

Firstly you will need a copy of one of two `js` files either the minified or non-minified version (`sticky-footer.min.js` or `sticky-footer.js`).
You can install it various ways:

-   via NPM - `npm install sticky-footer.js` ([https://www.npmjs.com/package/sticky-footer.js](https://www.npmjs.com/package/sticky-footer.js))
-   using jsDelivr CDN - [https://www.jsdelivr.com/package/npm/sticky-footer.js](https://www.jsdelivr.com/package/npm/sticky-footer.js) (for example `https://cdn.jsdelivr.net/npm/sticky-footer.js@1.2.1/src/sticky-footer.min.js`)
-   download file directly

Next insert the script/file into the necessary pages (`sticky-footer.min.js` or `sticky-footer.js`).

Then in your JavaScript, construct the StickyFooter and pass the main element selector as its only parameter. The main content selector being the selector of the element that should grow if the content isn't long enough. (for example `var stickyFooter = new StickyFooter('.main-content');`).

You can store the returned value from `StickyFooter` to then later manually trigger a refresh on repositioning, by calling the `repositionFooter` function on that returned object.

## License

This project is licensed under the terms of the GNU General Public License v3.0 license.
