A hacked up patch to get pngwriter to work with libpng16
========================================================

pngwriter 0.5.4 currently works with libpng1.4
Use this patch to get pngwriter to work with libpng1.6

_Use at your own risk_

Apply this patch against pngwriter 0.5.4
----------------------------------------

> tar xfv pngwriter-0.5.4.tar.gz
> cd pngwriter-0.5.4
> patch -Np1 -i patch_for_png_16.diff
