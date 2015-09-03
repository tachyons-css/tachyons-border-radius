# tachyons-border-radius
2.1.0

Performance based css module.

## Install
```
npm install --save-dev tachyons-border-radius
```

or download the css on github and include in your project:

```
git clone git@github.com:mrmrs/tachyons-border-radius
```

## The Code
```
/*

   BORDER RADIUS

   Base:
     br   = border-radius

   Modifiers:
     n    = none
     1    = 1st step in scale
     2    = 2nd step in scale
     3    = 3rd step in scale
     4    = 4th step in scale
     5    = 5th step in scale
     circ = circle
     -100 = 100%

   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large

*/

  .brn {        border-radius: 0; }
  .br1 {        border-radius: .125rem; }
  .br2 {        border-radius: .25rem; }
  .br3 {        border-radius: .5rem; }
  .br4 {        border-radius: 1rem; }
  .br5 {        border-radius: 2rem; }
  .br-100 {     border-radius: 100%; }

@media screen and (min-width: 48em) {
  .brn-ns {     border-radius: 0; }
  .br1-ns {     border-radius: .125rem; }
  .br2-ns {     border-radius: .25rem; }
  .br3-ns {     border-radius: .5rem; }
  .br4-ns {     border-radius: 1rem; }
  .br5-ns {     border-radius: 2rem; }
  .br-100-ns {  border-radius: 100%; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .brn-m {     border-radius: 0; }
  .br1-m {     border-radius: .125rem; }
  .br2-m {     border-radius: .25rem; }
  .br3-m {     border-radius: .5rem; }
  .br4-m {     border-radius: 1rem; }
  .br5-m {     border-radius: 2rem; }
  .br-100-m {  border-radius: 100%; }
}

@media screen and (min-width: 64em) {
  .brn-l {     border-radius: 0; }
  .br1-l {     border-radius: .125rem; }
  .br2-l {     border-radius: .25rem; }
  .br3-l {     border-radius: .5rem; }
  .br4-l {     border-radius: 1rem; }
  .br5-l {     border-radius: 2rem; }
  .br-100-l {  border-radius: 100%; }
}

```

## Author

[mrmrs](http://mrmrs.io)

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

