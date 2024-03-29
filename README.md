# PADDING

  A mobile-first, eight-step padding scale based on powers of 2.
  Set the desired padding on any combination of sides on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install padding.css --save-dev
```
or download the css on github and include in your project.

## File Size
minified & gzipped - 961B
padding.min.css - 6.8K
padding.css - 9.4K

## The Code
```
/*
   PADDING

   An eight step scale based on powers of two ranging from 0 to 16rem

   Legend:

   p = padding

   a = all
   h = horizontal
   v = vertical
   t = top
   r = right
   b = bottom
   l = left

   n = none
   xs = extra small
   s = small
   m = medium
   l = large
   x = extra
   xl = extra large
   xxl = extra extra large

*/

.pan  {  padding: 0; }
.paxs {  padding: .25rem; }
.pas  {  padding: .5rem; }
.pam  {  padding: 1rem; }
.pal  {  padding: 2rem; }
.pax  {  padding: 4rem; }
.paxl {  padding: 8rem; }
.paxxl { padding: 16rem; }

.pln  {  padding-left: 0; }
.plxs {  padding-left: .25rem; }
.pls  {  padding-left: .5rem; }
.plm  {  padding-left: 1rem; }
.pll  {  padding-left: 2rem; }
.plx  {  padding-left: 4rem; }
.plxl {  padding-left: 8rem; }
.plxxl { padding-left: 16rem; }

.prn  {  padding-right: 0; }
.prxs {  padding-right: .25rem; }
.prs  {  padding-right: .5rem; }
.prm  {  padding-right: 1rem; }
.prl  {  padding-right: 2rem; }
.prx  {  padding-right: 4rem; }
.prxl {  padding-right: 8rem; }
.prxxl { padding-right: 16rem; }

.pbn  {  padding-bottom: 0; }
.pbxs {  padding-bottom: .25rem; }
.pbs  {  padding-bottom: .5rem; }
.pbm  {  padding-bottom: 1rem; }
.pbl  {  padding-bottom: 2rem; }
.pbx  {  padding-bottom: 4rem; }
.pbxl {  padding-bottom: 8rem; }
.pbxxl { padding-bottom: 16rem; }

.ptn  {  padding-top: 0; }
.ptxs {  padding-top: .25rem; }
.pts  {  padding-top: .5rem; }
.ptm  {  padding-top: 1rem; }
.ptl  {  padding-top: 2rem; }
.ptx  {  padding-top: 4rem; }
.ptxl {  padding-top: 8rem; }
.ptxxl { padding-top: 16rem; }

.pvn {   padding-top: 0;       padding-bottom: 0; }
.pvxs {  padding-top: .25rem;  padding-bottom: .25rem; }
.pvs {   padding-top: .5rem;   padding-bottom: .5rem; }
.pvm {   padding-top: 1rem;    padding-bottom: 1rem; }
.pvl {   padding-top: 2rem;    padding-bottom: 2rem; }
.pvx {   padding-top: 4rem;    padding-bottom: 4rem; }
.pvxl {  padding-top: 8rem;    padding-bottom: 8rem; }
.pvxxl { padding-top: 16rem;   padding-bottom: 16rem; }

.phn {   padding-left: 0;      padding-right: 0; }
.pvxs {  padding-left: .25rem; padding-right: .25rem; }
.phs {   padding-left: .5rem;  padding-right: .5rem; }
.phm {   padding-left: 1rem;   padding-right: 1rem; }
.phl {   padding-left: 2rem;   padding-right: 2rem; }
.phx {   padding-left: 4rem;   padding-right: 4rem; }
.phxl {  padding-left: 8rem;   padding-right: 8rem; }
.phxxl { padding-left: 16rem;  padding-right: 16rem; }

