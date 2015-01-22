# &lt;csv-preview&gt; [![Build Status](https://travis-ci.org/dmaslov/csv-preview.svg?branch=master)](https://travis-ci.org/dmaslov/csv-preview)

A [Polymer](http://polymer-project.org) element to preview csv data and structured data (array of map) in table format

## Demo

> [Check it live](http://dmaslov.github.io/csv-preview).

## Installation

Install using [Bower](http://bower.io):

```shell
 bower install csv-preview
```

## Usage

* Import Polyfill Web Components support for older browsers:

```
<script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
```

* Import Custom Element:

```
<link rel="import" href="bower_components/csv-preview/csv-preview.html">
```

* Start using it!(need to pass raw csv data somehow into element. Investigate index.html to see exmple)

* If column separator of csv data is not comma, pass it in `separator` attribute. The `separator` attribute is not required, you may remove it if column delimeter is comma (by default)

```
<csv-preview data="" separator=""></csv-preview>
```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`data`      | *string*                  | ``                  | raw csv data (comma delimied by default)
`separator`      | *string*                  | `,`                  | column separator (",", ";", etc)


## Tests

```shell
npm install -g web-component-tester
wct
```

## License

[MIT License](http://opensource.org/licenses/MIT)
