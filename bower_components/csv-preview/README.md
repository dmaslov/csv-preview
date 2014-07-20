# &lt;csv-preview&gt;

A [Polymer](http://polymer-project.org) element to preview csv data and structured data (array of map) in table format

## Demo

> [Check it live](http://dmaslov.github.io/csv-preview).

## Installation

Install using [Bower](http://bower.io):

```shell
 bower install csv-preview
```

## Usage

* Import Web Components' polyfill:

```
<script src="bower_components/platform/platform.js"></script>
<script src="bower_components/polymer/polymer.js"></script>
```

* Import Custom Element:

```
<link rel="import" href="bower_components/csv-preview/csv-preview.html">
```

* Start using it!(need to pass raw csv data somehow into element. Investigate index.html to see exmple)

```
<csv-preview data=""></csv-preview>
```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`data`      | *string*                  | ``                  | raw csv data (comma delimied)


## License

[MIT License](http://opensource.org/licenses/MIT)