@media screen and (min-width: 48em) {
  .pan-ns  {  padding: 0; }
  .paxs-ns {  padding: .25rem; }
  .pas-ns  {  padding: .5rem; }
  .pam-ns  {  padding: 1rem; }
  .pal-ns  {  padding: 2rem; }
  .pax-ns  {  padding: 4rem; }
  .paxl-ns {  padding: 8rem; }
  .paxxl-ns { padding: 16rem; }

  .pln-ns  {  padding-left: 0; }
  .plxs-ns {  padding-left: .25rem; }
  .pls-ns  {  padding-left: .5rem; }
  .plm-ns  {  padding-left: 1rem; }
  .pll-ns  {  padding-left: 2rem; }
  .plx-ns  {  padding-left: 4rem; }
  .plxl-ns {  padding-left: 8rem; }
  .plxxl-ns { padding-left: 16rem; }

  .prn-ns  {  padding-right: 0; }
  .prxs-ns {  padding-right: .25rem; }
  .prs-ns  {  padding-right: .5rem; }
  .prm-ns  {  padding-right: 1rem; }
  .prl-ns  {  padding-right: 2rem; }
  .prx-ns {   padding-right: 4rem; }
  .prxl-ns {  padding-right: 8rem; }
  .prxxl-ns { padding-right: 16rem; }

  .pbn-ns  {  padding-bottom: 0; }
  .pbxs-ns {  padding-bottom: .25rem; }
  .pbs-ns  {  padding-bottom: .5rem; }
  .pbm-ns  {  padding-bottom: 1rem; }
  .pbl-ns  {  padding-bottom: 2rem; }
  .pbx-ns  {  padding-bottom: 4rem; }
  .pbxl-ns {  padding-bottom: 8rem; }
  .pbxxl-ns { padding-bottom: 16rem; }

  .ptn-ns  {  padding-top: 0; }
  .ptxs-ns {  padding-top: .25rem; }
  .pts-ns  {  padding-top: .5rem; }
  .ptm-ns  {  padding-top: 1rem; }
  .ptl-ns  {  padding-top: 2rem; }
  .ptx-ns  {  padding-top: 4rem; }
  .ptxl-ns {  padding-top: 8rem; }
  .ptxxl-ns { padding-top: 16rem; }

  .pvn-ns {   padding-top: 0;       padding-bottom: 0; }
  .pvxs-ns {  padding-top: .25rem;  padding-bottom: .25rem; }
  .pvs-ns {   padding-top: .5rem;   padding-bottom: .5rem; }
  .pvm-ns {   padding-top: 1rem;    padding-bottom: 1rem; }
  .pvl-ns {   padding-top: 2rem;    padding-bottom: 2rem; }
  .pvx-ns {   padding-top: 4rem;    padding-bottom: 4rem; }
  .pvxl-ns {  padding-top: 8rem;    padding-bottom: 8rem; }
  .pvxxl-ns { padding-top: 16rem;   padding-bottom: 16rem; }

  .phn-ns {   padding-left: 0;      padding-right: 0; }
  .pvxs-ns {  padding-left: .25rem; padding-right: .25rem; }
  .phs-ns {   padding-left: .5rem;  padding-right: .5rem; }
  .phm-ns {   padding-left: 1rem;   padding-right: 1rem; }
  .phl-ns {   padding-left: 2rem;   padding-right: 2rem; }
  .phx-ns {   padding-left: 4rem;   padding-right: 4rem; }
  .phxl-ns {  padding-left: 8rem;   padding-right: 8rem; }
  .phxxl-ns { padding-left: 16rem;  padding-right: 16rem; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .pan-m  {  padding: 0; }
  .paxs-m {  padding: .25rem; }
  .pas-m  {  padding: .5rem; }
  .pam-m  {  padding: 1rem; }
  .pal-m  {  padding: 2rem; }
  .pax-m  {  padding: 4rem; }
  .paxl-m {  padding: 8rem; }
  .paxxl-m { padding: 16rem; }

  .pln-m  {  padding-left: 0; }
  .plxs-m {  padding-left: .25rem; }
  .pls-m  {  padding-left: .5rem; }
  .plm-m  {  padding-left: 1rem; }
  .pll-m  {  padding-left: 2rem; }
  .plx-m  {  padding-left: 4rem; }
  .plxl-m {  padding-left: 8rem; }
  .plxxl-m { padding-left: 16rem; }

  .prn-m  {  padding-right: 0; }
  .prxs-m {  padding-right: .25rem; }
  .prs-m  {  padding-right: .5rem; }
  .prm-m  {  padding-right: 1rem; }
  .prl-m  {  padding-right: 2rem; }
  .prx-m  {  padding-right: 4rem; }
  .prxl-m {  padding-right: 8rem; }
  .prxxl-m { padding-right: 16rem; }

  .pbn-m  {  padding-bottom: 0; }
  .pbxs-m {  padding-bottom: .25rem; }
  .pbs-m  {  padding-bottom: .5rem; }
  .pbm-m  {  padding-bottom: 1rem; }
  .pbl-m  {  padding-bottom: 2rem; }
  .pbx-m  {  padding-bottom: 4rem; }
  .pbxl-m {  padding-bottom: 8rem; }
  .pbxxl-m { padding-bottom: 16rem; }

  .ptn-m  {  padding-top: 0; }
  .ptxs-m {  padding-top: .25rem; }
  .pts-m  {  padding-top: .5rem; }
  .ptm-m  {  padding-top: 1rem; }
  .ptl-m  {  padding-top: 2rem; }
  .ptx-m  {  padding-top: 4rem; }
  .ptxl-m {  padding-top: 8rem; }
  .ptxxl-m { padding-top: 16rem; }

  .pvn-m {   padding-top: 0;       padding-bottom: 0; }
  .pvxs-m {  padding-top: .25rem;  padding-bottom: .25rem; }
  .pvs-m {   padding-top: .5rem;   padding-bottom: .5rem; }
  .pvm-m {   padding-top: 1rem;    padding-bottom: 1rem; }
  .pvl-m {   padding-top: 2rem;    padding-bottom: 2rem; }
  .pvx-m {   padding-top: 4rem;    padding-bottom: 4rem; }
  .pvxl-m {  padding-top: 8rem;    padding-bottom: 8rem; }
  .pvxxl-m { padding-top: 16rem;   padding-bottom: 16rem; }

  .phn-m {   padding-left: 0;      padding-right: 0; }
  .pvxs-m {  padding-left: .25rem; padding-right: .25rem; }
  .phs-m {   padding-left: .5rem;  padding-right: .5rem; }
  .phm-m {   padding-left: 1rem;   padding-right: 1rem; }
  .phl-m {   padding-left: 2rem;   padding-right: 2rem; }
  .phx-m {   padding-left: 4rem;   padding-right: 4rem; }
  .phxl-m {  padding-left: 8rem;   padding-right: 8rem; }
  .phxxl-m { padding-left: 16rem;  padding-right: 16rem; }
}

@media screen and (min-width: 64em)  {
  .pan-l  {  padding: 0; }
  .paxs-l {  padding: .25rem; }
  .pas-l  {  padding: .5rem; }
  .pam-l  {  padding: 1rem; }
  .pal-l  {  padding: 2rem; }
  .pax-l  {  padding: 4rem; }
  .paxl-l {  padding: 8rem; }
  .paxxl-l { padding: 16rem; }

  .pln-l  {  padding-left: 0; }
  .plxs-l {  padding-left: .25rem; }
  .pls-l  {  padding-left: .5rem; }
  .plm-l  {  padding-left: 1rem; }
  .pll-l  {  padding-left: 2rem; }
  .plx-l  {  padding-left: 4rem; }
  .plxl-l {  padding-left: 8rem; }
  .plxxl-l { padding-left: 16rem; }

  .prn-l  {  padding-right: 0; }
  .prxs-l {  padding-right: .25rem; }
  .prs-l  {  padding-right: .5rem; }
  .prm-l  {  padding-right: 1rem; }
  .prl-l  {  padding-right: 2rem; }
  .prx-l  {  padding-right: 4rem; }
  .prxl-l {  padding-right: 8rem; }
  .prxxl-l { padding-right: 16rem; }

  .pbn-l  {  padding-bottom: 0; }
  .pbxs-l {  padding-bottom: .25rem; }
  .pbs-l  {  padding-bottom: .5rem; }
  .pbm-l  {  padding-bottom: 1rem; }
  .pbl-l  {  padding-bottom: 2rem; }
  .pbx-l  {  padding-bottom: 4rem; }
  .pbxl-l {  padding-bottom: 8rem; }
  .pbxxl-l { padding-bottom: 16rem; }

  .ptn-l  {  padding-top: 0; }
  .ptxs-l {  padding-top: .25rem; }
  .pts-l  {  padding-top: .5rem; }
  .ptm-l  {  padding-top: 1rem; }
  .ptl-l  {  padding-top: 2rem; }
  .ptx-l  {  padding-top: 4rem; }
  .ptxl-l {  padding-top: 8rem; }
  .ptxxl-l { padding-top: 16rem; }

  .pvn-l {   padding-top: 0;       padding-bottom: 0; }
  .pvxs-l {  padding-top: .25rem;  padding-bottom: .25rem; }
  .pvs-l {   padding-top: .5rem;   padding-bottom: .5rem; }
  .pvm-l {   padding-top: 1rem;    padding-bottom: 1rem; }
  .pvl-l {   padding-top: 2rem;    padding-bottom: 2rem; }
  .pvx-l {   padding-top: 4rem;    padding-bottom: 4rem; }
  .pvxl-l {  padding-top: 8rem;    padding-bottom: 8rem; }
  .pvxxl-l { padding-top: 16rem;   padding-bottom: 16rem; }

  .phn-l {   padding-left: 0;      padding-right: 0; }
  .pvxs-l {  padding-left: .25rem; padding-right: .25rem; }
  .phs-l {   padding-left: .5rem;  padding-right: .5rem; }
  .phm-l {   padding-left: 1rem;   padding-right: 1rem; }
  .phl-l {   padding-left: 2rem;   padding-right: 2rem; }
  .phx-l {   padding-left: 4rem;   padding-right: 4rem; }
  .phxl-l {  padding-left: 8rem;   padding-right: 8rem; }
  .phxxl-l { padding-left: 16rem;  padding-right: 16rem; }
}

```
# License

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

