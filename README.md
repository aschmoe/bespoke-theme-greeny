[![Build Status](https://secure.travis-ci.org/cedced19/bespoke-theme-greeny.png?branch=master)](https://travis-ci.org/cedced19/bespoke-theme-greeny)

# bespoke-theme-greeny

Greeny theme for [Bespoke.js](http://markdalgleish.com/projects/bespoke.js) &mdash; [View demo](http://cedced19.github.io/bespoke-theme-greeny/demo/dist)

> **Please note:** This theme is in beta and designed for use with a future release of Bespoke.js

## Download

Download the [production version][min] or the [development version][max].

[min]: https://raw.github.com/cedced19/bespoke-theme-greeny/master/dist/bespoke-theme-greeny.min.js
[max]: https://raw.github.com/cedced19/bespoke-theme-greeny/master/dist/bespoke-theme-greeny.js

## Usage

This theme is shipped in a [UMD format](https://github.com/umdjs/umd), meaning that it is available as a CommonJS/AMD module or browser global.

For example, when using CommonJS modules:

```js
var bespoke = require('bespoke'),
  greeny = require('bespoke-theme-greeny');

bespoke.from('#presentation', [
  greeny.theme(),
  greeny.scale()
]);
```

When using browser globals:

```js
bespoke.from('#presentation', [
  bespoke.themes.greeny.scale(),
  bespoke.themes.greeny.theme()
]);
```

## Credits

This theme was built with [generator-bespoketheme](https://github.com/markdalgleish/generator-bespoketheme).

## License

[MIT License](http://cedced19.github.io/license/)
