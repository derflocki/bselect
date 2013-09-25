# bselect 

The select decorator component that was missing for Twitter Bootstrap *3*.

### Features
* Dropdown decorator for `<select>` elements
* Easy to use, a simple jQuery call and you're done!
* Tested via [QUnit](http://qunitjs.com/)
* Support for internationalization
* ARIA ready
* __Lightweight__
 * `.js`: about 1 KB minified and gzipped, ~11 KB uncompressed
 * `.css`: about 1 KB minified and gzipped, ~6 KB uncompressed

## Installation
* Installation via Bower: `bower install bselect`
* Installation via NPM: `npm install bselect`
* Download zip/tarball - https://github.com/derflocki/bselect/archive/master.zip
* git clone this repo: `git clone git@github.com:derflocki/bselect.git`

## Demo
Access [http://derflocki.github.io/bselect/](http://derflocki.github.io/bselect/) to see demos.

## Usage

    javascript
    // Create the component
    $("select").bselect();

    // Create the component without an search input
    $("select").bselect({ searchInput : false });

    // Update the component - make the animation slower
    $("select").bselect("option", "animationDuration", 600);


## Bugs
If you've found any problems, [tell me!](https://github.com/derflocki/bselect/issues/new)

## License
MIT
