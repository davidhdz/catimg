utilities
=========

catimg
---
Utilidad que permite pegar una serie de imágenes en formato vertical u horizontal.
`catimg` utiliza `imagemagick` para procesar las imágenes y agregar bordes automáticamente, pudiendo escoger el tamaño del mismo y color.

    Usage: catimg [options] infiles outfile

    Options:
      --version             show program's version number and exit
      -h, --help            show this help message and exit
      -v, --vertical        vertical arrangement (default)
      -z, --horizontal      horizontal arrangement
      -s number, --size=number
                            size between images, default 0
      -b color, --bgcolor=color
                            background color, default white
