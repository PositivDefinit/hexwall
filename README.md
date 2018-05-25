
<!-- README.md is generated from README.Rmd. Please edit that file -->
hexwall
=======

The `hexwall.R` file contains one function `gen_hexwall()`, which can be used to generate an image that neatly arranges a folder of hexagons.

There are several arguments allowing some control over the function's operation.

-   path: The path to a folder of hexagon stickers
-   sticker\_row\_size: The number of stickers in the longest row
-   sticker\_width: The width of each sticker in pixels
-   remove\_small: Should hexagons smaller than the sticker\_width be removed?
-   remove\_size: Should hexagons of an abnormal size be removed?

``` r
source("hexwall.R")
#> Linking to ImageMagick 6.9.7.4
#> Enabled features: fontconfig, freetype, fftw, lcms, pango, x11
#> Disabled features: cairo, ghostscript, rsvg, webp
hexwall("samplehex", sticker_row_size = 3, sticker_width = 200)
```

<img src="README_files/figure-markdown_github/example-1.png" width="600" />
