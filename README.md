# jQuery Spellchecker

The jQuery Spellchecker is a free Javascript spellchecker in the form of a
lightweight jQuery plugin that can be used to check the spelling of text
within a form field or within a DOM tree.

Note: This is a friendly fork of jquery-spellchecker, because the original was
marked unmaintained.  The PHP webservice has been removed from the source tree,
with a view to making the JS code more reusable (see 'Requirements' below.

## Features

* Unicode support (works with most languages)
* HTML parsing (for using the spellchecker within WSYIWYG editors)
* Text parsing (for using the spellchecker on form fields)
* Multiple fields
* Friendly API
* Event based
* MIT licensed

## Browser support

The plugin has been tested and works with the following browsers:

* IE6+ and latest Chrome, Firefox, Safari and Opera

## Requirements

* jQuery
* findAndReplaceDOMText
* A webservice that implements the API required by this code - see
  e.g. [CV-Library's implementation in Golang](https://github.com/cv-library/spellchecker) or [node-aspell-spellchecker](https://github.com/smithatlanta/node-aspell-spellchecker)

Volunteers to find a good place to host the PHP implementation are welcome.

## Documentation

* [View documentation](https://github.com/badsyntax/jquery-spellchecker/wiki/Documentation)

## Examples

You can find simple usage examples in the downloadable package.

* [Fancy demos](http://jquery-spellchecker.badsyntax.co)
* [Basic demos](http://jquery-spellchecker.badsyntax.co/basic)


## Issues

Testing is much appreciated. Please post any issue you find in the [issue tracker](https://github.com/cv-library/jquery-spellchecker/issues).

## Contributing

* View the [contribute documentation](CONTRIBUTING.md) to learn how to contribute to the project.

## Thanks

This project would not be possible without the [findAndReplaceDOMText](https://github.com/padolsey/findAndReplaceDOMText) function written by [James Padolsey](https://github.com/padolsey).

Thanks to Richard Willis who [originally wrote](https://github.com/badsyntax/jquery-spellchecker) and maintained this plugin.

## License

Licensed under the MIT license.
