# JsonReader


[![CI Status](https://github.com/pcrov/JsonReader/workflows/CI/badge.svg)](https://github.com/pcrov/JsonReader/actions?query=workflow%3ACI)
[![Coverage Status](https://coveralls.io/repos/github/pcrov/JsonReader/badge.svg?branch=master)](https://coveralls.io/github/pcrov/JsonReader?branch=master)
[![License](https://poser.pugx.org/pcrov/jsonreader/license)](https://github.com/pcrov/JsonReader/blob/master/LICENSE)
[![Latest Stable Version](https://poser.pugx.org/pcrov/jsonreader/v/stable)](https://packagist.org/packages/pcrov/jsonreader)

This is a streaming pull parser - like [XMLReader](http://php.net/xmlreader) but for JSON.

## Requirements

PHP 7.3 or higher with the Intl extension.

## Installation

To install with composer:

```sh
composer require pcrov/jsonreader
```

## Usage

JsonReader's interface and behavior is very much like [XMLReader](http://php.net/xmlreader). If you've worked with that then
this will feel familiar.

For [examples](https://github.com/pcrov/JsonReader/wiki/Examples) and
[API documentation](https://github.com/pcrov/JsonReader/wiki/JsonReader-API) see
the [wiki](https://github.com/pcrov/JsonReader/wiki).

## Note

Only UTF-8 encoded JSON is supported. If you need to parse JSON in another encoding
see [Handling Non UTF-8 Encodings](https://github.com/pcrov/JsonReader/wiki/Handling-Non-UTF-8-Encodings)
on the [wiki](https://github.com/pcrov/JsonReader/wiki).
