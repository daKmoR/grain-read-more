[![Polymer Version](https://img.shields.io/badge/polymer-v2-blue.svg)](https://www.polymer-project.org)

# \<read-more\>

Opens more content on click.

## Installation

```sh
$ bower install --save daKmoR/read-more
```

## Getting Started

Import the package.

```html
<link rel="import" href="/bower_components/read-more/read-more.html">
```

To define a custom dialog with markup, use the `nebula-dialog` element.

```html
<read-more>
  <h3>Read More</h3>
  <div slot="more">
    The Content is only visible if read-more is opened
  </div>
</read-more>
```

*For more information, see the API documentation.*

## Working on the Element

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.
* View the Element via `polymer serve`
* Run tests via `polymer test`
