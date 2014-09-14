# Diff to Html Node Module by [rtfpessoa](https://github.com/rtfpessoa)

Diff to Html generates pretty HTML diffs.

### Inspiration

This project uses [diff2html](https://github.com/rtfpessoa/diff2html) as base.

## Features

* `line-by-line` and `side-by-side` diff

* char-by-char highlight

* new and old line numbers

* inserted and removed lines

* GitHub like style

## Online Example

> Go to [Diff2HTML](http://rtfpessoa.github.io/diff2html/)

## Other Distributions

* [WebJar](http://www.webjars.org/)

* Manually download and import [diff2html.js](https://github.com/rtfpessoa/diff2html) into your page

## Setup

    sudo npm install -g diff2html

## Usage

    Usage: diff2html [git-diff options]

    Options:

        -h, --help           output usage information
        -V, --version        output the version number
        -i, --input [file]   Diff input file.
        -o, --output [file]  Output to file path. Defaults to stdout.
        -p, --preview        Open preview in the browser.
        -l, --line           Line by Line diff.
        -s, --side           Side by Side diff.
        -j, --json           Export diff in json format.

## Contribution

All contributions are welcome.

To contribute just send a pull request with your feature,fix,... and it will be reviewed asap.

## License

Copyright 2014 Rodrigo Fernandes. Released under the terms of the MIT license.

---