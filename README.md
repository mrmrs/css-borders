# CSS BORDERS

  Mobile-first classes for css-borders.
  Set the desired css-borders on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-borders
```
View on [npm](https://www.npmjs.org/package/css-borders)


## File Size

1.4K borders.css
1.1K borders.min.css
207B minified and gzipped

## The Code
```
  .ba { border-style: solid;            border-width: 1px; }
  .bt { border-top-style: solid;        border-top-width: 1px; }
  .br { border-right-style: solid;      border-right-width: 1px; }
  .bb { border-bottom-style: solid;     border-bottom-width: 1px; }
  .bl { border-left-style: solid;       border-left-width: 1px; }

@media screen and (min-width: 48em) {
  .ba-ns { border-style: solid;         border-width: 1px; }
  .bt-ns { border-top-style: solid;     border-top-width: 1px; }
  .br-ns { border-right-style: solid;   border-right-width: 1px; }
  .bb-ns { border-bottom-style: solid;  border-bottom-width: 1px; }
  .bl-ns { border-left-style: solid;    border-left-width: 1px; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .ba-m { border-style: solid;          border-width: 1px; }
  .bt-m { border-top-style: solid;      border-top-width: 1px; }
  .br-m { border-right-style: solid;    border-right-width: 1px; }
  .bb-m { border-bottom-style: solid;   border-bottom-width: 1px; }
  .bl-m { border-left-style: solid;     border-left-width: 1px; }
}

@media screen and (min-width: 64em)  {
  .ba-l { border-style: solid;          border-width: 1px; }
  .bt-l { border-top-style: solid;      border-top-width: 1px; }
  .br-l { border-right-style: solid;    border-right-width: 1px; }
  .bb-l { border-bottom-style: solid;   border-bottom-width: 1px; }
  .bl-l { border-left-style: solid;     border-left-width: 1px; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

