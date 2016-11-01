# css-borders 1.0.6

Css module of single purpose classes for borders

#### Stats

241 | 20 | 40
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-borders
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-borders
```

ssh:
```
git clone git@github.com:tachyons-css/css-borders.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-borders";
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
<link rel="stylesheet" href="http://unpkg.com/css-borders@1.0.6/css/css-borders.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-borders">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   BORDERS
*/
.ba { border-style: solid; border-width: 1px; }
.bt { border-top-style: solid; border-top-width: 1px; }
.br { border-right-style: solid; border-right-width: 1px; }
.bb { border-bottom-style: solid; border-bottom-width: 1px; }
.bl { border-left-style: solid; border-left-width: 1px; }
@media screen and (min-width: 48em) {
 .ba-ns { border-style: solid; border-width: 1px; }
 .bt-ns { border-top-style: solid; border-top-width: 1px; }
 .br-ns { border-right-style: solid; border-right-width: 1px; }
 .bb-ns { border-bottom-style: solid; border-bottom-width: 1px; }
 .bl-ns { border-left-style: solid; border-left-width: 1px; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .ba-m { border-style: solid; border-width: 1px; }
 .bt-m { border-top-style: solid; border-top-width: 1px; }
 .br-m { border-right-style: solid; border-right-width: 1px; }
 .bb-m { border-bottom-style: solid; border-bottom-width: 1px; }
 .bl-m { border-left-style: solid; border-left-width: 1px; }
}
@media screen and (min-width: 64em) {
 .ba-l { border-style: solid; border-width: 1px; }
 .bt-l { border-top-style: solid; border-top-width: 1px; }
 .br-l { border-right-style: solid; border-right-width: 1px; }
 .bb-l { border-bottom-style: solid; border-bottom-width: 1px; }
 .bl-l { border-left-style: solid; border-left-width: 1px; }
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

