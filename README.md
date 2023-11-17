# SDML language highlighter for highlight.js

![SDML Logo Text](https://raw.githubusercontent.com/sdm-lang/.github/main/profile/horizontal-text.svg)

## Usage

Simply include the Highlight.js library in your webpage or Node app, then load this module.

### Static website or simple usage

Simply load the module after loading Highlight.js. You'll use the minified version found in the `dist` directory. This
module is just a CDN build of the language, so it will register itself as the Javascript is loaded.

```html
<script type="text/javascript" src="/path/to/highlight.min.js"></script>
<script type="text/javascript" charset="UTF-8"
  src="/path/to/highlightjs-sdml/dist/sdml.min.js"></script>
<script type="text/javascript">
  hljs.initHighlightingOnLoad();
</script>
```

### With Node or another build system

If you're using Node, Webpack, Rollup, Browserify, etc, simply require the language module, then register it with
Highlight.js.

```javascript
var hljs = require('highlightjs');
var hljsChaos = require('highlightjs-chaos');

hljs.registerLanguage("chaos", hljsChaos);
hljs.initHighlightingOnLoad();
```

## License

This package is released under the Apache License, Version 2.0. See LICENSE file for details.

## Changes

TBD

## Development

https://highlightjs.readthedocs.io/en/latest/language-contribution.html
https://github.com/highlightjs/highlight.js/blob/master/extra/3RD_PARTY_QUICK_START.md

## Changes

TBD
