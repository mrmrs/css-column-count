# css-column-count 0.0.7

Css module of single purpose classes for column count

#### Stats

390 | 68 | 68
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-column-count
```

#### With Git

```
git clone https://github.com/tachyons-css/css-column-count
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-column-count";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-column-count">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   COLUMN COUNT
*/
.cc-1 { column-count: 1; }
.cc-2 { column-count: 2; }
.cc-3 { column-count: 3; }
.cc-4 { column-count: 4; }
.cc-5 { column-count: 5; }
.cc-6 { column-count: 6; }
.cc-7 { column-count: 7; }
.cc-8 { column-count: 8; }
.cc-9 { column-count: 9; }
.cc-10 { column-count: 10; }
.cc-11 { column-count: 11; }
.cc-12 { column-count: 12; }
.cc-13 { column-count: 13; }
.cc-14 { column-count: 14; }
.cc-15 { column-count: 15; }
.cc-16 { column-count: 16; }
.cc-auto { column-count: auto; }
@media screen and (min-width: 48em) {
 .cc-1-ns { column-count: 1; }
 .cc-2-ns { column-count: 2; }
 .cc-3-ns { column-count: 3; }
 .cc-4-ns { column-count: 4; }
 .cc-5-ns { column-count: 5; }
 .cc-6-ns { column-count: 6; }
 .cc-7-ns { column-count: 7; }
 .cc-8-ns { column-count: 8; }
 .cc-9-ns { column-count: 9; }
 .cc-10-ns { column-count: 10; }
 .cc-11-ns { column-count: 11; }
 .cc-12-ns { column-count: 12; }
 .cc-13-ns { column-count: 13; }
 .cc-14-ns { column-count: 14; }
 .cc-15-ns { column-count: 15; }
 .cc-16-ns { column-count: 16; }
 .cc-auto-ns { column-count: auto; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .cc-1-m { column-count: 1; }
 .cc-2-m { column-count: 2; }
 .cc-3-m { column-count: 3; }
 .cc-4-m { column-count: 4; }
 .cc-5-m { column-count: 5; }
 .cc-6-m { column-count: 6; }
 .cc-7-m { column-count: 7; }
 .cc-8-m { column-count: 8; }
 .cc-9-m { column-count: 9; }
 .cc-10-m { column-count: 10; }
 .cc-11-m { column-count: 11; }
 .cc-12-m { column-count: 12; }
 .cc-13-m { column-count: 13; }
 .cc-14-m { column-count: 14; }
 .cc-15-m { column-count: 15; }
 .cc-16-m { column-count: 16; }
 .cc-auto-m { column-count: auto; }
}
@media screen and (min-width: 64em) {
 .cc-1-l { column-count: 1; }
 .cc-2-l { column-count: 2; }
 .cc-3-l { column-count: 3; }
 .cc-4-l { column-count: 4; }
 .cc-5-l { column-count: 5; }
 .cc-6-l { column-count: 6; }
 .cc-7-l { column-count: 7; }
 .cc-8-l { column-count: 8; }
 .cc-9-l { column-count: 9; }
 .cc-10-l { column-count: 10; }
 .cc-11-l { column-count: 11; }
 .cc-12-l { column-count: 12; }
 .cc-13-l { column-count: 13; }
 .cc-14-l { column-count: 14; }
 .cc-15-l { column-count: 15; }
 .cc-16-l { column-count: 16; }
 .cc-auto-l { column-count: auto; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

