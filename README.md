# anyenv-each [![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/) [![Build Status](https://travis-ci.org/Milly/anyenv-each.svg?branch=master)](https://travis-ci.org/Milly/anyenv-each)

This is an [anyenv](https://github.com/anyenv/anyenv) plugin that
provides `anyenv each` command to run sub-command of all \*\*env.

## Installation

Simply clone the repository into the plugins directory:

    mkdir -p $(anyenv root)/plugins
    git clone https://github.com/Milly/anyenv-each $(anyenv root)/plugins/anyenv-each

## Usage

    anyenv each [--verbose|--quiet] [--stop-on-error] [--] <command> [<options>]

## Options

* -v/--verbose         Shows all output and details to stdout
* -q/--quiet           Do not shows anything
* -e/--stop-on-error   Stop if \*\*env command exits with a non-zero status

## License

[CC0](http://creativecommons.org/publicdomain/zero/1.0/) (Public Domain)
