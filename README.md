# \<id-alert\>

Idaho alert element

## Installation

Add the following to bower.json.

```JSON
{
  "id-alert": "https://github.com/accessidaho/egov-id-alert.git"
}
```

## Usage

Import the element:

```html
<link rel="import" href="bower_components/id-alert/id-alert.html">
```

Add the element and set properties:

```html
<id-alert color="[success, warning, danger]">Alert Message</id-alert>
```

## Styling

`<id-alert>` provides the following custom properties for styling:

Custom property | Description | Default
----------------|-------------|----------
`--id-primary-light-border` | Default border color | #d9edf7
`--id-primary-light` | Default background color | #eef7fb

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
