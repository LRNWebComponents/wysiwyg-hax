<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="wysiwyg-hax.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wysiwyg-hax></wysiwyg-hax>
```

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/LRNWebComponents/wysiwyg-hax)

# \<wysiwyg-hax\>

A wrapper for cms-hax which then makes it easier to pull into a wysiwyg field. This allows for replacing `<textarea>` tags currently in existing systems with a wysiwyg-hax tag which is rigged up.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
