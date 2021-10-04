# sinister six

An 11ty plugin that extends markdown-it's functionality

> This plugin is built entirely based on my preference and my markdown workflow

## Features:
- [markdown-it-anchor](https://github.com/valeriangalliat/markdown-it-anchor)
- [markdown-it-attrs](https://github.com/arve0/markdown-it-attrs)
- A [modified](/src/cite.js) version of [markdown-it-attribution](https://github.com/dweidner/markdown-it-attribution/)
- A [modified](/src/footnote.js)version of [markdown-it-footnote](https://github.com/markdown-it/markdown-it-footnote/)
- [markdown-it-image-figures](https://github.com/Antonio-Laguna/markdown-it-image-figures/)
- [markdown-it-mark](https://github.com/markdown-it/markdown-it-mark/)

## Usage
In your 11ty project:
```
npm i sinister-six
```

then add this to your site's .eleventy.js (or equivalent):

```js
const sinisterSix = require('sinister-six');

module.exports = function (eleventyConfig) {
  eleventyConfig.addPlugin(sinisterSix);
}
```
