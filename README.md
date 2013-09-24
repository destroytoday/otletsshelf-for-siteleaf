# Otlet's Shelf theme for Siteleaf

[![](http://dstry.it/RaXB/Screen%20Shot%202013-09-24%20at%206.05.04%20PM.png)](http://otletsshelf.siteleaf.net)

[Otlet's Shelf](http://otletsshelf.tumblr.com) originated as a Tumblr theme and an Amazon bookmarklet, designed and developed by [Andrew LeClair](http://www.andrewleclair.com/) & [Rob Giampietro](http://www.linedandunlined.com/). This is its [Siteleaf](http://siteleaf.com) port.

[View demo](http://otletsshelf.siteleaf.net)

## About Otlet's Shelf

> Named for [Paul Otlet](http://en.wikipedia.org/wiki/Paul_Otlet) — a librarian and visionary who popularized the 3x5 index card catalog and whose work in the early 1900’s prefigured the Internet — Otlet’s Shelf is a project in the spirit of free information exchange.

> Share a summer reading list. Keep track of the books on your physical shelves. Organize references around a subject of interest. Publish a wishlist. However you use it, Otlet’s Shelf is a simple tool which aims to turn the private act of collection into something shared.

## Improvements over original

- HTML5
- retina images
- removed ID selectors in CSS
- replaced fonts and colors with SASS variables
- replaced pixels with ems
- extracted reusable code into SASS mixins
- replaced circular avatar image with CSS-based circle cropping
- view books by author
- bold headers on book sidebar
- smaller type on book sidebar
- shelf in single book view

## Dev Instructions

1. Download or fork this repo.
2. Open Terminal in the directory.
3. Run `gem install bundler`, if Bundler isn't installed.
4. Run `bundle install` to install the required Ruby gems.
5. Run `bundle exec siteleaf config YOUR_DOMAIN` to configure your site to this directory.
6. Run `bundle exec guard` to watch and compile SASS and Coffeescript changes.
7. Run `bundle exec siteleaf server` in a new tab to preview your theme locally.
8. Open `0.0.0.0:9292` in your browser of choice.

## Screenshots

[![](http://dstry.it/RaXB/Screen%20Shot%202013-09-24%20at%206.05.04%20PM.png)](http://otletsshelf.siteleaf.net)
[![](http://dstry.it/RaXY/Screen%20Shot%202013-09-24%20at%206.09.08%20PM.png)](http://otletsshelf.siteleaf.net)
[![](http://dstry.it/RaYD/Screen%20Shot%202013-09-24%20at%206.11.20%20PM.png)](http://otletsshelf.siteleaf.net)
[![](http://dstry.it/RbMk/Screen%20Shot%202013-09-24%20at%206.12.49%20PM.png)](http://otletsshelf.siteleaf.net)
