# CSS POSITION

  Mobile-first classes for css-position.
  Set the desired css-position on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-position
```
View on [npm](https://www.npmjs.org/package/css-position)


## File Size

4.0K position.css
2.8K position.min.css
-rw-r--r--  1    2.8K Jul 16 21:09 position.min.min.css

## The Code
```
.pos-stat { position: static; }
.pos-rel  { position: relative; }
.pos-abs  { position: absolute; }
.pos-fix  { position: fixed; }

/* Values */

.top-0    { top:   0; }
.left-0   { left:  0; }
.right-0  { right: 0; }
.bottom-0 { bottom: 0; }

.top-1    { top:   1rem; }
.left-1   { left:  1rem; }
.right-1  { right: 1rem; }
.bottom-1 { bottom: 1rem; }

.top-2    { top:   2rem; }
.left-2   { left:  2rem; }
.right-2  { right: 2rem; }
.bottom-2 { bottom: 2rem; }

.top-4    { top:   4rem; }
.left-4   { left:  4rem; }
.right-4  { right: 4rem; }
.bottom-4 { bottom: 4rem; }

/* Top Percentage based scale */

.top-10  { top: 10%; }
.top-20  { top: 20%; }
.top-30  { top: 30%; }
.top-40  { top: 40%; }
.top-50  { top: 50%; }
.top-60  { top: 60%; }
.top-70  { top: 70%; }
.top-80  { top: 80%; }
.top-90  { top: 90%; }
.top-100 { top: 100%; }

.top-auto { top: auto; }
.top-i { top: inherit; ;}

.center { margin: 0 auto; }

@media screen and (min-width: 48em) {
  .pos-stat-ns { position: static; }
  .pos-rel-ns  { position: relative; }
  .pos-abs-ns  { position: absolute; }
  .pos-fix-ns  { position: fixed; }
  .top-0-ns    { top:   0; }
  .left-0-ns   { left:  0; }
  .right-0-ns  { right: 0; }
  .bottom-0-ns { bottom: 0; }
  .top-1-ns    { top:   1rem; }
  .left-1-ns   { left:  1rem; }
  .right-1-ns  { right: 1rem; }
  .bottom-1-ns { bottom: 1rem; }
  .top-2-ns    { top:   2rem; }
  .left-2-ns   { left:  2rem; }
  .right-2-ns  { right: 2rem; }
  .bottom-2-ns { bottom: 2rem; }
  .top-4-ns    { top:   4rem; }
  .left-4-ns   { left:  4rem; }
  .right-4-ns  { right: 4rem; }
  .bottom-4-ns { bottom: 4rem; }
  .top-10-ns  { top: 10%; }
  .top-20-ns  { top: 20%; }
  .top-30-ns  { top: 30%; }
  .top-40-ns  { top: 40%; }
  .top-50-ns  { top: 50%; }
  .top-60-ns  { top: 60%; }
  .top-70-ns  { top: 70%; }
  .top-80-ns  { top: 80%; }
  .top-90-ns  { top: 90%; }
  .top-100-ns { top: 100%; }
  .top-auto-ns { top: auto; }
  .top-i-ns { top: inherit; ;}
  .center-ns { margin: 0 auto; }
}

@media screen and (min-width:48em) and (max-width: 64em) {
  .pos-stat-m { position: static; }
  .pos-rel-m  { position: relative; }
  .pos-abs-m  { position: absolute; }
  .pos-fix-m  { position: fixed; }
  .top-0-m    { top:   0; }
  .left-0-m   { left:  0; }
  .right-0-m  { right: 0; }
  .bottom-0-m { bottom: 0; }
  .top-1-m    { top:   1rem; }
  .left-1-m   { left:  1rem; }
  .right-1-m  { right: 1rem; }
  .bottom-1-m { bottom: 1rem; }
  .top-2-m    { top:   2rem; }
  .left-2-m   { left:  2rem; }
  .right-2-m  { right: 2rem; }
  .bottom-2-m { bottom: 2rem; }
  .top-4-m    { top:   4rem; }
  .left-4-m   { left:  4rem; }
  .right-4-m  { right: 4rem; }
  .bottom-4-m { bottom: 4rem; }
  .top-10-m  { top: 10%; }
  .top-20-m  { top: 20%; }
  .top-30-m  { top: 30%; }
  .top-40-m  { top: 40%; }
  .top-50-m  { top: 50%; }
  .top-60-m  { top: 60%; }
  .top-70-m  { top: 70%; }
  .top-80-m  { top: 80%; }
  .top-90-m  { top: 90%; }
  .top-100-m { top: 100%; }
  .top-auto-m { top: auto; }
  .top-i-m { top: inherit; ;}
  .center-m { margin: 0 auto; }
}

@media screen and (min-width: 64em) {
  .pos-stat-l { position: static; }
  .pos-rel-l  { position: relative; }
  .pos-abs-l  { position: absolute; }
  .pos-fix-l  { position: fixed; }
  .top-0-l    { top:   0; }
  .left-0-l   { left:  0; }
  .right-0-l  { right: 0; }
  .bottom-0-l { bottom: 0; }
  .top-1-l    { top:   1rem; }
  .left-1-l   { left:  1rem; }
  .right-1-l  { right: 1rem; }
  .bottom-1-l { bottom: 1rem; }
  .top-2-l    { top:   2rem; }
  .left-2-l   { left:  2rem; }
  .right-2-l  { right: 2rem; }
  .bottom-2-l { bottom: 2rem; }
  .top-4-l    { top:   4rem; }
  .left-4-l   { left:  4rem; }
  .right-4-l  { right: 4rem; }
  .bottom-4-l { bottom: 4rem; }
  .top-10-l  { top: 10%; }
  .top-20-l  { top: 20%; }
  .top-30-l  { top: 30%; }
  .top-40-l  { top: 40%; }
  .top-50-l  { top: 50%; }
  .top-60-l  { top: 60%; }
  .top-70-l  { top: 70%; }
  .top-80-l  { top: 80%; }
  .top-90-l  { top: 90%; }
  .top-100-l { top: 100%; }
  .top-auto-l { top: auto; }
  .top-i-l { top: inherit; ;}
  .center-l { margin: 0 auto; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

