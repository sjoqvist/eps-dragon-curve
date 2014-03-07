# EPS Bézier Dragon Curve

This repository provides an example of how to draw a fractal
[dragon curve](http://en.wikipedia.org/wiki/Dragon_curve) using
[Bézier curves](http://en.wikipedia.org/wiki/B%C3%A9zier_curve) with short
[EPS](http://en.wikipedia.org/wiki/Encapsulated_PostScript) code. Note that on
close inspection the line doesn't touch itself at any point along its path.

The code is manually written but should comply with the standards. To put the
code through a test, I sent the raw EPS file to a PS 3 emulating laser
printer, and it printed the curve correctly without complaining.

![Dragon curve preview with magnified
cutout](https://raw.github.com/aliquis/eps-dragon-curve/master/preview.png)

To generate this preview PNG, execute

    script/preview-gen

in the project folder.
