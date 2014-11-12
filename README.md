npm module heloworld
=========

A small library providing utility methods to `escape` and `unescape` HTML entities

## Installation

  npm install npm-module-heloworld --save

## Usage

  var scapegoat = require('npm-module-heloworld')
      escape = scapegoat.escape,
      unescape = scapegoat.unescape;

  var html = '<h1>Hello World</h1>',
      escaped = escape(html),
      unescaped = unescape(escaped);

  console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);

## Tests

  npm test

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.
Add unit tests for any new or changed functionality. Lint and test your code.

## Release History

* 0.1.0 Initial release

## References:

1. http://quickleft.com/blog/creating-and-publishing-a-node-js-module
