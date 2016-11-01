# css-column-count 1.0.6

Css module of single purpose classes for column count

#### Stats

540 | 68 | 204
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-column-count
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-column-count
```

ssh:
```
git clone git@github.com:tachyons-css/css-column-count.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-column-count";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-column-count@1.0.6/css/css-column-count.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-column-count">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   COLUMN COUNT
*/
.cc-1 { -webkit-column-count: 1; -moz-column-count: 1; column-count: 1; }
.cc-2 { -webkit-column-count: 2; -moz-column-count: 2; column-count: 2; }
.cc-3 { -webkit-column-count: 3; -moz-column-count: 3; column-count: 3; }
.cc-4 { -webkit-column-count: 4; -moz-column-count: 4; column-count: 4; }
.cc-5 { -webkit-column-count: 5; -moz-column-count: 5; column-count: 5; }
.cc-6 { -webkit-column-count: 6; -moz-column-count: 6; column-count: 6; }
.cc-7 { -webkit-column-count: 7; -moz-column-count: 7; column-count: 7; }
.cc-8 { -webkit-column-count: 8; -moz-column-count: 8; column-count: 8; }
.cc-9 { -webkit-column-count: 9; -moz-column-count: 9; column-count: 9; }
.cc-10 { -webkit-column-count: 10; -moz-column-count: 10; column-count: 10; }
.cc-11 { -webkit-column-count: 11; -moz-column-count: 11; column-count: 11; }
.cc-12 { -webkit-column-count: 12; -moz-column-count: 12; column-count: 12; }
.cc-13 { -webkit-column-count: 13; -moz-column-count: 13; column-count: 13; }
.cc-14 { -webkit-column-count: 14; -moz-column-count: 14; column-count: 14; }
.cc-15 { -webkit-column-count: 15; -moz-column-count: 15; column-count: 15; }
.cc-16 { -webkit-column-count: 16; -moz-column-count: 16; column-count: 16; }
.cc-auto { -webkit-column-count: auto; -moz-column-count: auto; column-count: auto; }
@media screen and (min-width: 48em) {
 .cc-1-ns { -webkit-column-count: 1; -moz-column-count: 1; column-count: 1; }
 .cc-2-ns { -webkit-column-count: 2; -moz-column-count: 2; column-count: 2; }
 .cc-3-ns { -webkit-column-count: 3; -moz-column-count: 3; column-count: 3; }
 .cc-4-ns { -webkit-column-count: 4; -moz-column-count: 4; column-count: 4; }
 .cc-5-ns { -webkit-column-count: 5; -moz-column-count: 5; column-count: 5; }
 .cc-6-ns { -webkit-column-count: 6; -moz-column-count: 6; column-count: 6; }
 .cc-7-ns { -webkit-column-count: 7; -moz-column-count: 7; column-count: 7; }
 .cc-8-ns { -webkit-column-count: 8; -moz-column-count: 8; column-count: 8; }
 .cc-9-ns { -webkit-column-count: 9; -moz-column-count: 9; column-count: 9; }
 .cc-10-ns { -webkit-column-count: 10; -moz-column-count: 10; column-count: 10; }
 .cc-11-ns { -webkit-column-count: 11; -moz-column-count: 11; column-count: 11; }
 .cc-12-ns { -webkit-column-count: 12; -moz-column-count: 12; column-count: 12; }
 .cc-13-ns { -webkit-column-count: 13; -moz-column-count: 13; column-count: 13; }
 .cc-14-ns { -webkit-column-count: 14; -moz-column-count: 14; column-count: 14; }
 .cc-15-ns { -webkit-column-count: 15; -moz-column-count: 15; column-count: 15; }
 .cc-16-ns { -webkit-column-count: 16; -moz-column-count: 16; column-count: 16; }
 .cc-auto-ns { -webkit-column-count: auto; -moz-column-count: auto; column-count: auto; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .cc-1-m { -webkit-column-count: 1; -moz-column-count: 1; column-count: 1; }
 .cc-2-m { -webkit-column-count: 2; -moz-column-count: 2; column-count: 2; }
 .cc-3-m { -webkit-column-count: 3; -moz-column-count: 3; column-count: 3; }
 .cc-4-m { -webkit-column-count: 4; -moz-column-count: 4; column-count: 4; }
 .cc-5-m { -webkit-column-count: 5; -moz-column-count: 5; column-count: 5; }
 .cc-6-m { -webkit-column-count: 6; -moz-column-count: 6; column-count: 6; }
 .cc-7-m { -webkit-column-count: 7; -moz-column-count: 7; column-count: 7; }
 .cc-8-m { -webkit-column-count: 8; -moz-column-count: 8; column-count: 8; }
 .cc-9-m { -webkit-column-count: 9; -moz-column-count: 9; column-count: 9; }
 .cc-10-m { -webkit-column-count: 10; -moz-column-count: 10; column-count: 10; }
 .cc-11-m { -webkit-column-count: 11; -moz-column-count: 11; column-count: 11; }
 .cc-12-m { -webkit-column-count: 12; -moz-column-count: 12; column-count: 12; }
 .cc-13-m { -webkit-column-count: 13; -moz-column-count: 13; column-count: 13; }
 .cc-14-m { -webkit-column-count: 14; -moz-column-count: 14; column-count: 14; }
 .cc-15-m { -webkit-column-count: 15; -moz-column-count: 15; column-count: 15; }
 .cc-16-m { -webkit-column-count: 16; -moz-column-count: 16; column-count: 16; }
 .cc-auto-m { -webkit-column-count: auto; -moz-column-count: auto; column-count: auto; }
}
@media screen and (min-width: 64em) {
 .cc-1-l { -webkit-column-count: 1; -moz-column-count: 1; column-count: 1; }
 .cc-2-l { -webkit-column-count: 2; -moz-column-count: 2; column-count: 2; }
 .cc-3-l { -webkit-column-count: 3; -moz-column-count: 3; column-count: 3; }
 .cc-4-l { -webkit-column-count: 4; -moz-column-count: 4; column-count: 4; }
 .cc-5-l { -webkit-column-count: 5; -moz-column-count: 5; column-count: 5; }
 .cc-6-l { -webkit-column-count: 6; -moz-column-count: 6; column-count: 6; }
 .cc-7-l { -webkit-column-count: 7; -moz-column-count: 7; column-count: 7; }
 .cc-8-l { -webkit-column-count: 8; -moz-column-count: 8; column-count: 8; }
 .cc-9-l { -webkit-column-count: 9; -moz-column-count: 9; column-count: 9; }
 .cc-10-l { -webkit-column-count: 10; -moz-column-count: 10; column-count: 10; }
 .cc-11-l { -webkit-column-count: 11; -moz-column-count: 11; column-count: 11; }
 .cc-12-l { -webkit-column-count: 12; -moz-column-count: 12; column-count: 12; }
 .cc-13-l { -webkit-column-count: 13; -moz-column-count: 13; column-count: 13; }
 .cc-14-l { -webkit-column-count: 14; -moz-column-count: 14; column-count: 14; }
 .cc-15-l { -webkit-column-count: 15; -moz-column-count: 15; column-count: 15; }
 .cc-16-l { -webkit-column-count: 16; -moz-column-count: 16; column-count: 16; }
 .cc-auto-l { -webkit-column-count: auto; -moz-column-count: auto; column-count: auto; }
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

ISC

