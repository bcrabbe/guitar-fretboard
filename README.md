# \<guitar-fret-board\>

a guitar fret board graphic for displaying notes and chord shapes.
<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="../guitar-fret-board.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
  <guitar-fret-board chord='{"str6":[{"fret":5,"label":"1"}],
	                            "str5":[{"fret":7,"label":"3"}],
	                            "str4":[{"fret":7,"label":"4"}],
	                            "str3":[{"fret":6,"label":"2"}],
	                            "str2":[{"fret":5,"label":"1"}],
	                            "str1":[{"fret":5, "label":"1"}]}'
	  ></guitar-fret-board>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Install Dependancies
```
$ bower install
```

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```
