---
layout: home
---
# consola.css [![NPM][icon-npm]][link-npm] [![Bower][icon-bower]][link-bower] [![NPM Downloads][icon-npm-dt]][link-npm] [![license][icon-license]][link-license] [![Code Climate][icon-codeclimate]][link-codeclimate]
consola.css is a lightweight CSS micro-framework for a console like style.

It is very minimalistic and has therefore a small footprint of under **5.2 kB gzipped**.
It also includes SCSS and CSS files and comes with a gulpfile for customizing the build.

## Installation

Via bower
 ```
 $ bower install --save consola.css
 ```

Via npm
 ```
 $ npm install --save consola.css
 ```

### Using the SCSS

In your SCSS file, you can import consola.css:

```scss
@import "/path/to/consola.css/scss/consola";
```

Variables are stored in the `scss/_variables.scss` file, so they can be easily customized:
```scss
$font-size: 14px;
$red: #ff0000;

@import "/path/to/consola.css/scss/consola";
```

### Using the CSS
Just add a `<link>` in your `<head>` of either `consola.css` or
the minified version `consola.min.css`.

## License
MIT License - Copyright (c) 2016 Pascal Kleindienst

See [LICENSE](LICENSE) for full license description

## Credits
* [Normalize](http://necolas.github.io/normalize.css) for the foundation.
* [Flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid) for the grid style.


[icon-codeclimate]: https://api.codeclimate.com/v1/badges/7fe8ca1359f70a009a19/maintainability
[link-codeclimate]: https://codeclimate.com/github/PascalKleindienst/consola.css/maintainability
[icon-license]: https://img.shields.io/github/license/PascalKleindienst/consola.css.svg?style=flat-square
[link-license]: https://raw.githubusercontent.com/PascalKleindienst/consola.css/master/LICENSE
[icon-npm]: https://img.shields.io/npm/v/consola.css.svg?style=flat-square
[link-npm]: https://www.npmjs.com/package/consola.css
[icon-npm-dt]: https://img.shields.io/npm/dt/consola.css.svg?style=flat-square
[icon-bower]: https://img.shields.io/bower/v/consola.css.svg?style=flat-square
[link-bower]: https://github.com/PascalKleindienst/consola.css