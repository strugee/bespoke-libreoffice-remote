[![Build Status](https://secure.travis-ci.org/strugee/bespoke-libreoffice-remote.png?branch=master)](https://travis-ci.org/strugee/bespoke-libreoffice-remote) [![Coverage Status](https://coveralls.io/repos/strugee/bespoke-libreoffice-remote/badge.png)](https://coveralls.io/r/strugee/bespoke-libreoffice-remote)

# bespoke-libreoffice-remote

Impersonate LibreOffice Impress to talk to the Impress Remote app

## Download

Download the [production version][min] or the [development version][max], or use a [package manager](#package-managers).

[min]: https://raw.github.com/strugee/bespoke-libreoffice-remote/master/dist/bespoke-libreoffice-remote.min.js
[max]: https://raw.github.com/strugee/bespoke-libreoffice-remote/master/dist/bespoke-libreoffice-remote.js

## Usage

This plugin is shipped in a [UMD format](https://github.com/umdjs/umd), meaning that it is available as a CommonJS/AMD module or browser global.

For example, when using CommonJS modules:

```js
var bespoke = require('bespoke'),
	libreofficeRemote = require('bespoke-libreofficeRemote');

bespoke.from('#presentation', [
	libreofficeRemote()
]);
```

When using browser globals:

```js
bespoke.from('#presentation', [
	bespoke.plugins.libreofficeRemote()
]);
```

## Package managers

### npm

```bash
$ npm install bespoke-libreoffice-remote
```

### Bower

```bash
$ bower install bespoke-libreoffice-remote
```

## Credits

This plugin was built with [generator-bespokeplugin](https://github.com/markdalgleish/generator-bespokeplugin).

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
