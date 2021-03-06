# PostCSS colorstring [![Build Status](https://travis-ci.org/keukenrolletje/postcss-colorstring.svg?branch=master)](https://travis-ci.org/keukenrolletje/postcss-colorstring)

[PostCSS] plugin to turn any string into a valid color.

based on<br />
http://stackoverflow.com/questions/8318911/why-does-html-think-chucknorris-is-a-color<br />
http://scrappy-do.blogspot.be/2004/08/little-rant-about-microsoft-internet.html

[PostCSS]: https://github.com/postcss/postcss
[ci-img]:  https://travis-ci.org/keukenrolletje/postcss-celebcolors.svg
[ci]:      https://travis-ci.org/keukenrolletje/postcss-celebcolors

## Installation

```bash
$ npm install postcss-color-hcl
```

##Usage

```js
postcss([ require('postcss-colorstring') ])
```

Using this `input.css`:
```css
.foo {
  color-ie:  Supercalifragilisticexpialidocious;
}
```
you will get:
```css
.foo {
  color: #0c000c;
}
```

See [PostCSS] docs for examples for your environment.
