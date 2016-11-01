# virtualforest-data

A single day of data as collected in autumn by the [virtualforest.io](http://virtualforest.io) project. This data is freely available for experimentation, creative creations. For full access to the data for scientific and commercial purposes please contact me by email.

The data included is full resolution, unaltered data as per acquisition. The mask.png file allows you to exclude the bottom part of the images which includes the base of the camera mount using the [imagemagick](https://www.imagemagick.org) code bellow.

```bash
convert input.jpg mask.png -compose Multiply -composite output.jpg

```

A description of the camera setup is given in my [photosphere github repository](https://khufkens.github.io/photosphere).

----

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
