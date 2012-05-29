A hacked up patch to get pngwriter to work with libpng15
========================================================

pngwriter 0.5.4 currently works with libpng1.2

Use this patch to get pngwriter to work with libpng1.5

Read more about pngwriter at

http://pngwriter.sourceforge.net/

_Use at your own risk_

Apply this patch against pngwriter 0.5.4
----------------------------------------

    tar xfv pngwriter-0.5.4.tar.gz
    cd pngwriter-0.5.4
    patch -Np1 -i ../patch_for_png_15.diff
