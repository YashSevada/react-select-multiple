# react-multiselect

**A ReactJS component to render a multiselect (with a filter).**

This component creates a list of checkboxes to select options.
Behind the scenes an hidden tag <select> is updated with your selected options.

<img src="./docs/img/example.png" alt="Example" />

## Installation

Install `react-multiselect` with [npm](https://www.npmjs.com/):

```
$ npm install react-multiselect
```

For [CommonJS](http://wiki.commonjs.org/wiki/CommonJS) users:

```javascript
var ReactMultiselect = require('react-multiselect');
```

## Options

* list [array] (required): the initial list of options as an array of objects like that:

```javascript
[
    {value: "FR", title: "France"},
    {value: "BE", title: "Belgique"},
    {value: "ES", title: "Espagne"},
    {value: "IT", title: "Italie"},
    {value: "DE", title: "Allemagne"}
]
```

* selectors [bool]: if set to true, it display links to select all/none options in one click
* selectAllLabel [string]: the "select all" label
* selectNoneLabel [string]: the "select none" label
* checkedByDefault [array]: a list of preselected options. Example:

```javascript
[
    {value: "BE", title: "Belgique"},
    {value: "ES", title: "Espagne"}
]
```

* filterPlaceholder [string]: a placeholder for the input filter

## Demo

Clone the repository and move into:

```console
$ git clone git@github.com:AdeleD/react-multiselect.git
$ cd react-multiselect
```

Open the file [example/index.html](http://github.com/AdeleD/react-multiselect/example/index.html) to see the result.
